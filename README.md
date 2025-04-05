# Mac 跨平台兼容字体 Mac Cross-Platform Compatible Fonts

Mac 用户在处理 Windows 下编辑的文档时，会遇到字体的兼容性问题，常见字体如仿宋GB_2312、方正小标宋、楷体_GB2312等，如果不安装经过特殊处理的字体，将无法正常识别。该仓库修复了仿宋GB2312在打印或导出PDF时会字体变形的问题。

Mac users often encounter font compatibility issues when working with documents edited on Windows, particularly with common fonts like FangSong GB_2312, FangZheng XiaoBiaoSong, and KaiTi_GB2312. Without specially processed fonts, these cannot be properly recognized. This repository fixes the issue where FangSong GB2312 becomes distorted when printing or exporting to PDF.

## 使用方法 Usage

### 安装 Installation


下载，并使用 MacOS 自带的 Font Book 安装。

如果安装过同名的字体，请删除并清空缓存后再行安装。


Download and install using MacOS's built-in Font Book.

If you have installed fonts with the same name, please delete them and clear the cache before installing.

|Font Name 字体名称|Download Link 下载地址|
|-------|-------|
|FangZheng XiaoBiaoSong_GBK 方正小标宋_GBK|[Download 下载](https://github.com/z-jack/macfonts/raw/master/Fonts/MacFZXBSGBK.ttf)
|FangZheng XiaoBiaoSong Simplified 方正小标宋简体|[Download 下载](https://github.com/z-jack/macfonts/raw/master/Fonts/MacFZXBSJT.ttf)
|FangSong_GB2312 仿宋_GB2312|[Download 下载](https://github.com/z-jack/macfonts/raw/master/Fonts/MacFSGB2312.ttf)
|KaiTi_GB2312 楷体_GB2312|[Download 下载](https://github.com/z-jack/macfonts/raw/master/Fonts/MacKTGB2312.ttf)

### 清空字体缓存 Clearing Font Cache

以下命令可能会报错，但经过测试仍可正常刷新字体缓存。

The following command may show an error, but testing has shown it still successfully refreshes the font cache.

```bash
sudo atsutil databases -remove
```

## 版权说明 Copyright Notice


* 所有字体仅可用于个人学习交流，如未获得版权方授权，请在24小时内删除字体，否则后果自负。
* 任何人不得分发、销售及用作其他商业用途，否则将承担法律后果。
* 字体版权归原版权方所有，侵删。

* All fonts are for personal study and communication only. If you have not obtained authorization from the copyright owner, please delete the fonts within 24 hours, or you will be responsible for the consequences.
* No one may distribute, sell, or use these fonts for other commercial purposes, or they will bear legal consequences.
* The font copyright belongs to the original copyright owner. Will be removed if infringing.

## 致谢 Acknowledgments


感谢@guorenxi提供的[原始字体文件仓库](https://github.com/guorenxi/MacFonts)，以及@iAladdin提供的[修复仿宋字体文件](https://github.com/guorenxi/MacFonts/issues/1)


Thanks to @guorenxi for providing the [original font file repository](https://github.com/guorenxi/MacFonts), and @iAladdin for providing the [fixed FangSong font file](https://github.com/guorenxi/MacFonts/issues/1)