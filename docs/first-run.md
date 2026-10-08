# 首次运行

[返回目录](../README.md)

第一个练习选择 **HSL GameController**：它负责比赛状态和机器人通信，不需要先拥有机器人。[官方仓库](https://github.com/RoboCup-HumanoidSoccerLeague/GameController)提供预编译版本、源码运行说明和通信接口。以下步骤依据仓库说明整理；本手册尚未在指定机器上完成 GUI 实测。

## 方案 A：使用发布包

1. 打开 [GameController Releases](https://github.com/RoboCup-HumanoidSoccerLeague/GameController/releases)，选择适合操作系统的发布包，记录标签和下载日期。
2. 解压或安装后，按发布包内的启动脚本打开程序。首次出现的 Launcher 可选择比赛配置、队伍、球衣颜色和网络接口；配置项以当前发布包的说明为准。
3. 先在离线练习环境观察界面和比赛状态，再阅读仓库 README 的 **Network Communication** 部分。它解释了 GameController 发给机器人的控制消息、机器人回传的状态消息及队伍通信。
4. 截图或记录所选版本、操作系统、是否启动成功，以及看到的比赛状态。若启动失败，保存错误信息或日志，核对发布包平台与防火墙设置。

## 方案 B：从源码运行（已安装 Rust 时）

```sh
git clone https://github.com/RoboCup-HumanoidSoccerLeague/GameController.git
cd GameController
cargo run -- -h
cargo run
```

`cargo run -- -h` 用来先查看当前版本的参数；`cargo run` 按官方 README 的方式启动 Launcher。源码依赖及编译时间由当前项目决定。**不要把命令退出码、出现窗口和真实机器人通信成功混为同一项验收**。[来源：GameController README](https://github.com/RoboCup-HumanoidSoccerLeague/GameController)。

## 练习完成标准

记录“版本、系统、命令、预期、实际、日志位置”六项。能说明 GameController 与机器人之间传递什么信息，并找出对应的协议定义，就完成了这个入门练习。连接真实机器人前还应核对当届[规则](https://github.com/RoboCup-HumanoidSoccerLeague/HSL-Rules/releases)、队伍网络方案和安全操作要求。
