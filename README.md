android_local_manifest
======================

Local Manifest for Alcatel OT-995

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-10.1
    curl -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/PatrickPalm/android_local_manifest/cm-10.1/local_manifest.xml
    repo sync

Compile:

    . build/envsetup.sh && lunch cm_cocktail-userdebug
    make bacon -j8


