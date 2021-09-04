Getting started with ONEOS AOSP
====================

![ONEOS AOSP](https://one.revtechs.me/assets/img/logo.png)

Initialize Local Repository
-------------
```bash
  repo init -u git@github.com:OneOS-AOSP/android_manifest -b 11
```

Syncing Repository
-------------
```bash
  repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

Lunch Command
-------------
```bash
  . build/envsetup.sh
  lunch one_<device_codename>-buildtype
  mka one
```
