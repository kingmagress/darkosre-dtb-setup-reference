# darkosre-dtb-setup-reference

## Introduction
These are my setup steps for transitioning from ArkOS to dARKOSRE. I have R36S v21 (Panel 4).

## Steps and details - For BOOT-ArkOS-AEUX [Recommended as it uses 60hz]
1. Copy the R36S ArkOS-AEUX files - rk3326-r35s-linux.dtb, rk3326-rg351mp-linux.dtb, rg351mp-kernel.dtb
2. Paste it in the formatted dARKOSRE boot partition.
3. Update boot.ini to reference rk3326-r35s-linux.dtb. Do not reference rk3326-rg351mp-linux.dtb.
    - Change rk3326-r36s-linux.dtb to rk3326-r35s-linux.dtb
4. Rename rg351mp-kernel.dtb to rg351mp-uboot.dtb

## Steps and details - For BOOT-Factory (files that came straight from the factory) [Not recommended as it uses 77hz]
1. Copy the R36S stock(ArkOS) files - gameconsole-r36s.dtb, rk3326-rg351mp-linux.dtb, rg351mp-kernel.dtb
2. Paste it in the formatted dARKOSRE boot partition.
3. Update boot.ini to reference rk3326-rg351mp-linux.dtb. Do not reference gameconsole-r36s.dtb directly.
    - Change rk3326-r36s-linux.dtb to rk3326-rg351mp-linux.dtb
4. Rename rg351mp-kernel.dtb to rg351mp-uboot.dtb

## Alternately
1. Copy over the files from this repository's respective BOOT folder over to the formatted dARKOSRE boot partition.

## Boot-Factory
![alt text](image.png)

## BOOT-ArkOS-AEUX
![alt text](image-1.png)

