pkgname=breeze-cursor-theme
pkgver=5.26.2
pkgrel=1
arch=(any)
pkgdesc='Cursor for the Breeze visual style'
url='https://kde.org/plasma-desktop/'
license=(LGPL)
source=(https://download.kde.org/stable/plasma/$pkgver/breeze-$pkgver.tar.xz)
sha256sums=('5dd27b88a9fe92f785badf12151c30201edbd2a65756e9d714358e85f5586de5')

package() {
  install -d "$pkgdir/usr/share/icons/"
  cp "breeze-$pkgver/cursors/Breeze/Breeze/" "$pkgdir/usr/share/icons/" -r
  cp "breeze-$pkgver/cursors/Breeze_Snow/Breeze_Snow/" "$pkgdir/usr/share/icons/" -r
}
