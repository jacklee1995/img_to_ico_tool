# Script for Converting Images to ICO Icon Files

**Author**: **Juncai Li** (**jcLee95**)

![img](readme.assets/bb869bb0b79b48209c6206043890c985_qq_28550263.png)

**Version**: **1.0.0**
**Email**: 291148484@163.com
**License**: [MIT](/LIENCES)

> This script is used to generate .ico icon files.

Usage: Place all your `png` files in the `sources` directory under the root directory, and specify the size of the generated icons in the `config.ini` configuration file under the root directory.
The configuration file contains the following content:

```ini
[convert]
source_typr=.png    # .png or .jpg or all
output_size=128x128 
output_format=.ico  # .ico or .png or .jpg
```

Where `output_size` is used to specify the size of the generated icon. In this version, other configurations are not available. Note: Icon files in `.ico` format must be square, requiring the specified width and height to be equal, common sizes include `16x16`, `32x32`, `64x64`, `128x128`, `256x256`, and so on.

