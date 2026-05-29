# Boss Sales Diagnosis Skill

一个面向 B2B 老板、销售负责人和专家型个体的销售诊断 Skill。

它不是销售话术库，也不是通用销售 chatbot。它尝试把长期 B2B 销售现场中形成的判断力，沉淀为可调用的 AI 工作助手：用来诊断真实销售卡点、判断机会质量、识别信任缺口、重构客户价值，并给出下一步行动。

## What It Does

- 诊断 B2B 销售中的真实卡点
- 判断客户问题背后的信任、价值、决策链和时机问题
- 生成老板视角的销售推进建议
- 输出可直接使用的微信、邮件、会议和内部汇报文本
- 帮助超级个体或企业把隐性经验转化为 AI Skill

## Included Assets

- `100` 条销售判断规则
- `30` 个高频销售场景
- `20` 个微案例
- 一套销售诊断框架
- 一套诊断问题库
- 一套交易分诊规则：Invest / Repair / Nurture / Stop
- 一套客户和内部交付物模板
- 一套输出模板
- 一个可被 Codex 使用的 Skill 定义

## Installation

Clone this repository and copy the skill folder into your Codex skills directory:

```bash
cp -R boss-sales-diagnosis ~/.codex/skills/
```

Then start a new Codex session and ask a concrete B2B sales question, for example:

```text
客户嫌我们贵，报价后一直不回复，我该怎么判断这单还有没有机会？
```

## Example Use Cases

- 客户只问价格，不愿意谈需求
- 报价后客户沉默
- 竞争对手低价抢单
- 老关系突然失效
- 销售员见不到决策人
- 大客户提出特殊条件
- 老板不知道这单是否值得继续投入
- 企业想把销售总监或老板的经验沉淀成 AI 工作助手

## Design Principles

- 销售首先是商业判断问题，不是话术问题
- 真正的成交来自信任、价值、时机和决策链的共同成立
- 不把低价当作唯一竞争对手
- 不为了成交而牺牲长期信任
- 不在关键信息缺失时假装确定
- 不只建议“解释价值”，而是直接生成可使用的交付物
- 不把内部规则、评分表和模板名暴露给最终用户
- 根据问题复杂度自动选择短诊断、标准诊断或深度审单
- 不用大词包装普通建议
- 不把 AI 做成“问我任何问题”的聊天框，而是做成可复用的判断系统

## For One-Person Companies

This project is also a sample of how a one-person company can turn personal expertise into an AI-deliverable asset.

The real product is not only this sales diagnosis skill. The deeper pattern is:

```text
personal experience -> judgment rules -> scenarios -> cases -> workflow -> AI skill
```

That pattern can be reused for sales, consulting, customer service, presales, bidding, project review, and other expert-heavy business domains.

## License

MIT License. See `LICENSE`.
