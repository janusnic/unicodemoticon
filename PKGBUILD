#Automatically generated by pip2arch on 2015-06-05

pkgname=python-unicodemoticon
pkgver=1.0.2
pkgrel=1
pkgdesc="Like a Color Picker but for Unicode Emoticons. Trayicon with Unicode Emoticons using Python3 Qt5."
url="https://github.com/juancarlospaco/unicodemoticon"
depends=('python' 'pip')
makedepends=('python3' )
license=('CUSTOM')
arch=('any')
source=('https://pypi.python.org/packages/source/u/unicodemoticon/unicodemoticon-1.0.2.zip')
md5sums=('a44f3d6eecc964fbf9b9eecec8586f12')

build() {
    cd $srcdir/unicodemoticon-1.0.2
    python setup.py build
}

package() {
    cd $srcdir/unicodemoticon-1.0.2
    python setup.py install --root="$pkgdir" --optimize=1 
}
