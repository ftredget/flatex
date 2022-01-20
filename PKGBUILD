# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=flatex
pkgver=1.0.1
pkgrel=1
pkgdesc="My LaTeX macros etc."
arch=('any')
url="http://www.github.com/ftredget/flatex"
license=('GPL')
depends=('texlive-core')
noextract=()
source=("$pkgname.tar.gz")
install=$pkgname.install
sha256sums=('c47f359e9eabab4ab8635b34c7838a2226feba0da6a3a77cb71bf23fff4a5a15')

package() {
  install -dm755 "$pkgdir"/usr/share/texmf
  cp -r flatex/ "$pkgdir"/usr/share/texmf/tex/
}

