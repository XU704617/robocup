# RoboCup 入门

[返回目录](../README.md)

RoboCup 是以机器人与人工智能研究、教育为目标的国际赛事体系。除机器人足球（Soccer），还包括 Rescue、@Home、Industrial 和 Junior 等领域；它们的任务、机器人和规则不同。[来源：RoboCup Federation](https://www.robocup.org/)、[2026 赛事组别概览](https://2026.robocup.org/leagues/)。

## 足球组与本手册的范围

足球组还包括 Small Size、Middle Size、Soccer Simulation（2D/3D）等。本手册重点介绍 **Humanoid Soccer League（HSL，人形机器人足球组）**。HSL 由原 Humanoid League（HL）和 Standard Platform League（SPL）合并，首次世界赛于 2026 年举行。HSL 的机器人自主踢球，涉及双足运动、视觉、定位、行为和队伍协作。[来源：HSL 官方网站](https://hsl.robocup.org/)、[2026 赛事足球组介绍](https://2026.robocup.org/leagues/robocupsoccer/)。

在 HSL 内，还要区分 Small、Middle、Large 三种机器人尺寸组别，以及 Foundation、Advanced 两种队伍配置。具体尺寸、人数与允许的硬件依当届规则决定；[2026 年赛事页](../events/2026/hsl-world-cup.md)给出了该届示例。

## 看资料时先确认三件事

1. **年份和赛事**：世界赛、区域赛和队内选拔的规则可能不同。
2. **组别和版本**：旧 HL/SPL 材料可用于了解技术，但不能直接当成 HSL 当届规则。
3. **平台和用途**：开源队伍的软件栈通常针对特定机器人，不等于所有平台都能直接运行。

从[网站与信息渠道](../resources/websites.md)进入官方资料，再按[新人路线](getting-started.md)选择下一步。

## RoboCup 各领域看什么

| 领域 | 核心任务 | 与本手册的关系 |
| --- | --- | --- |
| Soccer | 机器人自主踢球；含多个硬件与仿真组别 | 本手册聚焦其中的 HSL |
| Rescue | 灾害环境中的搜索、感知与救援任务 | 可借鉴探索和自主系统思路，规则另行查询 |
| @Home | 家庭与室内服务机器人任务 | 可借鉴感知和人机交互方法，规则另行查询 |
| Industrial | 工业场景的机器人任务 | 可借鉴调度和系统集成方法，规则另行查询 |
| Junior | 面向青少年的机器人教育赛事 | 参赛对象与赛题另行查询 |

这些是阅读导航，不代表各领域每年固定举行同一赛题。[赛事领域总览](https://www.robocup.org/)与[2026 分组介绍](https://2026.robocup.org/leagues/)提供最新入口。

## 一场 HSL 比赛需要哪些系统

可以把比赛理解为四个并行问题：**机器人要能稳定运动**，**能从传感器判断场上情况**，**能按比赛状态决定动作**，**能与裁判系统及队友正确通信**。例如“寻找并踢向球门”需要相机识别球、估计机器人和球的相对位置、规划接近路线、控制步态和踢球动作，还要根据 GameController 的比赛状态决定何时可以执行。各队伍的实现不同；[系统结构](system-overview.md)逐个解释接口与常见故障。

2026 年 HSL 的 Small、Middle、Large 是**人形机器人尺寸组别**，与 RoboCup Soccer 的独立 Small Size League、Middle Size League 不是同一命名层级。阅读网页时先看它属于哪个联盟或组别。[来源：RoboCup 2026 足球组介绍](https://2026.robocup.org/leagues/robocupsoccer/)、[HSL 参赛通知](https://hsl.robocup.org/call-for-participation/)。
