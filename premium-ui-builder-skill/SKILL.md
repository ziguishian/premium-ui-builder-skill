---
name: premium-ui-builder-skill
description: 将“页面不够高级、太普通、像模板”等模糊审美需求转化为可执行的 UI 设计与前端实现方案。用于两类场景：(1) 新项目从 0 到 1 的页面规划（信息架构、视觉系统、组件系统、技术栈、可复制 Prompt）；(2) 已有页面的高级感升级与产品化重构（问题诊断、分维度优化、具体改造指令、禁止项）。当用户提出新建官网/landing/dashboard/工具页/个人站，或提出优化当前页面质感与产品感时触发。
---

# premium-ui-builder-skill

按以下步骤执行，不要跳步。

## 1) 识别模式

先判定用户意图并选择单一模式：

- **New Project Design Mode**：用户在描述新建项目、从 0 开始、规划页面。
- **UI Upgrade Mode**：用户在描述已有页面、当前 UI、优化重构。

若信息不足：
1. 先给出基于常见场景的“明确标注假设”的方案；
2. 再在结尾给出最多 3 个确认问题。

## 2) 强制使用“四层模型”

所有建议必须覆盖并落地到以下四层：

1. **CSS（质感）**：边框、阴影、圆角、背景分层、排版精度
2. **Motion（呼吸感）**：hover/press/loading/transition 等反馈
3. **Spatial/3D（空间感）**：是否使用、氛围层级、移动端降级、性能边界
4. **UI System（产品感）**：组件变体、状态系统、一致性约束

## 3) New Project Design Mode 输出流程

必须按顺序输出：

# 项目理解
# 页面类型判断
# 页面气质建议
# 信息架构建议
# 视觉系统建议
# 组件系统建议
# 动效与交互建议
# 3D / 空间感建议
# 推荐技术栈
# 可直接复制给 AI 的项目启动 Prompt
# 需要避免的问题
# 可选确认问题

执行要求：
- 页面类型从：Landing / SaaS 官网 / Dashboard / Admin / AI 产品页 / 个人站 / 工具型 App / 内容站 / 移动端 / 桌面端中判定。
- 若用户未给目标用户与场景，明确写“以下为假设”。
- 技术栈按复杂度分级，禁止默认堆重技术。

## 4) UI Upgrade Mode 输出流程

必须按顺序输出：

# 当前问题判断
# 普通感来源诊断
# 高级感优化方向
# 具体修改建议
# 推荐关键词清单
# 可直接复制给 AI 的页面优化 Prompt
# 需要避免的问题
# 可选确认问题

执行要求：
- 诊断必须具体到模块或组件，不可只说“不高级”。
- 每条建议必须包含：改哪里 / 改成什么 / 用什么实现 / 要删减什么。
- 必须补齐真实产品状态：empty / loading / error / success。

## 5) Prompt 生成规范（两模式通用）

生成最终 Prompt 时，必须包含：
1. 目标上下文
2. 页面结构或改造范围
3. 视觉系统约束
4. 动效与交互约束
5. 组件系统与状态要求
6. 3D/空间感策略与降级
7. 技术栈与性能边界
8. 明确禁止项
9. 输出物要求（结构说明 + 可运行代码）

## 6) 负面约束

严禁：
- 只给审美词，不给实现路径
- 大面积廉价渐变或过曝发光
- 无意义堆叠 3D
- 背景抢主体
- 组件风格不统一
- 为炫技牺牲可读性、响应式和性能
- 输出 Dribbble 概念稿式不可用结果

## 7) 关键词库（按需引用）

- CSS: backdrop-blur, subtle border, soft shadow, layered surfaces, refined typography
- Motion: micro-interactions, hover feedback, scroll reveal, smooth transition, easing curve
- Spatial: gradient mesh, radial glow, depth layers, lightweight particles, parallax
- UI System: component variants, unified buttons, empty/loading/error states, dashboard layout

