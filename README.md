<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-jx3

_这是一个使用 NoneBot 框架编写的插件，提供多种功能如日常查询，预测，金价查询，鲜花，公告，沙盘，jjc，黑市，骚话，奇遇，招募以及多种消息推送功能。_

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/water/nonebot-plugin-jx3.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-jx3">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-jx3.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>


## 📖 介绍

nonebot-plugin-jx3 是一个使用 NoneBot 框架编写的插件，它提供了多种功能，例如日常查询，预测，金价查询，鲜花，公告，沙盘，jjc，黑市，骚话，奇遇，招募以及多种消息推送功能，例如"818", "开服", "新闻", "抓马", "扶摇", "诛恶", "阵营活动提醒", "攻防实况", "玄晶","奇遇","绝世奇遇" 等。

## 💿 安装

<details open>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-jx3

</details>

<details>
<summary>手动安装</summary>
将 none-plugin-jx3 文件夹复制到你的 NoneBot 项目的 plugins 目录下。

在你的 NoneBot 配置文件中，添加插件的导入路径：

plugin_dirs = ["plugins"]

将requirements.txt复制到bot目录，进入bot的虚拟环境，执行：

    pip install -r requirements.txt

安装完成后正常启动bot即可
</details>

## ⚙️ 配置

在 nonebot2 项目的`.env`文件中添加下表中的必填配置

| 配置项 | 必填 | 默认值 | 说明 |
|:-----:|:--:|:---:|:----:|
| jx3api_key | 否  |  空  | jx3.api.com购买的key |
| jx3_tuilan_ticket | 否  |  空  | 推栏ticket |
| jx3wss_token| 否  |  空  | jx3.api.com购买的wss |
| jx3_command_header | 否  |  空  | 指令的前缀，防止和其他插件冲突 |
| jx3_bot_name | 否  | 团团  | api生成图片用的名字 |

第一步使用插件是要绑定服务器。例如：-绑定 绝代天骄

一旦服务器是绑定的，就可以使用各种查询功能。通过-订阅，你可以查询能够订阅的功能。
## 指令示例

| 指令 | 参数 | 指令示例 | 说明 |
|:-----:|:--:|:---:|:----:|
| 剑网三帮助 | 无  |  剑网三帮助  | 获取剑网三插件的帮助信息 |
| 绑定 | 服务器(建议进群运行一次)  |  绑定绝代天骄  | 将服务器绑定到群组 |
| 日常 | 无  |  日常绝代天骄 或 日常 | 获取今天的日常 |
| 预测| 无  |  预测绝代天骄 或 预测 | 获取明天的日常 |
| 金价 | 服务器(可省略，默认取绑定服务器)  |  金价绝代天骄 或 金价  | 获取过去两周的服务器金价 |
| 鲜花 | 服务器(可省略，默认取绑定服务器)  |  鲜花绝代天骄 或 鲜花  | 获取过去两周的服务器鲜花价格 |
| 公告 | 无  |  公告绝代天骄 或 公告 | 获取最新的公告 |
| 沙盘 | 服务器(可省略，默认取绑定服务器)  |  沙盘绝代天骄 或 沙盘 | 获取服务器沙盘 |
| jjc | 模式(22、33、55) | 服务器(可省略，默认取绑定服务器) | 角色名  | jjc 22 绝代天骄 xxx 或 jjc 22 xxx | 获取jjc战绩 |
| 黑市 | 无  |  黑市 | 获取时装价格 |
| 骚话 | 无  |  骚话 | 随即一条骚话 |
| 奇遇 | 服务器(可省略，默认取绑定服务器) | 角色名  | 奇遇 绝代天骄 xxx 或 奇遇 xxx | 获取角色奇遇记录 |
| 招募 | 服务器(可省略，默认取绑定服务器) | 关键词(支持模糊搜索，可省略，省略返回所有招募)  | 招募 绝代天骄 名剑 或 招募 名剑 | 获取服务招募 |

开发者:water

qq:415276785

感谢 绝代天骄-白首亦同归-帮主 赞助api测试。
