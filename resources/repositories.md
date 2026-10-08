# 仓库与工具

[返回目录](../README.md)

以下项目于 **2026-10-08** 从原始仓库或维护组织页核对。它们用途不同；克隆前先看 README、许可证、发布标签、依赖和适用机器人平台。

| 项目 | 能用来做什么 | 使用时先确认 |
| --- | --- | --- |
| [HSL-Rules](https://github.com/RoboCup-HumanoidSoccerLeague/HSL-Rules) | 规则源文件和发布 PDF | 比赛查[对应年份的 Release](https://github.com/RoboCup-HumanoidSoccerLeague/HSL-Rules/releases)；仓库 `main` 可包含开发中内容 |
| [HSL GameController](https://github.com/RoboCup-HumanoidSoccerLeague/GameController) | 运行比赛控制软件，理解比赛状态与通信协议 | 发布包平台、配置、网络接口和协议版本 |
| [HSL RobotInspection](https://github.com/RoboCup-HumanoidSoccerLeague/RobotInspection) | 机器人检查与体能测试辅助工具 | 适用的当届规则、脚本说明 |
| [Hamburg Bit-Bots / bitbots_main](https://github.com/bit-bots/bitbots_main) | 开放的 ROS 2 人形足球软件栈，含感知、运动、行为等模块 | 机器人适配、[项目文档](https://docs.bit-bots.de/)与 Pixi 构建说明；仓库标注 MIT 许可证 |
| [RoboCup-SPL / GameController](https://github.com/RoboCup-SPL/GameController) | TeamCommunicationMonitor 等旧 SPL 支持工具；仓库说明其在 HSL 中仍用于辅助 | 不要与新的 HSL GameController 主程序混淆 |
| [Rhoban / frasa](https://github.com/Rhoban/frasa) | 小型人形机器人起身动作研究的仿真环境示例 | 研究环境与当前比赛平台的差异，查看依赖和许可证 |

如果本地已有 HSL-Rules 克隆，可用于离线阅读，但更新前要核对分支、提交和 Release。名称中带 RoboCup 的其他仓库未必属于 HSL；录入前应先读其 README，核对赛题和适用组别。
