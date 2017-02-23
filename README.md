# Toolchain-icestorm

## Introduction

Static binaries of the **Icestorm** tools (yosys, arachne, icetools and icotools). Packaged for [Apio](https://github.com/FPGAwars/apio) and [Platformio](http://platformio.org/).

## Usage

Build:

```
bash build.sh "linux_x86_64 linux_i686"
```

Clean:

```
bash clean.sh "linux_x86_64 linux_i686"
```

Target architectures:
* linux_x86_64
* linux_i686
* linux_armv7l
* linux_aarch64
* windows_x86
* windows_amd64
* darwin

Final packages will be deployed in the **\_packages/build_ARCH/** directories.

NOTE: *libftdi1.a* and *libusb-1.0.a* files have been generated for each architecture using the [Tools-system scripts](https://github.com/FPGAwars/tools-system).
# Documentation

[The project documentation is located in the wiki](https://github.com/FPGAwars/toolchain-icestorm/wiki).

# Authors

* [Jesús Arroyo Torrens](https://github.com/Jesus89)
* [Juan González (Obijuan)](https://github.com/Obijuan)

## License

Licensed under a GPL v2 and [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
