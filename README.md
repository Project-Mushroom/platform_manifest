[**Miku-UI Snowland**](https://github.com/Miku-UI)

[**中文版**](https://github.com/Project-Mushroom/platform_manifest/blob/snow/READMECN.md)

# Miku UI

![MikuUI](https://raw.githubusercontent.com/Project-Mushroom/platform_manifest/snow/img/MikuUI.png)

Miku UI is an AOSP-Based Project focus on Performance and ... 

> **Miku？**

**How to Start！**

Well...Are you a buildbot?

Then, check [**Our Wiki**](https://github.com/Project-Mushroom/platform_manifest/wiki) before you start！

Sync Sourcecode
------------


```shell
repo init -u https://github.com/Project-Mushroom/platform_manifest -b snow
```


```shell
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```


## Be Careful

> If you are using an ify-only-Device Configuration for building Miku UI , DO NOT RELEASE IT, FOR OWN USE ONLY.
>
> And please DO NOT Public your ify-only-Device Configuration, respect the original author, plz.
>
> DO NOT RELEASE any build of Miku UI based on an ify-only-Device Configuration to any telegram channel or XDA Forum.
> 
> Bcz it's unstable with Miku UI and may lead problems!

After that let's ...

## Start to build！！

```shell
# Init
. build/envsetup.sh

# Lunch
lunch miku_[codename]-[build type]

# Make a diva !
make diva
```


Credits
-------
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**exTHmUI**](https://github.com/exthmui)
 * [**Weeb Project**](https://github.com/WeebProject)
 * [**Dirty Unicorns**](https://github.com/DirtyUnicorns)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**Mokee**](https://github.com/Mokee)
 * [**crDroid**](https://github.com/crdroidandroid)
