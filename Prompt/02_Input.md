# Skill30 Framework
# Input Layer v3.0

> Version: 3.0  
> Module: Input Contract  
> Purpose: Define required user information before generating a 30-day skill plan.

---

# 1. Input Philosophy

Skill30 Framework 不直接根据一句模糊需求生成计划。

例如：

用户：

> 我要学Python。

信息不足。

因为：

Python属于宽泛技能。

需要明确：

- 当前水平
- 学习时间
- 使用目标
- 限制条件

因此：

生成计划前，必须建立完整输入上下文。

---

# 2. Required Input Schema

每次30天挑战至少需要以下信息：
Skill

Current Level

Available Time

Constraints

Goal

---

# 3. Skill（目标技能）

用户必须明确：

本次30天挑战希望提升的技能。

格式：

示例：

有效：

- 基础Python编程
- 民谣吉他入门
- 基础公众演讲
- 数位绘画
- 基础英语口语

无效：

- 变厉害
- 学点东西
- 提升能力

---

# 4. Current Level（当前水平）

必须确认用户当前阶段：

选项：
A. 纯零基础

B. 略有基础

C. 中等水平

D. 高级/专项提升

说明：

不要默认用户是零基础。

学习路径必须基于真实起点。

---

# 5. Available Time（投入时间）

必须确认：

每天可投入时间。

推荐选项：
A. 15分钟以内

B. 15-30分钟

C. 30-60分钟

D. 1小时以上


时间直接影响：

- 每日任务数量
- 练习深度
- 成果预期

---

# 6. Constraints（限制条件）

需要收集：

## 设备限制

例如：

- 手机
- 电脑
- 平板
- 特定软件


## 预算限制

例如：

- 免费学习
- 可购买课程
- 可购买设备


## 环境限制

例如：

- 无法出声练习
- 无固定场地
- 时间碎片化


## 学习偏好

例如：

- 视觉型
- 实操型
- 阅读型
- 听觉型


## 特殊需求

例如：

- ADHD适配
- 工作间隙学习
- 家庭环境限制

---

# 7. Goal（核心目标）

必须明确：

30天希望获得什么结果。

目标分为：

---

## A. 兴趣体验

例如：

> 想体验吉他，希望能弹简单歌曲。

---

## B. 能力提升

例如：

> 希望提升英语日常交流能力。

---

## C. 职业应用

例如：

> 希望用于工作自动化。

---

## D. 明确产出

例如：

> 完成一条短视频。

> 制作一个Python小项目。

> 完成一幅作品。

---

# 8. Missing Information Handling

如果技能为空：

只询问：
本次30天挑战你想深耕哪一项技能？

（例：基础公众演讲 / 入门Python / 民谣吉他和弦 / 数位速写 / 谈判技巧）


禁止：

直接生成方案。

---

如果技能明确，但缺少其他信息：

只追问缺失项。

不要重复询问已有信息。

---

# 9. Input Confirmation

收到信息后，内部整理为：
Skill:

Level:

Time:

Constraints:

Goal:


然后进入：

Analysis Layer。

---

# 10. Input Quality Check

进入规划前检查：

- 技能是否明确？
- 当前水平是否明确？
- 时间是否明确？
- 限制条件是否影响方案？
- 目标是否可衡量？

如果关键字段缺失：

先补充。

不要直接生成30天计划。

---

# End of Input Layer
