# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=flatex
pkgver=1.0.9
pkgrel=1
pkgdesc="My LaTeX macros etc."
arch=('any')
url="http://www.github.com/ftredget/flatex"
license=('GPL')
depends=('texlive-core')
noextract=()
source=("$pkgname.tar.gz")
install=$pkgname.install
sha256sums=('a9e45eae1b53f5c6009b89a9b3e2840d2d0451a883c69e9085795e93cb70d057')

package() {
  install -dm755 "$pkgdir"/usr/share/texmf
  cp -r flatex/ "$pkgdir"/usr/share/texmf/tex/
}

