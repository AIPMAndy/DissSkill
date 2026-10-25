<div align="center">

# DissSkill

### 你的 AI 什么都说好。DissSkill 专门问：然后呢？

把 AI 从“情绪价值供应商”，变成你的决策压力测试器。

[![License: MIT](https://img.shields.io/badge/license-MIT-111111.svg)](LICENSE)
![Works with Codex](https://img.shields.io/badge/works%20with-Codex-0A7C66.svg)
![Works with Claude](https://img.shields.io/badge/works%20with-Claude-D97757.svg)

[快速开始](#30-秒开-diss) · [它有什么用](#它到底有什么用) · [看一次实战](#一次典型的-diss) · [English](#english)

</div>

---

你：我有一个绝妙的产品想法。

普通 AI：太棒了！这是一个非常有潜力的方向！

**DissSkill：绝妙到什么程度？有三个用户愿意付钱，还是有三十个朋友给你点赞？**

你：……

**DissSkill：很好，第一条市场数据已经有了。**

> 不是为了把你骂醒，是为了让最便宜的失败发生在开工之前。

## 它到底有什么用？

做决定时，最危险的往往不是没有答案，而是太快得到一个顺耳的答案。

DissSkill 用 5 种对抗性视角拆你的产品、项目、商业计划或重大选择，专门寻找：

- 被热情藏起来的关键假设
- 一算 ROI 就站不住的伪需求
- “大家都这么做”背后的集体盲区
- 现在不验证、以后会很贵的风险
- 看起来很忙，实际没有推进的下一步

最后得到的不是一盆冷水，而是一份可执行的压力测试报告：

```text
事实 / 判断 / 假设
        ↓
高风险 / 中风险 / 低风险
        ↓
待验证问题 + 最小验证动作
```

一句话：**先 Diss 决策，再为决策买单。**

## 五人拆台办

| 视角 | 专门拆什么 | 它会追问 |
| --- | --- | --- |
| **苏格拉底** | 模糊定义与隐藏假设 | “你说的需求，到底是谁的需求？” |
| **乔布斯** | 产品硬伤与伪差异化 | “如果只能保留一个价值，它是哪一个？” |
| **芒格** | 可行性、激励与 ROI | “反过来想，这件事最容易怎么失败？” |
| **塔勒布** | 脆弱性与小概率重击 | “哪个意外一来，你就直接出局？” |
| **未来视角** | 长期代价与后悔 | “一年后回头看，你最可能后悔没验证什么？” |

这些名字代表思维框架，不是名人模仿秀。DissSkill 批判的是决策，不是人。

## 30 秒开 Diss

### Codex

```bash
mkdir -p ~/.codex/skills && git clone https://github.com/AIPMAndy/DissSkill.git ~/.codex/skills/diss-skill
```

### Claude Code

```bash
mkdir -p ~/.claude/skills && git clone https://github.com/AIPMAndy/DissSkill.git ~/.claude/skills/diss-skill
```

安装后开启一个新对话，直接说：

```text
用 DissSkill 拆一下这个方案：[粘贴你的方案]
```

也可以把刀递得更准一点：

```text
别夸我。用 DissSkill 找出这个产品最可能失败的 3 个原因。
用芒格视角算一遍这个商业计划的 ROI 和激励错位。
用塔勒布视角找出这个技术方案最脆弱的环节。
让未来的我给现在写一封后悔信，然后给出本周能做的验证动作。
```

> 已安装旧版？旧触发词“绝对理性批判”仍然有效。

## 一次典型的 Diss

**原计划：**

> 做一个 AI 写作助手，三个月上线，先把功能做全，再开始找用户。

**普通 AI 可能会给你：**

> 这是一个充满潜力的方向。建议先规划编辑器、素材库、多模型和会员系统。

**DissSkill 会先问：**

- **高风险：** 需求未经验证，“功能做全”可能只是把未知成本做全。
- **致命假设：** 用户缺的是另一个写作工具，而不是分发、选题或稳定产出。
- **竞争压力：** 通用模型已经覆盖基础写作，差异化尚未成立。
- **最小验证：** 暂停完整开发，用 7 天访谈 10 个目标用户，并尝试收取 3 笔订金。
- **停止条件：** 没有人愿意交付真实素材或付费，就不要用更多功能掩盖需求问题。

它不会替你做决定。它只负责让你在做决定之前，看见账单。

完整案例见 [examples/example-critique.md](examples/example-critique.md)。

## 什么时候最值得用？

- 产品立项：这个需求是真需求，还是创始人的自我感动？
- 商业计划：收入写了三页，获客成本为什么只写了一行？
- 功能排期：用户要的是这个功能，还是团队刚好会做这个功能？
- 技术选型：我们在解决问题，还是在收藏新框架？
- 重大决策：现在的兴奋，能不能扛住三个月后的代价？

不适合拿来做什么：人身攻击、替代专业法律/医疗/财务意见，以及在信息不足时假装确定。

## 为什么不是“再写一个 Prompt”？

单条 Prompt 容易得到一段看起来很聪明的反对意见。DissSkill 把批判变成固定流程：

1. 先补齐目标、资源、时间与成功标准。
2. 用五个互补视角依次施压，避免只有一种偏见。
3. 区分事实、判断与假设，并标注置信度。
4. 合并重复风险，按严重程度排序。
5. 把批判收束成可验证、可停止、可执行的下一步。

所以它的价值不是“更会喷”，而是**让批判最终落到行动上**。

## 仓库结构

```text
DissSkill/
├── SKILL.md                    # 核心工作流与触发说明
├── role-1-socratic.md          # 苏格拉底：澄清假设
├── role-2-steve-jobs.md        # 产品硬伤：聚焦价值
├── role-3-charlie-munger.md    # 芒格：反向思考与 ROI
├── role-4-nassim-taleb.md      # 塔勒布：脆弱性与失败模式
├── role-5-jeff-bezos.md        # 未来视角：长期代价与后悔
└── examples/
    └── example-critique.md      # 完整实战案例
```

## 参与改进

真实世界不缺好点子，缺的是经得起坏消息的好点子。

欢迎提交 Issue 或 Pull Request：

- 提供一个被 DissSkill 救下或劝退的真实案例
- 改进某个角色的追问框架
- 补充可验证的失败模式
- 增加新的语言版本

觉得它有用，可以点一个 Star。觉得它没用，也欢迎开 Issue 来 Diss 它。

## English

### Your AI says yes. DissSkill asks, “Then what?”

DissSkill turns an agreeable AI assistant into a decision stress tester. It applies five adversarial lenses to products, plans, business cases, technical choices, and other high-stakes decisions.

Instead of generic criticism, it returns:

- hidden assumptions and failure modes
- risks ranked by severity and confidence
- facts separated from judgments and guesses
- concrete validation steps and stop conditions

Install for Codex:

```bash
mkdir -p ~/.codex/skills && git clone https://github.com/AIPMAndy/DissSkill.git ~/.codex/skills/diss-skill
```

Install for Claude Code:

```bash
mkdir -p ~/.claude/skills && git clone https://github.com/AIPMAndy/DissSkill.git ~/.claude/skills/diss-skill
```

Then start a fresh conversation and say:

```text
Use DissSkill to find the three most likely ways this plan fails: [your plan]
```

DissSkill critiques the decision, not the person. It does not replace professional legal, medical, or financial advice.

<!-- andy-author-card:start -->
## 作者 / About the author

**AI 酋长 Andy（Andy Liu，GitHub/X @AIPMAndy）**：前腾讯/百度 AI 产品专家，大模型独角兽前 VP，现专注 AI + 产品方法论创业。

微信 `AIPMAndy`（备注「DissSkill」） · [X @AIPMAndy](https://x.com/AIPMAndy) · [Telegram @AIPMAndy](https://t.me/AIPMAndy) · [个人官网 metaver.vip](https://metaver.vip/)

*AI Chief Andy (Andy Liu, @AIPMAndy on GitHub and X) is a former Tencent and Baidu AI product expert and former VP at an LLM unicorn, now a serial entrepreneur focused on AI and product methodology.*

### 作者的其他项目

- [AndySoul](https://github.com/AIPMAndy/AndySoul)：CLAUDE.md / AGENTS.md 规则模板，让 Claude Code、Codex、Cursor 少犯错
- [DNA Memory](https://github.com/AIPMAndy/dna-memory)：Claude Code、Codex 共用的本地 AI Agent 记忆 MCP
- [SafeSkill](https://github.com/AIPMAndy/safeskill)：装 AI Skill 之前，先扫危险命令、提示注入和密钥泄露
- [OpenClaw Skills 中文精选](https://github.com/AIPMAndy/awesome-openclaw-skills-CN)：OpenClaw Skills 分类整理，附国产模型接入指南
- [Grok Bot 中文攻略](https://aipmandy.github.io/grok-bot-handbook/)：AI Agent 中文教程

<!-- andy-author-card:end -->

## License & Author

[MIT License](LICENSE) · Created by Andy ([@AIPMAndy](https://github.com/AIPMAndy))
