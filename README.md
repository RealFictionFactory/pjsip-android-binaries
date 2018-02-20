# pjsip-android-binaries
Binary files of Android pjsip library compilation

Built from PJSIP 2.7.1 with default configs (APP_PLATFORM=android-21)

# How to use it

1. Put armeabi-v7a (and arm64-v8a if needed) into jniLibs folder (the same level as res and java folders) in appropriate module.
2. Put org folder into java folder in appropriate module
3. Include
```
  static {
        System.loadLibrary("pjsua2");
  }
```

somewhere in your code to load the library.
