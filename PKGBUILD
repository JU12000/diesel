# DO NOT UPLOAD THIS PACKAGE TO THE AUR!

# Maintainer: JU12000
pkgname=diesel
pkgver=1.0.0
pkgrel=2
pkgdesc="A command line utility for Steam account switching"
arch=('any')
license=('GPL3')
depends=('procps-ng' 'steam')
makedepends=('git')
source=("diesel")
sha256sums=('fd77b8b90b510cdae61332476ac250528860f4d1a574c1527ab1c957dd6c5664')

package() {
	install -Dm755 "${srcdir}/diesel" -t "${pkgdir}/usr/bin"
}
