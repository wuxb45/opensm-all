# Maintainer: Xingbo Wu <wuxb45@gmail.com>

pkgname=opensm-all
pkgver=1
pkgrel=1
pkgdesc='Start opensm on all ports'
arch=('x86_64' 'i686')
url='https://www.openfabrics.org/index.php/overview.html'
license=('GPL2' 'custom:"Open Fabrics Alliance BSD"')
depends=('opensm')
source=('opensm-all.service'
        'opensm-all.launch')
md5sums=('SKIP'
         'SKIP')

package() {
  install -Dm644 "${srcdir}/opensm-all.service" "${pkgdir}/usr/lib/systemd/system/opensm-all.service"
  install -Dm755 "${srcdir}/opensm-all.launch" "${pkgdir}/usr/bin/opensm-all.launch"
}
