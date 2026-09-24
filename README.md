# ForgeWurst

在Minecraft Forge上运行的Wurst作弊客户端。

从 [[https://github.com/KrisTHL181/Chinese-ForgeWurst]]() 派生，作为独立更新分支.

## 如何将这个项目编译为.JAR文件

在 `ForgeWurst\ForgeWurst MC 1.12.2\`下运行 `gradlew build.bat` 即可. 也可直接运行根目录下的 `build.bat`。

不想自己编译的话，可以直接去 [Releases](../../releases) 下载编译好的 jar。

## 许可和法律事务

此代码根据 `GNU General Public License v3.` 进行授权。

**您只能在使用相同许可证发布的开源客户端中使用此代码！不允许在闭源代码/专用客户端中使用它！**

查看 [LICENSE.txt](LICENSE.txt) 以获取详情, 以及关于您可以和不能使用此代码做什么的简化摘要。

**请不要在禁止使用作弊客户端的服务器（如Hypixel）上使用该模组！这可能造成账户封禁或其他问题！**

**造成的损失（如账号封禁、使用者民声损失等）与作者无关。**

## Fork版特性

* 已全部翻译为中文 (人工翻译!)
* 合并了原仓库下的一个修复NullPointerException的补丁([https://github.com/Wurst-Imperium/ForgeWurst/pull/2](https://github.com/Wurst-Imperium/ForgeWurst/pull/2))
* 删除了 MC 1.10.2 版本的支持 (删除了README.md中相应的文本)
* 在命令中加入了一些实用功能（如SeedDup、IP）
* 加入了部分功能 (如TpAura、BoatFly等)
* 将一些只有侵入客户端（原版Wurst有两个版本：一个是侵入原版客户端的，一个是Forge版但已停更）才有的功能移植到了该Forge版本上。

## 自Fork版特性

* 新增LOGO与功能显示开关：打开GUI后，在UI设置窗口中可以随时开关左上角的ForgeWurst标题与已启用功能列表的显示，状态会自动保存。

## 自动构建

本分支配置了GitHub Actions自动构建，推送到master或手动在Actions页面触发时，会自动编译模组并把编译好的jar发布到[Releases](../../releases)，可直接下载使用。
