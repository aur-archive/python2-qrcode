# Contributor: Francois Boulogne <fboulogne at april dot org>
# Maintainer: Francois Boulogne <fboulogne at april dot org>

pkgname=python2-qrcode
pkgver=5.1
pkgrel=1
pkgdesc="Python library to generate QR codes"
arch=('any')
url="https://github.com/lincolnloop/python-qrcode"
license=('BSD')
depends=('python2-pillow' 'python2' 'python2-six')
makedepends=('python2-setuptools')
source=(http://pypi.python.org/packages/source/q/qrcode/qrcode-${pkgver}.tar.gz)

package() {
  cd "$srcdir/qrcode-$pkgver"
  python2 setup.py install --root="${pkgdir}" --optimize=1
}

# vim:ts=2:sw=2:et:
md5sums=('1f20223419bbf992208ada0c12ed4577')
