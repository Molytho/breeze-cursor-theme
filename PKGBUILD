pkgname=breeze-cursors
pkgver=6.4.3
_dirver=$(echo $pkgver | cut -d. -f1-3)
pkgrel=1
arch=(any)
pkgdesc='Cursor files for the Breeze visual style for the Plasma Desktop'
url='https://kde.org/plasma-desktop/'
license=(LGPL)
source=(https://download.kde.org/stable/plasma/$_dirver/breeze-$pkgver.tar.xz{,.sig})
sha256sums=('017a2dadf803a0c2d167489f5ba4d2a0011fc58fcf18c5e76fa6fc22f4844fbf'
            'SKIP')
validpgpkeys=('E0A3EB202F8E57528E13E72FD7574483BB57B18D'  # Jonathan Esk-Riddell <jr@jriddell.org>
              '0AAC775BB6437A8D9AF7A3ACFE0784117FBCE11D'  # Bhushan Shah <bshah@kde.org>
              'D07BD8662C56CB291B316EB2F5675605C74E02CF'  # David Edmundson <davidedmundson@kde.org>
              '1FA881591C26B276D7A5518EEAAF29B42A678C20') # Marco Martin <notmart@gmail.com>

package() {
    cd breeze-$pkgver
    install -dm755 "$pkgdir/usr/share/icons/"
    cp -r cursors/{Breeze/Breeze,Breeze_Light/Breeze_Light} "$pkgdir/usr/share/icons/"
}
