# TWRP for the Samsung Galaxy J7 2017

TWRP device tree for Samsung Galaxy J7 2017 (`j7y17lte`), based on the TWRP AOSP 12.1 manifest.

## Build
```bash
source build/envsetup.sh
lunch twrp_j7y17lte-eng
mka recoveryimage
```
The recovery image is `out/target/product/j7y17lte/recovery.img`.
