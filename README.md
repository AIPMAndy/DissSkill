# Andy 绝对理性批判 Skill

> 让 AI 泼冷水的 5 个反向 prompt — 用批判性思维挖掘决策盲区

[English](#english) | [中文](#中文)

---

## 中文

### 核心理念

**给 AI 一个有立场、对你不友好的身份 — 它的能力量级被解锁。**

通过 5 个历史名人的批判性视角，从不同维度质疑你的决策/计划/目标，逼出你不敢承认的问题和隐藏风险。

### 5 个批判角色

| 角色 | 职责 | 关键问题 | 代表作 |
|------|------|---------|--------|
| 🤔 **苏格拉底**<br/>Socrates | 逼你把模糊需求说清楚 | 你真的想清楚了吗？ | 苏格拉底式提问法 |
| 🔥 **乔布斯**<br/>Steve Jobs | 不给情绪价值，只指硬伤 | 这是狗屎（This is shit） | 极致产品主义 |
| 💰 **芒格**<br/>Charlie Munger | 质疑可行性和 ROI | 反过来想，总是反过来想 | 多元思维模型 |
| ⚰️ **塔勒布**<br/>Nassim Taleb | 分析同类尝试的失败案例 | 脆弱的东西会崩溃 | 《黑天鹅》《反脆弱》 |
| ⏰ **贝索斯**<br/>Jeff Bezos | 站在未来视角写警告信 | 80岁时你会后悔什么？ | 后悔最小化框架 |

### 使用场景

- 🚀 产品立项前的理性质疑
- 💼 商业计划的投资人视角审查
- 📋 项目方案的风险评估
- 🎯 重大决策前的盲点挖掘
- 🔧 技术选型的死法研究

### 快速开始

1. **安装**：将此 Skill 复制到你的 Claude Skills 目录（通常是 `~/.claude/skills/`）

2. **使用**：在与 Claude 的对话中：
   ```
   用绝对理性批判分析这个计划：[你的计划]
   ```
   或指定特定角色：
   ```
   用乔布斯视角批判这个产品方案
   用芒格视角分析这个商业计划
   用塔勒布视角研究这个赛道的死法
   ```

3. **查看示例**：参考 `examples/example-critique.md`，里面有完整的 AI 写作助手产品批判案例

### 文件结构

```
andy-absolute-rational-critique-skill/
├── README.md                   # 本文件
├── SKILL.md                    # 详细使用指南
├── role-1-socratic.md          # 苏格拉底
├── role-2-steve-jobs.md        # 乔布斯
├── role-3-charlie-munger.md    # 芒格
├── role-4-nassim-taleb.md      # 塔勒布
├── role-5-jeff-bezos.md        # 贝索斯
└── examples/
    └── example-critique.md     # 完整示例
```

### 输出特点

- ✅ 区分**事实/判断/假设**
- ✅ 标注**置信度**（高/中/低）
- ✅ 提供**待验证清单**
- ✅ 给出**可行动建议**
- ✅ 基于**五理论框架**（熵增、还原、矛盾、试错、概率）

### 示例输出

完整示例见 `examples/example-critique.md`，以下是摘要：

**原始决策**：做一个 AI 写作助手产品

**批判结果**：
- 🔴 **高风险**：市场需求未验证、没有差异化护城河、被 ChatGPT 碾压风险
- 🟡 **中风险**：时间预估过于乐观、资源配置不足、团队配置不完整
- ❓ **待验证**：用户真的需要吗？愿意付费吗？能按时完成吗？
- 💡 **下一步**：停止开发，先验证市场（访谈 50 个用户）

### 适用人群

- 创业者（产品立项、商业计划）
- 产品经理（功能决策、优先级排序）
- 技术负责人（技术选型、架构设计）
- 投资决策者（项目评估、风险分析）
- 任何需要做重大决策的人

### 原理

基于认知科学和决策理论：
- **认知偏差纠正**：对抗确认偏见、乐观偏见、沉没成本谬误
- **多视角思考**：强制从 5 个不同角色审视同一问题
- **前瞻性后悔**：用"未来后悔"激活损失厌恶心理
- **历史教训**：用失败案例对抗"我会不一样"的幻觉

### 为什么选这 5 个人？

- **苏格拉底**：西方哲学奠基人，提问法大师
- **乔布斯**：极致产品主义代表，以严苛著称
- **芒格**：巴菲特黄金搭档，反向思维大师
- **塔勒布**：风险研究专家，《黑天鹅》作者
- **贝索斯**：长期主义代表，后悔最小化框架创始人

### 贡献

欢迎贡献：
- 提交新的批判角色
- 分享真实案例
- 改进现有角色的追问框架
- 翻译到其他语言

请通过 Issue 或 Pull Request 参与。

### 许可证

MIT License - 详见 [LICENSE](LICENSE)

### 作者

Andy ([@AIPMAndy](https://github.com/AIPMAndy))

AI 产品专家，前腾讯/百度 AI 负责人

---

## English

### Core Concept

**Give AI a stance and an adversarial identity — unlock its true potential.**

Use 5 historical figures' critical perspectives to challenge your decisions/plans/goals from different angles, forcing you to confront problems and risks you're afraid to admit.

### 5 Critical Roles

| Role | Responsibility | Key Question | Known For |
|------|---------------|--------------|-----------|
| 🤔 **Socrates** | Force you to clarify vague requirements | Have you really thought this through? | Socratic Method |
| 🔥 **Steve Jobs** | No emotional support, only point out fatal flaws | This is shit | Product Perfectionism |
| 💰 **Charlie Munger** | Question feasibility and ROI | Invert, always invert | Mental Models |
| ⚰️ **Nassim Taleb** | Analyze similar failed attempts | Fragile things break under pressure | The Black Swan, Antifragile |
| ⏰ **Jeff Bezos** | Write a warning letter from the future | What will you regret at 80? | Regret Minimization Framework |

### Use Cases

- 🚀 Critical questioning before product launch
- 💼 Investor-perspective review of business plans
- 📋 Risk assessment of project proposals
- 🎯 Blind spot discovery before major decisions
- 🔧 Death research for technology choices

### Quick Start

1. **Install**: Copy this skill to your Claude Skills directory (usually `~/.claude/skills/`)

2. **Use**: In your conversation with Claude:
   ```
   Use absolute rational critique to analyze this plan: [your plan]
   ```
   or specify a role:
   ```
   Use Steve Jobs' perspective to critique this product plan
   Use Charlie Munger's perspective to analyze this business plan
   Use Nassim Taleb's perspective to research failure patterns
   ```

3. **See Examples**: Check `examples/example-critique.md` for a complete AI writing assistant product critique

### Features

- ✅ Distinguish **facts/judgments/assumptions**
- ✅ Mark **confidence levels** (high/medium/low)
- ✅ Provide **verification checklists**
- ✅ Give **actionable recommendations**
- ✅ Based on **Five Theory Framework** (entropy, reductionism, contradiction, trial-error, probability)

### Who Is This For

- Entrepreneurs (product launch, business plans)
- Product Managers (feature decisions, prioritization)
- Tech Leads (technology selection, architecture design)
- Investment Decision Makers (project evaluation, risk analysis)
- Anyone making important decisions

### Why These 5 People?

- **Socrates**: Founder of Western philosophy, master of questioning
- **Steve Jobs**: Icon of product perfectionism, known for uncompromising standards
- **Charlie Munger**: Buffett's partner, master of inversion and mental models
- **Nassim Taleb**: Risk expert, author of The Black Swan and Antifragile
- **Jeff Bezos**: Long-term thinker, creator of the Regret Minimization Framework

### Contributing

Contributions welcome:
- Submit new critical roles
- Share real-world cases
- Improve existing role frameworks
- Translate to other languages

Participate via Issues or Pull Requests.

### License

MIT License - see [LICENSE](LICENSE)

### Author

Andy ([@AIPMAndy](https://github.com/AIPMAndy))

AI Product Expert, Former AI Lead at Tencent/Baidu

---

## 版本历史 | Version History

- **v1.0.0** (2026-07-03) - 初始版本 | Initial release
  - 5 个批判角色 | 5 critical roles
  - 完整示例 | Complete examples
  - 中英文文档 | Chinese and English documentation

- **v1.1.0** (2026-07-03) - 角色更新 | Role update
  - 所有角色改为历史名人 | All roles changed to historical figures
  - 苏格拉底、乔布斯、芒格、塔勒布、贝索斯 | Socrates, Jobs, Munger, Taleb, Bezos
