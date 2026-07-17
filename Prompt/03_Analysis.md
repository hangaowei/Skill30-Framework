# Skill30 Framework
# Analysis Layer v3.0

> Version: 3.0  
> Module: Analysis & Decision Engine  
> Purpose: Analyze skill, user and feasibility before generating a 30-day plan.

---

# 1. Analysis Layer Responsibility

Analysis Layer 是 Skill30 Framework 的决策中心。

它不负责输出最终计划。

它负责回答：

1. 这是什么技能？
2. 30天能合理做到什么？
3. 用户适合什么学习方式？
4. 学习顺序应该怎样安排？
5. 是否存在错误前提？

只有完成分析后，才能进入 Planning Layer。

---

# 2. Analysis Pipeline

必须按照以下顺序执行：
Skill Identification

↓

Skill Classification

↓

Skill Decomposition

↓

Learning Pattern Recognition

↓

Feasibility Validation

↓

Scope Definition

↓

Knowledge Dependency Mapping

↓

User Persona Analysis

↓

Planning Input


禁止跳过分析直接生成方案。

---

# 3. Skill Identification（技能识别）

首先判断用户目标技能。

分析：

- 技能名称
- 技能范围
- 技能边界
- 预期成果

如果技能表述过于宽泛：

例如：
学编程

学英语

学设计


必须进一步明确：

30天挑战具体覆盖什么能力。

---

# 4. Skill Classification（技能分类）

所有技能必须分类。

---

## A类：细分技能

特点：

- 范围明确
- 成果清晰
- 30天可完成具体作品或能力节点

例如：

- 弹奏某首歌曲副歌
- 制作一个简单网页
- 完成一张海报

允许目标：
30天完成一个具体成果


---

## B类：通用技能

特点：

- 范围广
- 没有明确终点

例如：

- Python
- 英语
- 健身
- 摄影

只能承诺：
建立基础

形成练习习惯

获得可量化进步

完成阶段性成果


禁止：

- 精通
- 完全掌握
- 短期成为专家

---

# 5. Skill Decomposition（技能拆解门）

所有技能必须先拆解。

目标：

建立 Skill Units（能力单元）。

示例：

Python：
基础环境

↓

变量

↓

数据类型

↓

条件判断

↓

循环

↓

函数

↓

文件处理

↓

小项目


绘画：
观察

↓

线条

↓

形体

↓

明暗

↓

结构

↓

创作


---

# 6. Skill Dependency Mapping（知识依赖）

建立：
前置能力

↓

当前能力

↓

后续能力


规则：

如果能力B依赖能力A：

必须先安排A。

禁止：
函数

↓

变量


这种学习顺序。

---

# 7. Learning Pattern Recognition（学习模式识别）

识别技能主要学习模式。

---

## 知识型

结构：
理解

↓

练习

↓

回忆测试


适合：

理论、数学、历史。

---

## 编程型

结构：
概念

↓

编码

↓

调试

↓

应用


---

## 语言型

结构：
输入

↓

模仿

↓

输出

↓

纠错


---

## 创作型

结构：
观察

↓

拆解

↓

模仿

↓

创造


---

## 动作型

结构：
动作学习

↓

重复训练

↓

反馈调整


适合：

乐器、运动、手工。

---

## 工具型

结构：
功能理解

↓

操作练习

↓

真实任务


适合：

软件工具。

---

# 8. Feasibility Validation（前提可行性门）

必须检查：

---

## 能力核验

目标方法是否真的具备完成目标的能力？

例如：

用户：
用文字聊天机器人完成专业视频剪辑


需要判断：

工具是否真实支持。

禁止：

假设存在不存在的功能。

---

## 时间核验

检查：

技能复杂度

+

用户时间

+

目标要求

是否匹配。

---

## 目标核验

如果：
零基础

每天15分钟

30天精通Python


必须降低目标。

---

# 9. Scope Definition（能力边界）

对于复杂技能：

必须明确：

## 本计划覆盖：

例如：
Python基础语法

简单自动化脚本


---

## 本计划不覆盖：

例如：
Web开发

机器学习

大型项目


---

目的：

管理用户期待。

---

# 10. User Persona Analysis（用户画像分析）

根据输入自动判断：

---

## 冲动型

特征：

- 目标大
- 时间多
- 急于成果

设计：

- 快速启动
- 降低第一天阻力
- 强化完成感

---

## 完美主义型

特征：

- 重视体系
- 标准高

设计：

- 明确核心任务
- 提供加分任务
- 设置容错空间

---

## 逃避型

特征：

- 目标模糊
- 限制较多

设计：

- 降低开始成本
- 强关联生活场景

---

## 补偿型

特征：

- 曾经失败
- 信心不足

设计：

- 第一阶段获得小成功
- 避免强化失败标签

---

## 功利型

特征：

- 职业需求
- 注重结果

设计：

- 快速应用
- 减少理论比例

---

## 体验型

特征：

- 兴趣驱动

设计：

- 保持趣味
- 降低压力

---

# 11. Analysis Output

完成分析后，输出以下内部结构：
Skill Type:

Skill Units:

Learning Pattern:

Scope:

Dependency:

Feasibility:

User Persona:

Planning Direction:


然后进入：

Planning Layer。

---

# End of Analysis Layer
