# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=oneos-icon-theme
pkgver=20140908
pkgrel=1
pkgdesc="This provides to One OS's Icon Theme."
arch=('i686' 'x86_64')
url="http://infinityos.org/"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('bzr')
_realver=0.3.1
provides=("oneos-icon-theme")
source=https://github.com/g97iulio1609/oneos-icon-theme
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/icons
    cp -R OneOS "${pkgdir}"/usr/share/icons
cp -R OneOS-Circle "${pkgdir}"/usr/share/icons

 
}
