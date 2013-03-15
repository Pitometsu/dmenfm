# Maintainer: Scott Garrett <Wintervenom@archlinux.us>
# Contributor: Scott Garrett <Wintervenom@archlinux.us>
# Contributor: Michael Floering <michaelfloering@gmail.com>

pkgname=dmenfm
pkgver=0.1.2.1
pkgrel=1
pkgdesc="A simple dmenu-based file manager."
url="http://wintervenom.mine.nu"
arch=('i686' 'x86_64')
license=('GPL')
depends=('dmenu')

#install=($pkgname.install)

source=(
    'dmenfm'
)
md5sums=('2ae3d8a22aec2b7927162b1a71e5d454')

build() {
  cd $srcdir
  mkdir $pkgdir/usr $pkgdir/usr/bin
  cp dmenfm $pkgdir/usr/bin
  chmod a+x $pkgdir/usr/bin/dmenfm

  return 0
}
