# Blaze-AOSP #

<img src="https://raw.githubusercontent.com/Blaze-AOSP/manifest/10.0/blaze_logo.png"> 

## Credits ##

 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**BootleggersROM**](https://github.com/BootleggersROM)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)


## Getting Started ##

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/Blaze-AOSP/manifest -b 10.0
```
## Syncing Source ##

```bash
repo sync --current-branch --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -jX
( X is the number of parallel download repo should do choose depending on your cpu )
```

## Building ##

From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch blaze_<devicecodename>-userdebug
make bacon -jX
```

## Some Links ##

* [**Website**](https://blaze-aosp.github.io/)
* [**Telegram Group**](https://t.me/BlazeAOSP)
