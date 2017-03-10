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
md5sums=('e805c7aa11493c7186759e0427522e9b'
         '3435bd077a530ac28c3ef5c8a63d05d5')

package() {
  install -Dm644 "${srcdir}/opensm-all.service" "${pkgdir}/usr/lib/systemd/system/opensm-all.service"
  install -Dm755 "${srcdir}/opensm-all.launch" "${pkgdir}/usr/bin/opensm-all.launch"
}
