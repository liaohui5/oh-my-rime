## [fork from oh-my-rime](https://github.com/Mintimate/oh-my-rime)

![样式](demo.webp)

一套快速初始化 rime 的模板，因为平时我使用 `oh-my-zsh`，在使用 rime 时候，有种用`omz`的感觉；所以我给它取名叫`oh-my-rime`，你也可以叫它`薄荷拼音`，亦或者`Mint`。

## Oh-my-rime 指南

rime 配置教程：

- [跨平台的开源输入法 Rime 定制指南，打造强大的个性化输入法](https://www.mintimate.cn/2023/03/18/rimeQuickInit)
- [Bilibili 視頻: https://www.bilibili.com/video/BV12M411T7gf](https://www.bilibili.com/video/BV12M411T7gf)
- [Youtube 視頻: https://www.youtube.com/watch?v=yc4AivDDpMM](https://www.youtube.com/watch?v=yc4AivDDpMM)

如果你有 QQ 帐号，可以加入群聊（禁止广告）: 703260572

### 安装

以下教程，适用于 Linux、macOS 和 Windows（Xp~）

0. 安装[Rime 输入法](https://rime.im/)并注销或重启电脑；
1. 下载本仓库所有配置文件到本地 rime 配置文件；
2. 重新部署 Rime（Windows、Linux 可能需要配置分词依赖才可以使用 EasyEN，参考：[EasyEn](https://github.com/BlindingDark/rime-easy-en)）
3. 开始使用

## Tips

本地 rime 配置文件默认地址，如下

- Windows
  - Weasel: `%APPDATA%\Rime`
- Mac OS X
  - Squirrel: `~/Library/Rime`
- Linux
  - iBus:` ~/.config/ibus/rime`

本地 rime 日志文件默认地址如下：

- Windows
  - Weasel: `%TEMP%`
- Mac OS X
  - Squirrel: `$TMPDIR`
- Linux
  - iBus:` /tmp`

## 配置文件说明

- `default.custom.yaml` 设置输入法、如何切换输入法、翻页等
- `double_pinyin_flypy.custom.yaml` 双拼方案，
- `squirrel.custom.yaml` 鼠须管( Mac 版本 )设置哪些软件默认英文输入，输入法皮肤等
- `weasel.custom.yaml` 小狼毫( Win 版本 )设置哪些软件默认英文输入，输入法皮肤等
- `custom_phrase.txt` 设置快捷输入，修改完成后要重新部署才能生效

配置文件中大部分都有注释。

---

## 支持

- [Mintimate's Blog: https://www.mintimate.cn](https://www.mintimate.cn)
- [Mintimate 的爱发电: 加入电圈，支持创造!](https://afdian.net/a/mintimate)
- [Bilibili：@Mintimate](https://space.bilibili.com/355567627)
- [Youtube：@Mintimate](https://www.youtube.com/channel/UCI7LLdUGNzkcKOE7grAqCoA)

## 参考/致谢

1. [Rime-RimeWithSchemata](https://github.com/rime/home/wiki/RimeWithSchemata)
2. [Rime/小狼豪/鼠须管 输入法配置记](https://chenhe.me/post/oh-my-rime)
3. [rime-setting](https://github.com/Iorest/rime-setting)
4. [雾凇拼音 | 长期维护的简体词库](https://github.com/iDvel/rime-ice)

## 推荐项目

- [98 五笔，十分好用的五笔输入方案](http://www.98wubi.com/)
- [雾凇拼音，很优秀的中文词库](https://github.com/iDvel/rime-ice)
