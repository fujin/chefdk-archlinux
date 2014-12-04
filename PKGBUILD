# Maintainer: AJ Christensen <aj@junglistheavy.industries>
pkgname=chefdk
pkgver=0.3.5
pkgrel=1
pkgdesc="The Chef development kit, for Arch."
arch=('x86_64')
url="http://downloads.getchef.com/chef-dk/redhat/#/"
license=('Apache')
options=('emptydirs')
source=("https://opscode-omnibus-packages.s3.amazonaws.com/el/6/x86_64/chefdk-0.3.5-1.x86_64.rpm")
md5sums=('d2ad8ac7c1fbe6be1a5043bd43d50b69')

package() {
          msg2 "Moving data from ChefDK RPM Omnibus"
          mv "${srcdir}/opt" "${pkgdir}/opt"
}
