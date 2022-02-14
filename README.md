# TWRP Samsung Galaxy Tab A8
![Galaxy Tab A8](https://fdn2.gsmarena.com/vv/pics/samsung/samsung-galaxy-tab-a-s-pen-sm-p205-2.jpg "Galaxy Tab A8")
# How-to install dependencies
```
# How-to clone source and device tree:

mkdir -p ~/twrp && cd ~/twrp

$ repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
```
# Clone p205 repo
```
$ git clone https://github.com/topser9/twrp_device_samsung_p205 device/samsung/p205
```
Sync
```
$ repo sync
```
# How-to build:
```
$ export ALLOW_MISSING_DEPENDENCIES=true
 . build/envsetup.sh
 lunch omni_p205-eng
 mka recoveryimage
```
## How to find the image built
```
`cd /out/target/product/p205`
```
see recovery.img
```
# Device Tree for Samsung Galaxy Tab A8 (SM-P205)

Device Tree Made by topser99
```