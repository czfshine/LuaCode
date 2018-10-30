# LuaCode
一些工具代码，旨在方便理解Lua的字节码。
> 改造自Lua5.3.5官方的解释器。

包括一些工具可将lua脚本编译成字节码，还有查看，编辑，运行lua字节码的一系列工具集。主要是为了方便写一个Lua的翻译器（从lua代码到字节码）而衍生出的工具。

# 功能&需求

我们触及的数据有三种，一种是lua文本形式的源码。一种是人类可读的字节码形式(lasm Lua
Assembly)，另外一种是二进制的字节码，可以直接在虚拟机运行的。

相互转化：

|/ | lua  | lasm | bin  |
| ---- | ---- | ---- | ---- |
| lua | - | x | x |
| lasm | ok | - | ok |
| bin | ok | ok | - |




#   build

todo

# usage

todo

# 协议
和Lua一样使用MIT
