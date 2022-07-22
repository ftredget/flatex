# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=flatex
pkgver=1.0.19
pkgrel=1
pkgdesc="My LaTeX macros etc."
arch=('any')
url="http://www.github.com/ftredget/flatex"
license=('GPL')
depends=('texlive-core')
noextract=()
source=("$pkgname.tar.gz")
install=$pkgname.install
sha256sums=('86a50328c4f89f2a56476e952e9002303ab0f9c9f5dfc75b60bb96968090789a')

package() {
  install -dm755 "$pkgdir"/usr/share/texmf
  cp -r flatex/ "$pkgdir"/usr/share/texmf/tex/
}

