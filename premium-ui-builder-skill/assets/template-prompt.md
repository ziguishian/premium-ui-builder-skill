# premium-ui-builder-skill Prompt 模板

## 模板 1：新项目页面设计 Prompt

```text
你是一名资深产品设计师 + 前端架构师，请为项目 {project_name} 设计并实现一套高质量页面方案。

【项目背景】
- 页面类型：{page_type}
- 目标用户：{target_user}
- 核心目标：{core_goal}
- 品牌气质：{brand_tone}
- 期望视觉风格：{visual_style}

【结构要求】
请先规划信息架构，再输出页面实现。核心模块包括：
{core_sections}

【设计与实现要求（必须遵循四层模型）】
1) CSS（质感）
- 使用 refined typography、subtle border、soft shadow、layered surfaces
- 统一 spacing / radius / shadow token
- 避免廉价渐变与过度发光

2) Motion（呼吸感）
- 根据交互级别 {interaction_level} 设计动效
- 包含 hover/focus/press/loading 的反馈
- 使用克制、统一的 easing 和时长（避免花哨动画）

3) Spatial / 3D（空间感）
- 是否使用 3D：{use_3d}
- 如使用，仅作为氛围层，不能抢主体
- 必须提供移动端降级与性能保护策略

4) UI System（产品感）
- 构建统一组件系统（Button/Card/Input/Modal/Toast/Empty/Loading）
- 明确定义组件变体与状态
- 体现真实产品场景（空状态、错误态、成功反馈）

【技术栈】
{tech_stack}

【约束条件】
{constraints}

【输出要求】
1. 先输出页面结构与设计决策摘要
2. 再输出关键组件与页面代码（可直接开发）
3. 明确响应式策略（移动端/桌面端）
4. 给出性能与可访问性注意事项
5. 最后列出“需要避免的问题”
```

---

## 模板 2：现有页面优化 Prompt

```text
你是一名高级 UI 重构顾问，请基于以下信息对现有页面进行系统化升级，而不是仅做表面美化。

【当前页面】
{current_page_description}

【当前问题】
{current_problem}

【目标风格】
{desired_style}

【改造边界】
- 必须保留：{must_keep}
- 可调整部分：{can_change}

【技术栈】
{tech_stack}

【优化重点】
{optimization_focus}

【约束条件】
{constraints}

【执行方法（必须遵循）】
1) 先诊断普通感来源（信息层级、留白、组件一致性、色彩、动效、状态反馈）
2) 给出分维度优化方案：
   - CSS 质感
   - Motion 呼吸感
   - Spatial/3D 空间感（如不适合请给轻量替代）
   - UI System 产品感
3) 对每项优化写清：改哪里、改成什么、如何实现、删减什么
4) 补齐真实产品状态：empty/loading/error/success
5) 输出统一组件规范与关键页面重构代码

【禁止事项】
- 不要大面积廉价渐变
- 不要过度发光或堆叠 3D 特效
- 不要让背景抢主体
- 不要为了炫技破坏可读性与性能
- 不要输出不可维护的概念稿式代码

【输出要求】
1. 问题诊断清单
2. 优化策略总览
3. 逐模块改造方案
4. 关键代码实现
5. 最终验收清单
```

