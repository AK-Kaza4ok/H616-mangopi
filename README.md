# H616-mangopi (version 1.2)
DTS file for setting MQ-Quad

[MQ-Quad H616](https://mangopi.org/mqquad)
# Compile DTS fit to DTB binary and reboot

```ps
sudo apt-get install sunxi-tools device-tree-compiler rpi.gpio-common
git clone https://github.com/AK-Kaza4ok/H616-mangopi
cd /boot/dtb/allwinner/
dtc -I dts -O dtb -f sun50i-h616-orangepi-zero2.dts -o sun50i-h616-orangepi-zero2.dtb
```

### features:
* I2C (/dev/i2c-0)
* SPI

