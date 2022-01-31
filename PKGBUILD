# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=flatex
pkgver=1.0.2
pkgrel=1
pkgdesc="My LaTeX macros etc."
arch=('any')
url="http://www.github.com/ftredget/flatex"
license=('GPL')
depends=('texlive-core')
noextract=()
source=("$pkgname.tar.gz")
install=$pkgname.install
sha256sums=('97a781ac9340e5914b7395a0b0ccfb68d8f2944d5117c080df62a8821c04dbd9')

package() {
  install -dm755 "$pkgdir"/usr/share/texmf
  cp -r flatex/ "$pkgdir"/usr/share/texmf/tex/
}

