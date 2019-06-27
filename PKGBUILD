# Maintainer: your name <youremail@domain.com>
pkgname=zhcal
pkgver=0.1.0
epoch=20170511
pkgrel=5
pkgdesc="Chinese calendar"
arch=("i686" "x86_64")
url="https://github.com/giwhub/zhCal"
license=('MIT') 
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=(
	"https://github.com/giwhub/zhCal/archive/master.zip
")
noextract=()
md5sums=('SKIP')

package() {
	mkdir -p "${pkgdir}/usr/share/license/zhcal"
	mkdir -p "${pkgdir}/usr/local/bin"
	cd "$srcdir/zhCal-master"
	chmod 755 "$srcdir/zhCal-master/zhscal"
	cp "$srcdir/zhCal-master/COPYING" ${pkgdir}/usr/share/license/zhcal
	cp "$srcdir/zhCal-master/zhcal" ${pkgdir}/usr/local/bin
	cp "$srcdir/zhCal-master/zhscal" ${pkgdir}/usr/local/bin
}
