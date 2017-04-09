## Hackintosh Config

### Support version

macos sierra 10.12.3

Clover r3766

### Hardware

- Motherboard: ASUS PRIME B250M-PLUS
  - Audio: Realtek® ALC887 8-Channe
  - LAN: Intel® I219V
- CPU: Intel Core i5-7500
- Graphic Card: Sapphire Radeon NITRO+ Rx 480 8GB GDDR5 OC

### **Clover**

drivers:

```
$ ls /Volumes/EFI/EFI/CLOVER/drivers64UEFI
AppleImageCodec-64.efi     FSInject-64.efi         SMCHelper-64.efi
AppleKeyAggregator-64.efi  FirmwareVolume-64.efi   VBoxHfs-64.efi
AppleUITheme-64.efi        OsxAptioFix2Drv-64.efi
DataHubDxe-64.efi          OsxFatBinaryDrv-64.efi
```

kexts:

```
$ ls /Volumes/EFI/EFI/CLOVER/kexts/Other
AppleALC.kext  Lilu.kext
```

[https://github.com/vit9696/AppleALC](https://github.com/vit9696/AppleALC)

[https://github.com/vit9696/Lilu](https://github.com/vit9696/Lilu)

### More Info

[http://twi1ight.com/2017/03/hackintosh-install/](http://twi1ight.com/2017/03/hackintosh-install/)