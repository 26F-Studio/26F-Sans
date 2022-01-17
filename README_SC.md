# 26F-Sans
26F Studio的主题字体.
**警告: 此字体目前正仍在施工中.**

这个仓库用来存储26F Studio的主题字体——26F Sans. 我们计划未来在26F Studio的游戏和官网中使用这个字体.

## 特性 (计划)

- 多语言支持
- 丰富OpenType特性
- 可变字重和宽度

## 字体家族 (计划)

- 26F Sans
- 26F Mono
- 26F Serif

## 安装

请从Release中下载最新的正式版字体. 你也可以从GitHub Actions中下载最新的预览.

1. 下载并解压26F Sans.

### macOS

2. 使用字体册打开字体文件, 然后点击“安装字体”按钮.

### Linux

2. 将字体文件移至`~/.local/share/fonts`(如果您想要全系统安装字体, 请将其移至`/usr/share/fonts`).
3. 在Terminal运行`fc-cache -f -v`.

### Windows

2. 选择文件夹中的所有字体文件, 右键单击, 然后从菜单中选择 “安装”.

## 编辑

26F Sans的源文件位于`Source`目录中. 要编辑这些文件,

### macOS

1. 下载并安装Glyphs.
2. 使用Glyphs打开`.glyphs`'文件.

### 其他平台

1. 使用您平台上的字体编辑软件打开`.ufo`文件.

## 从源码构建
您可以直接使用Glyphs或其他字体编辑软件构建, 或者使用Google Font Tools (`gftools`)在命令行中构建. 您需要安装Python 3.7来使用`gftools`.

1. 在命令行中执行以下命令来安装`gftools`:
   ```
   $ pip install gftools
   ```
2. 在命令行中进入这个目录:  `../Source/glyphs/`,
3. 执行以下命令:
   ```
   gftools builder config.yaml
   ```
4. 在 `fonts` 文件夹找到构建完成的字体.


## 许可

26F Sans使用[SIL开放字体许可证, V1.1](ofl.txt). 您可以免费使用、修改、重新分发编译后的字体和源文件, 并且不需要提及26F Studio.

本仓库中 [build.yml](.github/workflows/build.yml) 是由 [JetBrains Mono仓库](https://github.com/JetBrains/JetBrainsMono/blob/master/.github/workflows/build-fonts.yml) 改编而来的, 源文件使用 [Apache 2.0 协议](https://www.apache.org/licenses/LICENSE-2.0) 进行授权.

本仓库的其他源代码使用[MIT许可协议](mit.txt).

## Credit

**字体设计**
C29H25N3O5 <michaelgu495@gmail.com>

