<img src="https://one.revtechs.me/assets/img/logo.png">

# OneOS AOSP

 Getting Started
---------------
To get started with the OneOS AOSP sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/OneOS-AOSP/android_manifest.git -b 12
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch oneos_devicecodename-buildtype
```

Start compilation

```bash
m otapackage
```

OR

```bash
m bacon
```	 

[Apply for Maintainership {COMMING SOON}](https://#)

---------------------------------------------------------------------------------------------------------------------

[OneOS AOSP Website](https://aosp.revtechs.me/) 

---------------------------------------------------------------------------------------------------------------------
