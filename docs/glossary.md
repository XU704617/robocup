# 术语与常见问题

[返回目录](../README.md)

| 术语 | 在本手册中的意思 |
| --- | --- |
| HSL | Humanoid Soccer League；2026 年起由原 HL 与 SPL 合并的人形足球组。[来源](https://hsl.robocup.org/) |
| HL / SPL | 旧 Humanoid League / Standard Platform League；阅读旧论文和代码时会遇到，旧规则不自动适用于 HSL。[来源](https://hsl.robocup.org/) |
| Small / Middle / Large | HSL 按机器人尺寸划分的比赛组别；具体门槛以当届规则为准。[2026 示例](../events/2026/hsl-world-cup.md) |
| Foundation / Advanced | HSL 每个尺寸组内的队伍配置，主要涉及场上机器人数量。[来源：2026 招募通知](https://hsl.robocup.org/call-for-participation/) |
| TDP | Team Description Paper，介绍队伍系统和研究工作的技术说明；2026 资格申请要求提交。[来源](https://hsl.robocup.org/call-for-participation/) |
| GameController | 比赛状态控制软件；机器人通过规定的通信格式接收状态并回传信息。[项目说明](https://github.com/RoboCup-HumanoidSoccerLeague/GameController) |
| 资格申请 / 正式注册 | 前者用于争取参赛资格，后者按赛事方流程完成参赛登记，两者的时间和材料分别核对。[2026 招募通知](https://hsl.robocup.org/call-for-participation/) |

## 常见问题

**为什么旧网页写 Humanoid League 或 SPL？** 这些名称属于合并前的组别。研究资料可继续参考；参赛应先看目标年份的 HSL 规则和通知。[来源](https://www.robocup.org/leagues/35)。

**从哪里找当届规则？** 从[HSL 官方网站](https://hsl.robocup.org/)进入[规则发布页](https://github.com/RoboCup-HumanoidSoccerLeague/HSL-Rules/releases)，记下发布标签。仓库开发分支可能包含尚未发布的修改。

**没有机器人能学什么？** 先阅读规则、TDP、通信协议和公开代码，再做[GameController 入门练习](first-run.md)。是否能跑仿真取决于所选仓库与硬件平台。

**找到开源代码就可以直接参赛吗？** 先看许可证、平台适配要求和当届关于第三方软件披露的规则。2026 招募通知要求说明使用的其他队伍软件和第三方库。[来源](https://hsl.robocup.org/call-for-participation/)。
