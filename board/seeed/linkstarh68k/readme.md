# Overview #

* Using kernel 6.4.x, as has support for rockchip 3568 and others
* Using most recent uboot available

## Grabbing ideas and binblobs ##

# Using Buildroot most recent release candidate #
* https://buildroot.org/downloads/buildroot-2023.08-rc3.tar.gz

### OpenWRT ###
* https://github.com/TahomaSoft/openwrt-cronicCorey
     + https://github.com/croniccorey/openwrt
* https://github.com/TahomaSoft/Openwrt-linkstart
     + https://github.com/Linkstar-H-series/Openwrt



### RockChip ###
* https://github.com/TahomaSoft/buildroot.rockchip
     + https://github.com/flatmax/buildroot.rockchip

* https://github.com/TahomaSoft/rockchip-linux-kernel
     + https://github.com/rockchip-linux/kernel


### Other Community Builds ###
* https://github.com/TahomaSoft/rk-ubuntu-build
     + https://github.com/unifreq/rk-ubuntu-build
          - Doesn't build

### Similar Boards ###


* https://github.com/radxa-build
     + https://github.com/radxa-build/rock-3a
     + https://github.com/radxa-build/rock-5b


### Linux ###

Note that this has some not good fiddling (not easy to reproduce)
* https://github.com/TahomaSoft/linux-6.4.13-cajeta
     + forked from kernel.org and plonked with




# Config URLs #




BR2_TARGET_UBOOT_CUSTOM_TARBALL_LOCATION="https://github.com/u-boot/u-boot/archive/refs/tags/v2023.07.02.tar.gz"

BR2_BACKUP_SITE="http://sources.buildroot.net"
BR2_KERNEL_MIRROR="https://cdn.kernel.org/pub"
BR2_GNU_MIRROR="http://ftpmirror.gnu.org"
BR2_LUAROCKS_MIRROR="http://rocks.moonscript.org"
BR2_CPAN_MIRROR="https://cpan.metacpan.org"
