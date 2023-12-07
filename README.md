# oe-manifest
This project is the repo manifest of OpenSTLinux release.
# STM32MP25 Ecosystem STM32MP25-Ecosystem-v5.0.2.BETA tag: <br>openstlinux-6.1-yocto-mickledore-mp2-v23.12.06

# Useful commands
* PC $> mkdir openstlinux-6.1-yocto-mickledore-mp2-v23.12.06
* PC $> cd openstlinux-6.1-yocto-mickledore-mp2-v23.12.06
* PC $> repo init -u https://github.com/PRG-MPU-ALPHA/oe-manifest.git -b refs/tags/openstlinux-6.1-yocto-mickledore-mp2-v23.12.06
* PC $> repo sync
* PC $> DISTRO=openstlinux-weston MACHINE=stm32mp25 source layers/meta-st/scripts/envsetup.sh
* PC $> bitbake st-image-weston
