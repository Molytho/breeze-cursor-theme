pkgname=breeze-cursor-theme
pkgver=5.23.5
pkgrel=1
arch=(any)
pkgdesc='Cursor for the Breeze visual style'
url='https://kde.org/plasma-desktop/'
license=(LGPL)
source=(https://download.kde.org/stable/plasma/$pkgver/breeze-$pkgver.tar.xz)
sha256sums=('2ca2a05b786ccd051e8cb1b0ac665d9443790cfaf15054359fa9adf9613edcdf')

package() {
  install -d "$pkgdir/usr/share/icons/"
  cp "breeze-$pkgver/cursors/Breeze/Breeze/" "$pkgdir/usr/share/icons/" -r
  cp "breeze-$pkgver/cursors/Breeze_Snow/Breeze_Snow/" "$pkgdir/usr/share/icons/" -r
}
