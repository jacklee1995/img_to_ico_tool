# 图片转ico图标文件脚本

**Author**: **李俊才**（jcLee95）

![img](readme_CN.assets/bb869bb0b79b48209c6206043890c985_qq_28550263.png)

**Version**: **1.0.0**
**Email**: 291148484@163.com
**License**: [MIT](/LIENCES)

> 该脚本用于生成 .ico 图标文件。


用法：将你的所有 `png` 文件放在 更目录下的 `sources`目录下，在根目录下的 `config.ini` 配置文件中指定生成图标的大小。
配置文件大概包含以下内容：
```ini
[convert]
source_typr=.png    # .png or .jpg or all
output_size=128x128 
output_format=.ico  # .ico or .png or .jpg
```

其中`output_size`用于指定生成的 icon 大小。在该版本中，其他配置均不可用。注意：`.icon` 格式的图标文件只能是正方形，要求指定的长宽相等，常见的大小例如`16x16`、`32x32`、`64x64`、`128x128`、`256x256`等等。