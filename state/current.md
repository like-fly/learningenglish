---
updated: 2026-08-06
phase: diagnostic
phase_label: 诊断期
difficulty_band: unassigned
cefr_reference: unassigned
next_task: baseline-02
next_task_file: assessments/baseline.md
next_task_status: ready
last_session: 2026-08-06-001
completed_sessions: 1
partial_sessions: 0
total_minutes: 18
effective_sessions_since_review: 1
effective_sessions_since_assessment: 1
review_due: false
assessment_due: false
recent_comprehension_pct: [50]
baseline_wpm: 45.9
recent_summary_score: 2
vocabulary_due: 0
---

# 当前学习状态

## 下一任务

**基线诊断 2：长句拆解与语境推断**

位置：`assessments/baseline.md` 的“诊断 2”。

启动方式：另一天向 Codex 发送“开始今天的学习”。Codex 应先进行简短回忆，再展示诊断 2 的说明、文章和问题。

## 当前判断

- 已完成诊断 1，暂不分配 CEFR 等级。
- 诊断 1：344 词，阅读 450 秒，45.9 WPM，理解率 50%，摘要 2/4。
- 本次挫败感为 5/5；需要继续观察下一次表现，单次结果不触发难度调整。
- 完成前三次诊断后，依据实际数据选择阅读基础期的起始难度。

## 最近指标

| 指标 | 数据 |
| --- | ---: |
| 最近 5 次理解率 | 50% |
| 基线 WPM | 45.9 |
| 最近摘要评分 | 2/4 |
| 到期词汇 | 0 |

## 状态维护约定

- `complete` 和 `minimum` 增加 `completed_sessions`。
- `partial` 只增加 `partial_sessions` 和实际分钟；继续同一任务时更新原记录。
- 每 5 次有效学习设置 `review_due: true`。
- 每 20 次有效学习设置 `assessment_due: true`。
- `recent_comprehension_pct` 最多保留最近 5 个有效数据点。
