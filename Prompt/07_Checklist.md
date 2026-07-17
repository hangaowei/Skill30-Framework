# Skill30 Framework
# Validation Layer v3.0

> Version: 3.0  
> Module: Quality Assurance Checklist  
> Purpose: Validate generated 30-day skill plans before delivery.

---

# 1. Validation Layer Responsibility

Validation Layer 不负责生成内容。

它负责检查：

- 是否符合 Framework 原则
- 是否满足用户条件
- 是否存在逻辑错误
- 是否存在虚构内容

---

# 2. Validation Pipeline

检查顺序：
Input Validation

↓

Feasibility Validation

↓

Skill Classification Check

↓

Learning Design Check

↓

Safety Check

↓

Output Format Check


---

# 3. Input Validation Checklist

检查：
□ 技能是否明确？

□ 当前水平是否明确？

□ 每日时间是否明确？

□ 目标是否明确？

□ 限制条件是否考虑？


如果关键输入缺失：

不要生成完整计划。

先补充信息。

---

# 4. Feasibility Validation Checklist

检查：
□ 30天目标是否现实？

□ 用户时间是否支持目标？

□ 方法是否有效？

□ 工具是否具备对应能力？


发现：

- 错误前提
- 不可能目标
- 工具能力误解

必须：

停止生成。

---

# 5. Skill Classification Checklist

检查：
□ 是否判断A类/B类技能？

□ A类是否有具体成果？

□ B类是否避免夸大？


禁止：

B类技能使用：

- 精通
- 完全掌握
- 专家水平

---

# 6. Learning Structure Checklist

检查：
□ 是否有4周阶段？

□ 是否符合能力依赖？

□ 是否从简单到复杂？

□ 是否包含练习？

□ 是否包含反馈？


---

# 7. Daily Task Checklist

逐日检查：
□ 每天是否≤3个动作？

□ 是否只有1个新知识点？

□ 是否有明确目标？

□ 是否有完成标准？

□ 是否有即时反馈？

□ 是否有容错方案？


---

# 8. Deliberate Practice Checklist

每项练习必须包含：

---

## 明确目标

检查：

用户是否知道：

今天训练什么。

---

## 即时反馈

检查：

用户是否知道：

如何判断效果。

---

## 最近发展区

检查：

任务是否：

稍有挑战但可完成。

---

# 9. Authenticity Checklist

重点检查：
□ 是否虚构软件功能？

□ 是否虚构按钮名称？

□ 是否虚构菜单路径？

□ 是否虚构API？

□ 未确认操作是否标注⚠？


如果不能确认：

改为策略层。

---

# 10. Safety Checklist

检查：
□ 是否涉及身体动作？

□ 是否需要安全提醒？

□ 是否从低难度开始？

□ 是否避免危险建议？


---

# 11. User Persona Adaptation Checklist

检查用户类型是否真正影响方案。

---

## 冲动型

确认：
□ 第1周降低成果压力

□ 有最低完成线


---

## 完美主义型

确认：
□ 有核心任务/加分任务

□ 有容错空间


---

## 逃避型

确认：
□ 第一阶段低门槛

□ 有现实场景连接


---

## 补偿型

确认：
□ 第一阶段有小成功

□ 避免失败标签


---

## 功利型

确认：
□ 有快速应用任务

□ 操作比例足够


---

## 体验型

确认：
□ 保留兴趣探索空间


---

# 12. Output Format Checklist

最终输出必须：
□ 挑战概述

□ 周计划

□ 前置素材包

□ Day1-Day30

□ 难度调整

□ 学习技巧


---

# 13. Final Approval Standard

只有满足：
真实性

可行性

安全性

用户适配

可执行性


才允许输出。

---

# 14. Failure Handling

如果检查失败：

不要隐藏问题。

根据类型处理：

---

## 输入不足

请求补充。

---

## 前提错误

说明原因。

---

## 目标过高

调整预期。

---

## 工具未知

请求资料或降低具体程度。

---

# End of Validation Layer
