LineageOS 14.1 for Sony Xperia Acro S
==============

Build
==============
```
repo init -u https://github.com/soulpower11/local_manifest -b cm-14.1
mkdir .repo/local_manifests/
ln -s ../manifests/local_manifest.xml .repo/local_manifests/local_manifest.xml
repo sync

source build/envsetup.sh

lunch lineage_hikari-userdebug

```
