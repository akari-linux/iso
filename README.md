# Akari Linux ISO Builder

This is the Akari Linux ISO builder, forked from [rhino-linux/os](https://github.com/rhino-linux/os) which creates ISO images from scratch. To set up the builder:

The resulting ISO, if successful, will be located in builds/`$ARCH`. The builder should automatically detect whether to build on ARM64 or AMD64, depending on the machine you run it on. **32-bit images are unsupported.**

This build system creates the images using `lb`/live-build with debootstrap to create images with configuration in `etc` folder.
