# darkosre-setup-reference

## Steps and details
1. Copy the R36S stock(ArkOS) files - gameconsole-r36s.dtb, rk3326-rg351mp-linux.dtb, rg351mp-kernel.dtb
2. Paste it in the formatted dARKOSRE boot partition.
3. Update boot.ini to reference rk3326-rg351mp-linux.dtb. Do not reference gameconsole-r36s.dtb directly.
    - Change rk3326-r36s-linux.dtb to rk3326-rg351mp-linux.dtb
4. Rename rg351mp-kernel.dtb to rg351mp-uboot.dtb

## Alternately
1. Copy over the files from this repository's BOOT folder over to the formatted dARKOSRE boot partition.

![alt text](image.png)