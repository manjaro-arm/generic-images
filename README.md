# Manjaro ARM Generic Aarch64
[![iso_build](https://github.com/manjaro-arm/generic-images/workflows/image_build_all/badge.svg)](https://github.com/manjaro-arm/generic-images/actions)

## description

Development Branch for Manjaro ARM images for Generic Aarch64 images

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm/generic-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d generic -e $EDITION`

## prerequisites

* Functioning firmware (u-boot or tow-boot) on the boards SPI flash

Tow-boot images for the SPI flash for your board can be downloaded from [the projects github page](https://github.com/Tow-Boot/Tow-Boot/releases)

## tested devices

This image has been tested to be working on the following devices:

* Pine64-LTS (by Dan Johansen)
* Pinephone Community Edition (by Benedikt Wildenhain)
