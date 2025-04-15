To start syncing with this branch:
```
repo init --partial-clone -b r-x86 -u https://github.com/deboniet/android-x86-manifest
```
```
repo sync -c --no-tags --no-clone-bundle -j$(nproc)
```

**Remember:** All files are downloaded from AOSP and the Android-x86 GitHub mirror. This is only a fix that replaces the old OSDN manifest to work with the GitHub mirror.

If you are searching for some of the kernels or build files, search them on the [SourceForge mirror](https://sourceforge.net/projects/android-x86/) of Android-x86.
