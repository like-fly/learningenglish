---
updated: 2026-08-18
phase: reading-foundation
phase_label: 阅读基础期
difficulty_band: "80–120 words; direct sentences; up to 3 core-word glosses"
cefr_reference: "A1–A2 reading range (provisional)"
next_task: review-001
next_task_file: null
next_task_status: ready
last_session: 2026-08-18-001
completed_sessions: 5
partial_sessions: 0
total_minutes: 86
effective_sessions_since_review: 5
effective_sessions_since_assessment: 5
review_due: true
assessment_due: false
recent_comprehension_pct: [50, 40, 86, 83, 67]
baseline_wpm: 45.9
recent_wpm: 40.6
recent_summary_score: 2
vocabulary_due: 0
---

# 当前学习状态

## 下一任务

**第一次五次学习复盘**

启动方式：下一次向 Codex 发送“开始今天的学习”。本次已达到 5 次有效学习，下次先从五份 session 原始记录复算理解率、摘要、速度和词汇表现，完成阶段复盘后再决定下一组任务。

## 当前判断

- 三次基线诊断已经完成，进入阅读基础期。CEFR 仅暂记为 A1–A2 阅读参考区间，不作为固定等级。
- 诊断 1：344 词，阅读 450 秒，45.9 WPM，理解率 50%，摘要 2/4。
- 诊断 2：189 词，阅读 240 秒，查词 1 次，理解率 40%，一句摘要 2/4；未确认查词时点，因此不计算 WPM。
- 诊断 3：184 词；首次阅读因核心词 `lend` 受阻，分段提供词义后理解率 86%，摘要 2/4。该理解率是支持后结果，不能和前两次独立表现直接比较；查词数和有效阅读时间无法确认，不计算 WPM。
- 基线显示：解决阻断性核心词后，能抓住具体好处、管理困难和连接短语的指代；当前主要障碍是高频动词，以及先识别主语和带时态谓语。
- 起始材料调整为 80–120 词、直接句式、最多预教三个核心词。复述先完成“谁 + 做什么”，再增加原因和细节。
- 阅读基础 1：102 词，独立阅读 120 秒，查词 0 次，51.0 WPM，理解率 83%，摘要 3/4。材料比基线短且更直接，速度暂不与基线直接比较；下一步需要识别 `must` 指向的责任信息。
- 阅读基础 2 最低任务：67 词，独立阅读 99 秒，查词 0 次，40.6 WPM，理解率 67%，摘要 2/4。首次准确识别 `must water` 的责任，但把 `can help` 误写成必做事项；提示后能删除该错误。材料很短，不与此前速度直接比较。
- 已完成第 5 次有效学习，`review_due` 已设为 `true`。下次先复盘，不直接进入新课。

## 最近指标

| 指标 | 数据 |
| --- | ---: |
| 最近 5 次理解率 | 50%, 40%, 86%（分段支持）, 83%, 67% |
| 基线 WPM | 45.9 |
| 最近独立阅读 WPM | 40.6（67 词最低任务，不与此前直接比较） |
| 最近摘要评分 | 2/4 |
| 到期词汇 | 0 |

## 状态维护约定

- `complete` 和 `minimum` 增加 `completed_sessions`。
- `partial` 只增加 `partial_sessions` 和实际分钟；继续同一任务时更新原记录。
- 每 5 次有效学习设置 `review_due: true`。
- 每 20 次有效学习设置 `assessment_due: true`。
- `recent_comprehension_pct` 最多保留最近 5 个有效数据点。
