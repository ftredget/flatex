# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=flatex
pkgver=1.0.20
pkgrel=1
pkgdesc="My LaTeX macros etc."
arch=('any')
url="http://www.github.com/ftredget/flatex"
license=('GPL')
depends=('texlive-core')
noextract=("flatex.sty" "LICENSE")
source=("flatex.sty" "LICENSE")
install=$pkgname.install
sha256sums=('1742a411109cbb2a33ea98129dfdf25431959f28a8b6676a4365962ad707ea61'
            '3972dc9744f6499f0f9b2dbf76696f2ae7ad8af9b23dde66d6af86c9dfb36986')

package() {
  install -dm755 "$pkgdir/usr/share/texmf"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm755 flatex.sty "$pkgdir/usr/share/texmf/tex/flatex.sty"
}

