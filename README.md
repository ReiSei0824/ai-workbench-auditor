# AI工位搭建师 · AI Workbench Auditor

[English](#english) | [中文](#chinese)

---

<h2 id="english">English</h2>

AI Workbench Auditor helps a creator, solo operator, or knowledge worker turn a messy pile of AI subscriptions into a role-based workbench. Instead of recommending more tools, it audits goals, task lanes, duplicate spend, and workflow breakpoints, then outputs a minimal setup plus a short rollout plan.

### What It Does

| # | Feature | Description |
|---|---------|-------------|
| 1 | **Role-first audit** | Starts from role, deliverables, pace, budget, and risk boundaries before touching tools. |
| 2 | **Stack inventory** | Sorts current tools into high-frequency, occasional, and FOMO-driven layers. |
| 3 | **Workbench blueprint** | Maps input, judgment, production, publishing, and review into a minimal AI desk. |
| 4 | **7-day rollout** | Produces a keep/remove/add list plus an execution order that does not break current output. |
| 5 | **Safety pass** | Flags pricing drift, over-broad permissions, and overdependence on one model or one app. |

### Installation

```bash
git clone https://github.com/ReiSei0824/ai-workbench-auditor.git ~/.claude/skills/ai-workbench-auditor
```

If the repository has not been published yet, copy this folder into `~/.claude/skills/ai-workbench-auditor`.

### Usage

Trigger the skill with prompts like:

- "帮我搭一个适合内容创业的 AI 工位"
- "看看我的 AI 工具栈哪里重复了"
- "I need an AI workbench audit for my solo business setup"
- "Design a minimal AI desk for writing, publishing, and review"

### Workflow

```
Role and constraints -> Stack inventory -> Workflow lane map -> Minimal workbench blueprint -> 7-day rollout -> Safety and anti-FOMO check
```

1. Clarify the user’s role, deliverables, budget, and boundaries.
2. Inventory current models, tools, subscriptions, and repeated spend.
3. Rebuild the work into five lanes: input, judgment, production, publishing, and review.
4. Design a minimal AI workbench with clear responsibilities for each slot.
5. Produce a keep/remove/add list and a seven-day rollout plan.
6. Run a final safety check on permissions, drift-prone facts, and over-automation.

### Scope

- **Does**: Audit and design a practical AI workbench for a real working role.
- **Does NOT**: Act as a generic tool recommendation list or replace business judgment.

---

<h2 id="chinese">中文</h2>

AI工位搭建师把“工具很多但越用越乱”的状态，整理成一套按角色和任务链路设计的 AI 工作台。它不鼓励继续囤工具，而是先看你的真实产出、工作节奏、重复支出和关键卡点，再给出最小可用配置与短周期落地步骤。

### 功能

| # | 功能 | 说明 |
|---|------|------|
| 1 | **角色优先审计** | 先看角色、交付物、节奏、预算和风险边界，而不是先聊软件。 |
| 2 | **工具栈盘点** | 把已有工具分成高频、偶发和 FOMO 驱动三层。 |
| 3 | **工位蓝图输出** | 按输入、判断、生产、发布、复盘五段重建 AI 工作台。 |
| 4 | **七天迁移计划** | 生成保留/删除/新增清单和不打断业务的落地顺序。 |
| 5 | **安全与反焦虑检查** | 标出定价漂移、权限过宽、单点依赖和过度自动化风险。 |

### 安装

```bash
git clone https://github.com/ReiSei0824/ai-workbench-auditor.git ~/.claude/skills/ai-workbench-auditor
```

如果仓库尚未发布，直接把本目录复制到 `~/.claude/skills/ai-workbench-auditor` 即可。

### 使用方式

可以这样触发：

- "帮我搭一个适合内容创业的 AI 工位"
- "看看我的 AI 工具栈哪里重复了"
- "给我做一次 AI workbench audit"
- "我想给一人公司搭最小可用 AI 工作台"

### 工作流

```
角色与边界 -> 工具盘点 -> 任务链路拆解 -> 最小工位蓝图 -> 七天落地计划 -> 安全与反FOMO复核
```

1. 明确角色、交付物、预算和边界。
2. 盘点当前模型、工具、订阅和重复支出。
3. 按输入、判断、生产、发布、复盘五段重建工作链路。
4. 输出最小可用 AI 工位及每一位的职责边界。
5. 生成保留/删除/新增清单与七天迁移顺序。
6. 做权限、事实漂移和过度自动化的最终检查。

### 范围界定

- **做什么**：为真实工作角色审计并设计可落地的 AI 工位。
- **不做什么**：不做泛泛工具安利，也不替代商业判断本身。

---

## File Structure

```
ai-workbench-auditor/
├── README.md
├── SKILL.md
└── publish-checklist.md
```

## License

MIT
