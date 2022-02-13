# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=flatex
pkgver=1.0.6
pkgrel=1
pkgdesc="My LaTeX macros etc."
arch=('any')
url="http://www.github.com/ftredget/flatex"
license=('GPL')
depends=('texlive-core')
noextract=()
source=("$pkgname.tar.gz")
install=$pkgname.install
sha256sums=('95ae5241553acacb4fff16d08bb5b714a85d617afd2cd1872a13ba5f5207d0da')

package() {
  install -dm755 "$pkgdir"/usr/share/texmf
  cp -r flatex/ "$pkgdir"/usr/share/texmf/tex/
}

