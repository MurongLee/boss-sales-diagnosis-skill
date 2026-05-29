# Output Templates

Use Chinese by default when the user writes Chinese. Keep reports concise unless the user asks for depth.

## Output Depth Selector

Choose the smallest output that solves the user's problem.

- **Short Diagnosis**: Use when the user asks a one-sentence question or wants quick advice. Length: 250-500 Chinese characters plus one copy-ready message if useful.
- **Standard Diagnosis**: Use when the user asks for diagnosis and provides limited context. Length: 700-1200 Chinese characters. Include assumptions, real blockage, next action, and one draft artifact.
- **Deep Deal Review**: Use only when the user asks for a review/report/deep analysis, asks whether to invest, or provides rich context. Include scoring only here, unless explicitly requested.

Never expose internal labels such as "question bank", "rubric", "template file", or file names. Translate internal process into natural business language.

## Short Diagnosis

Use this when the user asks a quick question.

```markdown
我的判断：[一句话定性。要敢判断，不要铺垫太久。]

我先按一个常见情况判断：[一句话说明关键假设，例如“你接触的大概率不是最终拍板人，方案前也没有约定复盘”。]

真正问题不是 [表面问题]，而是 [真实问题]。

下一步不要 [错误动作]。只做一次 [正确动作]；如果没反应，就 [降级为 Nurture / Stop / 等触发点]。

可以这样发：
[可复制话术。不要像销售话术课，要像正常业务沟通。]

我还需要确认三件事，才能把判断做准：[最多 3 个问题。]
```

## Standard Diagnosis

Use this when the user asks for a diagnosis with limited facts.

```markdown
**先说结论**
[一句话判断：这单最可能卡在哪里，以及建议 Invest / Repair / Nurture / Stop。]

**我先按这几个假设判断**
[用一小段自然语言写假设，不要列成系统检查表。说明如果假设不成立，判断会怎么变。]

**当前局势**
[2-4 句话判断这单现在处于什么状态。不要复述太多背景。]

**真正卡点**
[判断这单卡在价格、信任、价值翻译、决策链、资源、时机，还是机会质量。]

**你可能误判了什么**
[指出 1-2 个误判。语气直接，但要给理由。]

**下一步三件事**
1. [具体动作]
2. [具体动作]
3. [具体动作]

**可以直接使用**
[生成微信、邮件、会议议程、一页纸骨架、内部汇报中的一种。用户未提供行业/产品时，用通用业务语言填充，并说明可进一步替换成行业版。]

**是否继续投入**
[Invest / Repair / Nurture / Stop，并用一句话解释。不默认展示评分表。]
```

## Deep Deal Review

```markdown
**先说结论**
[一句话判断：机会质量、主要卡点、投入建议。]

**关键信息缺口**
[列出最多 3 个会改变判断的问题。不要说这些问题来自哪里。]

**我的判断假设**
[说明当前基于哪些假设继续判断。]

**机会质量**
[需要时展示 0-12 分评分。不要机械铺满表格；只展示影响结论的维度。]

**当前局势**
[判断局势。]

**真正卡点**
[判断真实阻碍。]

**信任与价值缺口**
[说明缺哪类信任，以及客户/联系人/决策人还没看见什么价值。]

**推进路径**
[给出让客户、决策人、销售方都更好的路径。]

**下一步动作**
1. [动作]
2. [动作]
3. [动作]

**可直接使用的交付物**
[生成一个或多个具体草稿。]

**是否继续投入**
[Invest / Repair / Nurture / Stop，并说明边界和退出条件。]
```

## Follow-Up Questions

Ask questions only when missing facts materially change the diagnosis. Use no more than 3.

Good questions:
- 这单大概金额和毛利水平是多少？
- 现在你接触到的是使用人、部门负责人，还是最终拍板的人？
- 客户原话是什么？最好贴出最关键的 2-3 句。
- 方案发出前，有没有约定明确的下一步？
- 竞争对手便宜在哪里，是价格低、关系强，还是交付风险看起来更小？
- 你现在想要的结果是什么：救这单、判断值不值得救、写跟进话术，还是向老板申请资源？

## Public Output Rules

- Do not mention internal files, internal method names, or that you used a question bank/rubric/template.
- Do not show "information gap analysis" as a separate technical section unless the user asks how the diagnosis was produced.
- Prefer "我先按一个常见情况判断" over "由于信息不足，我按假设推进".
- Prefer "这单只值得一次修复动作" over "Repair limited once" unless the user likes English labels.
- If using Invest/Repair/Nurture/Stop, explain the Chinese meaning the first time.
- Keep the user's immediate job in view: decide, reply, ask for meeting, prepare one-pager, apply for resources, or stop chasing.

## Copy-Ready Message Pattern

When generating a customer-facing message, keep it:
- short enough to send
- respectful of customer time
- focused on business value or risk
- not desperate
- not defensive

Pattern:

```text
[称呼]，我复盘了一下上次沟通，感觉我可能还没有把 [客户关心的问题] 讲透。

这件事的关键不只是 [表面议题]，而是 [业务影响/风险/内部解释]。

我建议我们用 15 分钟把 [一个具体判断/对比/方案] 过一下。如果过完你觉得价值不够，我也好及时调整，不继续打扰你。
```

## Internal Boss Note Pattern

```markdown
**机会判断**
[这不是普通订单/这是普通订单，不值得特殊投入]

**客户长期价值**
[金额、行业标杆、复购、转介绍、战略入口]

**当前阻碍**
[资源、价格、交付、决策链、竞品]

**资源申请**
[具体要什么资源，要多久，用在什么动作上]

**风险控制**
[分阶段投入、客户里程碑、退出条件、折扣交换条件]

**建议决策**
[批准/不批准/有限批准，并说明原因]
```
