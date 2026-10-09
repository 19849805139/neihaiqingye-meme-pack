# 内海青叶表情包

面向 AstrBot `meme_manager` 的「内海青叶」表情资源包，共收录 7 张静态图片，按聊天语义整理为 7 个类别。

## 安装

在 AstrBot 表情包管理器的资源广场中安装，或使用以下 GitHub 仓库地址安装：

```text
https://github.com/19849805139/neihaiqingye-meme-pack
```

也可以把本目录整个复制到 `AstrBot/data/plugin_data/meme_manager/packs/` 下，并在 `registry.json` 中登记。

## 目录结构

```text
manifest.json
memes_data.json
memes/<category>/<image files>
previews/cover.jpg
source_index.json
```

## 分类

| 分类 | 用途 |
| --- | --- |
| `happy` | 开心、欢呼、庆祝、事情顺利、期待好消息 |
| `sad` | 难过、委屈、哭泣、受挫、歉意 |
| `speechless` | 无语、沉默、不知道该怎么接话 |
| `sleep` | 困倦、想睡觉、熬夜、太累想休息 |
| `refuse` | 嫌弃、拒绝、让对方别过来 |
| `bored` | 无聊、不想继续、想先离开、告辞 |
| `shy` | 害羞、脸红、被夸、被摸头、不好意思 |

分类描述存放在 `manifest.json` 与 `memes_data.json` 中，供 `meme_manager` 构建提示词并按聊天语境选择图片。

## 使用与版权

本仓库仅用于非商业表情包使用与技术交流。角色、原始画面及相关素材版权归各自权利人所有。如权利人要求移除相关内容，请提交 Issue 联系维护者。

## 维护

想替换或补充图片时，直接把图片放进对应 `memes/<category>/` 目录，并同步更新 `manifest.json` 与 `memes_data.json` 中的分类描述即可。
