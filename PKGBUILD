# DO NOT UPLOAD THIS PACKAGE TO THE AUR!

# Maintainer: JU12000
pkgname=diesel-git
pkgver=1.0.0
pkgrel=1
pkgdesc="A command line utility for Steam account switching"
arch=('any')
url="ssh://git@github.com/JU12000/diesel"
license=('GPL3')
depends=('procps-ng' 'steam')
makedepends=('git')
source=("$pkgname::git+$url")
sha256sums=('SKIP')

pkgver() {
	cd "$pkgname"
	git describe --long --tags | sed 's/^v//;s/\([^-]*-g\)/r\1/;s/-/./g'
}

package() {
	cd "$pkgname"
	install -Dm755 diesel -t "${pkgdir}/usr/bin"
}
