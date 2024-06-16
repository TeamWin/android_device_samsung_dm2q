# TWRP Device Tree for Samsung Galaxy S23+

## For Decryption

[Install Instructions](https://xdaforums.com/t/sm-s916b-0-one-ui-6-1-userdata_aio-odin-flashable-to-remove-encryption-make-rom-rw-install-twrp-root-use-on-stock-firmware-unlocked-bootloaders.4610065/)

# Special Thanks 
[jrkruse](https://xdaforums.com/m/jrkruse.1949695/) For userdata aio script.

[mohammad.afaneh92](https://github.com/afaneh92) For prebuilt image of dm2q.

[Edward](https://github.com/edward0181) For help me.

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/twrp_device_samsung_dm2q device/samsung/dm2q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_dm2q-eng
mka recoveryimage
```