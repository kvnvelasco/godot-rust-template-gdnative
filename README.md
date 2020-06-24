# Godot Rust GDNative Template 

Set up to handle multi target builds for all (TODO) supported godot platforms sans web. 

Currently supported platforms are:
* Linux (X11)
* Android ARMv7
* Android ARM64
* Android x86 32 & 64

## Adding targets 
You may modify the targets listed in `gdnative_rust/.cargo/config` 

## Compiling for android 
Android compilation requires an android SDK and NDK. In the `gdnative_rust/.cargo/config` file
modify the <ANDROID_HOME> placeholder with a the path to your android sdk

## IntelliJ Support

The project also contains all run configurations for building and running godot and the rust app.
You must have the `gdscript` and `rust plugins installed and enabled

