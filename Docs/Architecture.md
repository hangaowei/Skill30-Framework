# Skill30 Framework
# Architecture Design

> Version: 3.0  
> Document Type: System Architecture

---

# 1. Overview

Skill30 Framework 采用分层架构设计。

核心思想：

将：
理解用户

↓

分析技能

↓

判断可行性

↓

设计学习路径

↓

生成计划

↓

质量验证


拆分为独立模块。

---

# 2. Overall Architecture

整体流程：
                User Input

                    │

                    ▼

          ┌─────────────────┐
          │  Input Layer    │
          │ 输入契约层       │
          └─────────────────┘

                    │

                    ▼

          ┌─────────────────┐
          │ Analysis Layer  │
          │ 分析决策层       │
          └─────────────────┘

                    │

                    ▼

          ┌─────────────────┐
          │ Safety Layer    │
          │ 安全真实性门禁   │
          └─────────────────┘

                    │

                    ▼

          ┌─────────────────┐
          │ Planning Layer  │
          │ 计划生成层       │
          └─────────────────┘

                    │

                    ▼

          ┌─────────────────┐
          │ Output Layer    │
          │ 输出规范层       │
          └─────────────────┘

                    │

                    ▼

          ┌─────────────────┐
          │ Validation      │
          │ 质量验收层       │
          └─────────────────┘

                    │

                    ▼

             Final Plan

---

# 3. Layer Responsibilities

---

# Layer 01
# System Layer

文件：
prompts/01_System.md


职责：

定义：

- AI角色
- 核心使命
- 行为边界
- 优先级规则

回答：

> AI应该如何工作？

---

# Layer 02
# Input Layer

文件：
prompts/02_Input.md


职责：

管理：

- 技能输入
- 用户信息
- 目标信息
- 限制条件

回答：

> AI需要知道什么？

---

# Layer 03
# Analysis Layer

文件：
prompts/03_Analysis.md


职责：

分析：

- 技能类型
- 技能拆解
- 学习模式
- 知识依赖
- 用户画像

回答：

> 这个技能应该怎么学？

---

# Layer 04
# Safety Layer

文件：
prompts/05_Safety.md


职责：

保护系统：

- 不虚构
- 不误导
- 不生成危险方案

回答：

> 这个计划是否真实可靠？

---

# Layer 05
# Planning Layer

文件：
prompts/04_Planning.md


职责：

生成：

- 周目标
- 日任务
- 练习路径
- 成果节点

回答：

> 如何安排30天？

---

# Layer 06
# Output Layer

文件：
prompts/06_Output.md


职责：

统一：

- Markdown结构
- 展示方式
- 用户阅读体验

回答：

> 如何交付？

---

# Layer 07
# Validation Layer

文件：
prompts/07_Checklist.md


职责：

最终审核：

- 完整性
- 可行性
- 安全性
- 真实性

回答：

> 这份计划是否达到标准？

---

# 4. Data Flow

数据流：
User

↓

Input Object

↓

Skill Analysis

↓

Decision Model

↓

Learning Strategy

↓

30-Day Plan

↓

Validation

↓

Output


---

# 5. Why Layered Design?

传统Prompt：
一个巨大Prompt

↓

直接输出


问题：

- 难维护
- 难升级
- 规则冲突
- 无法定位错误

---

Skill30：
模块化Prompt

↓

独立维护

↓

逐层优化

↓

版本升级


优势：

---

## 可维护性

修改某个规则：

只影响对应模块。

---

## 可扩展性

未来可以增加：

- Skill Database
- AI Agent
- 自动评估
- 学习追踪

---

## 可复用性

同一套架构：

支持：

- 技能学习
- 职业训练
- 兴趣培养
- 企业培训

---

# 6. Future Extension

未来版本：

---

## Skill DNA Engine

技能基因库：

记录：

- 技能结构
- 学习比例
- 常见错误
- 推荐训练方式

---

## Progress Tracking System

学习追踪：

记录：

- 完成情况
- 练习数据
- 能力变化

---

## Multi-Agent Architecture

多Agent协作：

例如：
分析Agent

↓

规划Agent

↓

反馈Agent

↓

评估Agent


---

# 7. Architecture Summary

Skill30 Framework 的核心不是：

生成更多内容。

而是：

通过结构化分析，

生成更可靠的成长路径。

---

# End of Architecture Design
