pkgname=tmpdebian
pkgver=1.1.1
pkgrel=1
pkgdesc="Part of the tmplinux suite. Temporary Arch Linux"
arch=('any')
url="https://github.com/TheOddCell/tmpdebian"
license=('MIT')
depends=('bash' 'debootstrap' 'shadow' 'util-linux' 'systemd' 'squashfs-tools')
makedepends=()
source=('tmpdebian')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpdebian "$pkgdir/usr/bin/tmpdebian"
}
