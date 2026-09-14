# Grill Me × FDE

## 简体中文

这是一个用于重要想法、方案和决策的对话式拷问技能。它先检查逻辑，再用 FDE 视角检查需求、价值与落地。

### 使用方式

- 明确说“Grill me”或“拷问我”：直接开始。
- 对话中出现重要但未经验证的主张、项目、产品、流程或自动化想法时：先问“要进入 Grill Me 吗？”等你决定。
- 你回答“不需要”后，按普通对话继续；同一话题不重复邀请。你也可以随时说“停止”。
- 你可以要求“逐题问”；否则按依赖关系组织问题轮次。

### 拷问流程

1. **逻辑拷问：**用决策树梳理主张、事实、解释、假设和结论；先问当前依赖已解决的问题，给出建议答案，等待回答后重算下一轮。先核实助手能自行查证的事实。
2. **FDE 拷问：**逻辑成立或已转化为可验证假设后，依次判断真实需求、需求价值与优先级、最小完整行动闭环、生产落地与人机控制、反馈闭环及产品复利。
3. **结束：**总结逻辑强弱、需求证据、价值、最小范围、落地风险和建议。拷问结束不代表自动开始实施。

两阶段避免重复：逻辑阶段判断“是否成立”，FDE 阶段判断“成立后是否值得做、做多大、怎么落地”。

## English

This conversational grilling skill pressure-tests consequential ideas, plans, and decisions. It tests the logic first, then examines demand, value, and delivery through an FDE lens.

### How to use it

- Say “Grill me” explicitly to start immediately.
- When a consequential but unverified claim, project, product, workflow, or automation idea appears implicitly, ask whether the user wants to enter Grill Me and wait.
- If the user declines, continue normally and do not offer again for the same topic. Stop immediately if asked.
- The user may request one question at a time; otherwise, organize questions into dependency-aware rounds.

### Interview flow

1. **Logic grilling:** map the claim, facts, interpretations, assumptions, and conclusion as a decision tree. Ask the current frontier whose prerequisites are settled, provide recommended answers, wait, then recompute. Verify facts the assistant can check.
2. **FDE grilling:** once the logic is supported or converted into a testable hypothesis, examine real demand, value and priority, the smallest complete action loop, production readiness and human controls, feedback, and product compounding.
3. **Close:** summarize reasoning strength, demand evidence, value, smallest scope, delivery risks, and recommendation. Finishing the interview does not start implementation automatically.

The phases avoid repetition: the logic phase asks whether the claim holds; the FDE phase asks whether it is worth doing, how small it can be, and how it can work in production.

## 日本語

この対話型グリル・ミー・スキルは、重要なアイデア、計画、意思決定を検証します。まず論理を問い、その後 FDE の視点から需要、価値、実運用を確認します。

### 使い方

- 「Grill me」と明示された場合は、確認を挟まず開始します。
- 重要だが未検証の主張、プロジェクト、製品、業務フロー、自動化案が会話に現れた場合は、開始前に参加するか尋ね、回答を待ちます。
- 辞退された場合は通常の会話を続け、同じ話題で再度勧めません。いつでも「停止」と言えます。
- 逐一一問ずつ進めるよう依頼できます。指定がなければ、依存関係に沿った質問ラウンドを使います。

### 質問の流れ

1. **論理検証：**主張、事実、解釈、前提、結論を意思決定ツリーに整理します。前提が解決済みの現在の質問群を提示し、推奨回答を添えて返答を待ち、その後ツリーを更新します。確認可能な事実は先に調べます。
2. **FDE 検証：**論理が支持された、または検証可能な仮説になった後、実際の需要、価値と優先順位、最小の完結した行動ループ、本番運用と人間の制御、フィードバック、プロダクトの複利を確認します。
3. **終了：**論理の強さ、需要の証拠、価値、最小スコープ、運用リスク、推奨をまとめます。質問を終えても自動的に実装を始めません。

2つの段階は重複を避けます。論理段階では「成立するか」を確認し、FDE 段階では「取り組む価値、最小範囲、本番運用」を確認します。

## 参照出处 / References / 参考

- 中文：逻辑拷问主要参考 [Matt Pocock 的 grilling](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md)，提问表达参考 [RobMitt 的 grill-me-skill](https://github.com/RobMitt/grill-me-skill)，FDE 部分结合《FDE入门到精通》。
- English: The logic-grilling flow adapts [Matt Pocock's grilling](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md), question phrasing draws on [RobMitt's grill-me-skill](https://github.com/RobMitt/grill-me-skill), and the FDE layer draws on 《FDE入门到精通》.
- 日本語：論理検証は [Matt Pocock の grilling](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md) を主に参考にし、質問表現には [RobMitt の grill-me-skill](https://github.com/RobMitt/grill-me-skill)、FDE 部分には《FDE入门到精通》を参考にしています。
