# Maintainer: trile7 at gmail dot com

pkgname=pdftools
pkgver=0.2.3
pkgrel=3
pkgdesc="Bash script for merge, split, extract, and convert pdf to jpg or text using ghostscript"
url="http://bashscripts.googlecode.com"
arch=('i686' 'x86_64')
license=('GPL3')
depends=(coreutils bash ghostscript)
source=(http://gurleegirl.com/bashscripts/$pkgname-$pkgver.tar.gz)

package() {
  mkdir -p "$pkgdir/usr/share/$pkgname"
  mkdir -p "$pkgdir/usr/bin"
  cp "$srcdir/$pkgname-$pkgver"/* "$pkgdir/usr/share/$pkgname"
  mv "$pkgdir/usr/share/$pkgname/$pkgname" "$pkgdir/usr/bin"
}

md5sums=('26602d2b1218380a89fcd2429522e66a')
