## 有关更新：

目前正在尝试使用Github Actions自动更新，也诚征collaborators维护该仓库、诚征赞助的CDN厂商。

> 更新日期：2022年1月19日

# Jellyfin插件仓库加速镜像

## 1. 相关软件及版权申明

[Jellyfin](https://github.com/jellyfin/jellyfin) 是一个免费的媒体系统，可让您控制管理和流式传输媒体。您可以在 [homepage](https://jellyfin.media/)上找到更多的相关讯息。

该仓库镜像了 ~~2021年08月17日~~ 2022年1月19日的[官方仓库](https://repo.jellyfin.org/releases/plugin/manifest-stable.json)内含的所有插件，并上传至本仓库。注意删除了部分插件的过于古旧的版本，对于这些旧版本目前仍停留在本仓库，可至`official-stable-old`文件夹寻找。

~~加速方式采用[jsDelivr](https://www.jsdelivr.com/)的Github仓库加速功能。~~

2021年12月20日大陆CDN网宿断开jsd对国内的连接，目前本仓库将仍保持jsd加速，同时新增本人自提供的cdn作为后备保证。

仓库内所有插件版权归各自的作者所有，若有侵犯到您的权益，请[联系我](mailto:LxnChan@Outlook.com)删除。

豆瓣刮削插件同步自[jellyfin-plugin-douban](https://github.com/Libitum/jellyfin-plugin-douban)，所有权利归属于作者所有。截至2022年01月19日该插件尚未更新，保持原有版本不变。

~~**该加速仓库可用于jsDlivr可用的任何国家和地区，但主要是服务因各种情况下导致网络不佳的中国。若您可以直接连接到Jellyfin的官方仓库请使用官方源！**~~

能用jsd用jsd，jsd不行就用我提供的cdn版本。

**该仓库仅在测试环境通过，生产环境由于不再使用该软件所以未进行持久性使用，错误在所难免，若遇到错误可联系我解决！**

## 2. 官方稳定仓库使用方式

主界面→控制台→插件→存储库，填写如下地址（任选其一）

```link
# jsDelivr 加速
https://cdn.jsdelivr.net/gh/LxnChan/jellyfin-plugin-mirror@{VersionTag}/plugin/manifest-stable-jsd.json

# Flow.lxnchan.cn 加速
https://flow.lxnchan.cn/jellyfin-plugin-mirror/manifest-stable-flow.json
```

> 其中{VersionTag}为[Release](https://github.com/LxnChan/jellyfin-plugin-mirror/releases)页面下的Tag版本号，建议使用Latest版本。

## 3. 豆瓣刮削插件

主界面→控制台→插件→存储库，填写如下地址（任选其一）

```link
# jsDelivr 加速
https://cdn.jsdelivr.net/gh/LxnChan/jellyfin-plugin-mirror@{VersionTag}/douban/manifest.json

# Flow.lxnchan.cn 加速
https://flow.lxnchan.cn/jellyfin-plugin-mirror/douban/manifest-flow.json
```

> 其中VersionTag为[Release](https://github.com/LxnChan/jellyfin-plugin-mirror/releases)页面下的Tag版本号，建议使用20210817c版本。

## 4. 支持我

多访问访问我的blog`https://lxnchan.cn`就行，侧边栏有赞助二维码，感兴趣就扫，不感兴趣随便看看也行。

# Mirror for Jellyfin Plugin Repo

## Related software and copyright notice

Jellyfin is a Free Software Media System that puts you in control of managing and streaming your media. You can find more information in the homepage.

This Repo mirrors all the plugins contained in the official Repo on ~~August 17, 2021~~ January 19, 2022, and uploads them to this Repo.

~~The acceleration method uses the Github repository acceleration function of jsDlivr.~~

The copyrights of all plugins in the Repo belong to their respective authors. If your rights are violated, please contact me to delete them.

~~**The accelerated warehouse can be used in any country and region where jsDlivr is available, but it mainly serves China where the network situation is worrying due to GFW. If you can directly connect to the official repository of Jellyfin, please use the official source!**~~
