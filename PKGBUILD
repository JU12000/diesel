# DO NOT UPLOAD THIS PACKAGE TO THE AUR!

# Maintainer: JU12000
pkgname=diesel
pkgver=1.0.0
pkgrel=1
pkgdesc="A command line utility for Steam account switching"
arch=('any')
license=('GPL3')
depends=('procps-ng' 'steam')
makedepends=('git')
source=("diesel")
sha256sums=('4b54e213fb01f7f0f7cf0717900934389999b40032d8421cf0e9cbc4cce29adc')

package() {
	install -Dm755 "${srcdir}/diesel" -t "${pkgdir}/usr/bin"
}
