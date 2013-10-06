**SteamBot** 是一个用C#写的进行steam聊天及交易互动的机器人.  项目源地址为https://github.com/Jessecar96/SteamBot.

**不用从github直接下载zip文件!**

请使用git下载项目. *下载zip是没用的* 因为项目是需要其他模块的,zip文件不包括这些模块.

请按如下步骤操作:

1. 使用git工具下载源码.
2. 编译源码.
3. 编辑设置文件 (用户名, 密码, 等等.).
4. *可选*, 通过修改源码定制机器人.

## 获取源码

**重复: 不用从github直接下载zip文件!**

请按照wiki的安装指南获得源码 [installation guide]. The install guide covers the instructions needed to obtain the source code as well as the instructions for compiling the code.

[![Build Status](https://travis-ci.org/Jessecar96/SteamBot.png?branch=master)](https://travis-ci.org/Jessecar96/SteamBot)

## 配置机器人

你必须修改机器人才能让机器人按你的想法哦南歌子. 你可以编辑文件 `SimpleUserHandler.cs` 或者 `AdminUserHandler.cs` 或者创建自己的 `UserHandler`文件. 查看wiki上的编辑指南 [configuration guide] . This guide covers configuring a basic bot as well as creating a custom user handler.

## 机器人关了

当你运行机器人的时候,你会发现有时你需要做一下基本的操作比如关闭或者重启机器人. 控制台允许你输入一下命令来让你做这些. 查看 [usage guide] 获取更多信息.

## 更多帮助?
如果这是bug, open an Issue; 如果是修改, 阅读 [CONTRIBUTING.md] 然后 open a Pull Request.  如果是关于怎么修改你的机器人,请访问 [/r/SteamBot](http://www.reddit.com/r/SteamBot). Please use the issue tracker only for bugs reports and pull requests. The subreddit should be used for all other  discussions.


贡献者名单 (add yourself if you want to):

- [Jessecar96](http://steamcommunity.com/id/jessecar) (project lead)
- [geel9](http://steamcommunity.com/id/geel9)
- [cwhelchel](http://steamcommunity.com/id/cmw69krinkle)

## Wanna Contribute?
Please read [CONTRIBUTING.md].


   [installation guide]: https://github.com/Jessecar96/SteamBot/wiki/Installation-Guide
   [CONTRIBUTING.md]: https://github.com/Jessecar96/SteamBot/blob/master/CONTRIBUTING.md
   [LICENSE]: https://github.com/Jessecar96/SteamBot/blob/master/LICENSE
   [configuration guide]: https://github.com/Jessecar96/SteamBot/wiki/Configuration-Guide
   [usage guide]: https://github.com/Jessecar96/SteamBot/wiki/Usage-Guide
