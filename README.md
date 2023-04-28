# oe-manifest
This project is the repo manifest of OpenSTLinux release.
# STM32MP25 Ecosystem ALPHA V0.2.0 tag: <br>openstlinux-5.15-yocto-kirkstone-mp2-v23.04.26

# Useful commands
* PC $> mkdir openstlinux-5.15-yocto-kirkstone-mp2-v23.04.26
* PC $> cd openstlinux-5.15-yocto-kirkstone-mp2-v23.04.26
* PC $> repo init -u https://github.com/PRG-MPU-ALPHA/oe-manifest.git -b refs/tags/openstlinux-5.15-yocto-kirkstone-mp2-v23.04.26
* PC $> repo sync
* PC $> DISTRO=openstlinux-weston MACHINE=stm32mp25 source layers/meta-st/scripts/envsetup.sh
* PC $> bitbake st-image-weston
