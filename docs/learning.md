# 学习路线

[返回目录](../README.md)

按自己的队伍任务选择顺序。下面的“完成标准”是学习练习，不是赛事资格标准。

| 阶段 | 学习内容 | 一个可检查的练习 |
| --- | --- | --- |
| 工具基础 | Git 分支与提交、命令行、项目所用语言 | 克隆一个公开仓库，找到 README、许可证、构建与测试入口；用 `git status` 确认改动 |
| 机器人基础 | 坐标系与变换、相机/IMU/编码器、关节与运动学 | 画出一个机器人从图像或关节数据到动作指令的路径 |
| 系统阅读 | 项目构建、消息或接口、日志、仿真 | 运行最小示例，记录启动命令、输入、输出与失败条件 |
| 足球任务 | 找球、定位、步态、踢球、起身、角色与队伍通信 | 选一个模块，把测试指标和相关规则条款对应起来 |
| 比赛集成 | 规则版本、GameController、实机检查 | 在测试环境模拟一次完整开赛和状态切换流程，保留日志 |

**推荐资料入口**：[Pro Git 中文版](https://git-scm.com/book/zh/v2)、[ROS 2 官方教程](https://docs.ros.org/en/jazzy/Tutorials.html)、[HSL 规则发布页](https://github.com/RoboCup-HumanoidSoccerLeague/HSL-Rules/releases)、[GameController 项目](https://github.com/RoboCup-HumanoidSoccerLeague/GameController)。ROS 2 只在队伍的软件栈使用它时作为必修；各项目的具体入口见[仓库索引](../resources/repositories.md)。

阅读 TDP 时可以按“问题 → 方法 → 硬件/数据 → 验证结果”做笔记。[2026 年官方队伍页](https://hsl.robocup.org/qualified-teams/)集中提供 TDP 与软件资料，适合比较不同队伍的方案。
