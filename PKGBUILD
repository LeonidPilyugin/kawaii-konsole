# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-konsole
pkgver=1.1
pkgrel=1
pkgdesc='Kawaii konsole.'
arch=('x86_64')
license=('GPL3')
groups=('kawaii')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('69b03bc177ce6989ba38754739275f0c25156b1f13fdce79bd9ed02a1b7c4c50')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/konsole
    install -dm755 $dir
    cp -r $srcdir/* $dir
}

