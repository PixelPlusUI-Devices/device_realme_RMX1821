# Realme 3/3i Device Tree
Realme 3/3i (RMX1821, RMX1823, RMX1825, RMX1827) are mid-range smartphones launched by Realme in March and July of 2019 respectively

![Realme 3/3i](https://www.gizmochina.com/wp-content/uploads/2019/04/Realme-3-MT6771-500x500.jpg "Realme 3/3i")

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | Octa-core 2.0/2.4 GHz MT6771/MT6771T Mediatek Helio P60/P70
GPU     | Mali-G72 MP3
Memory  | 3/4 GB RAM
Shipped Android Version | 9.0 ColorOS, upgraded to 10.0 RealmeUI
Storage | 32GB/64GB
Battery | 4230 mAh
Display | 6.22" 720 x 1520 px PPI 271
Rear Camera | 13 MP, f/1.8, 1/3.1", 1.12µm, PDAF and 2 MP (depth)
Front Camera | 13 MP, f/2.0, (wide), 1/3.1", 1.12µm

---

This device tree can be used to build PixelPlusUI for Realme 3/3i devices with RealmeUI vendor

## Applying [patches](https://github.com/PixelPlusUI-Devices/device_realme_RMX1821/tree/eleven/patches/build/make) in their respective directories of ROM source is mandatory.

## For IMS,
## clone [vendor_mediatek_ims](https://github.com/Los-FE/vendor_mediatek_ims) into vendor/mediatek/ims and
## clone [vendor_mediatek_interfaces](https://github.com/Los-FE/vendor_mediatek_interfaces) into vendor/mediatek/interfaces

## For RealmeParts,
## Clone [packages/apps/RealmeParts](https://github.com/Realme-G70-Series/android_packages_apps_RealmeParts) into packages/apps/RealmeParts
