# Maintainer: Guten Ye

pkgname="keepass-favicon"
pkgver=1.9.0
pkgrel=3
pkgdesc="A KeePass plugin that downloads and stores favicons. PKGBUILD source code at https://github.com/GutenYe/aur/tree/master/keepass-favicon"
arch=("any")
url="https://sourceforge.net/projects/keepass-favicon/"
license=("GPLv2")
depends=("keepass")
source=("KeePassFaviconDownloader-$pkgver.plgx::http://downloads.sourceforge.net/project/$pkgname/$pkgver/KeePassFaviconDownloader.plgx")

package() {
  cd "$srcdir"

  install -Dm664 KeePassFaviconDownloader-$pkgver.plgx "$pkgdir/usr/share/keepass/KeePassFaviconDownloader.plgx"
}

# vim:set ts=2 sw=2 et:
md5sums=('7b9bbc3196a31213403e2d0eafb1ef0a')
