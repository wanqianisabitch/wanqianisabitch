---
description: Make a python notion for  the  nanjing hotday
---

# A python notion

Miss.why遭遇在上安装Python 第三方交互式编辑器Spyder出线了各种问题，总体来说因为macOS的Bigsur系统对于很多数据内容以及软件并不开源。

提出指令

```text
conda create -n spyder-dev python=3
conda activate spyder-dev
conda install -c conda-forge spyder
```

每次需要调出Spyder的时候在终端上输入  

```text
conda activate spyder-dev
export QT_MAC_WANTS_LAYER=1
spyder
```

