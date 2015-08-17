# Contributor: TDY <tdy@gmx.com>
# Maintainer: cuihao <cuihao dot leo at gmail dot com>

pkgname=ttf-hanazono
pkgver=20120421
pkgrel=1
pkgdesc='A free Japanese kanji font, which contains about 78,685 characters (and 2 SPACEs) defined in ISO/IEC 10646 standard / the Unicode standard.'
arch=('any')
url="http://fonts.jp/hanazono/"
license=('custom')
depends=('fontconfig' 'xorg-font-utils')
install=ttf-hanazono.install
source=("http://sourceforge.jp/frs/redir.php?m=iij&f=%2Fhanazono-font%2F55644%2Fhanazono-20120421.zip")
md5sums=('abf31bc5cc0c7997a24d3305208b5192')

build() {
  cd "$srcdir"
  install -Dm644 HanaMinA.ttf "$pkgdir/usr/share/fonts/TTF/HanaMinA.ttf"
  install -Dm644 HanaMinB.ttf "$pkgdir/usr/share/fonts/TTF/HanaMinB.ttf"
  install -Dm644 LICENSE.txt "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
