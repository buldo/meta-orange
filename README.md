# meta-orange
This is experimental repo. Do not use it

# How to build for orange
```sh
git clone --recurse-submodules https://github.com/buldo/openhd-yocto-build.git
cd openhd-yocto-build
source poky/oe-init-build-env ./orange-build

# Build demo image
bitbake openhd-ground-image

# Create image file
wic create sunxi-sdcard-image -e openhd-ground-image
```

