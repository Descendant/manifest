# Descendant 

## Dependencies
Before getting started, please be sure to have the following packages in your OS:

```bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev openjdk-8-jdk libwxgtk3.0-dev```

## Init our repo
To start your own descendance, begin with:

```repo init -u https://github.com/Descendant/manifest.git -b TwoDotThree```

Then sync it up with:

```repo sync```

## Get at work 
To begin your build please do as follows:

```. build/envsetup.sh 
lunch treble_arm64_avN-userdebug
make systemimage
```
## Variants
Use ```treble_arm64_avN``` for an ARM64 A build. 

Use ```treble_arm64_bvN``` for an ARM64 AB build. 

Use ```treble_arm_avN``` for an ARM A build. 

Or use ```treble_a64_avN``` for an ARM, 64 Binder build.

## Contributing 
We do appreciate contributions to our source. 

In any form. 

If you'd wish to bring-up a device specific image for your device, please, consider heading to our Telegram chat

([click to visit Descendant website](https://descendant.me/) to find it out) or just PR the necessary commits over our repos.
