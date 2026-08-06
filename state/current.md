---
updated: 2026-08-06
phase: diagnostic
phase_label: 诊断期
difficulty_band: unassigned
cefr_reference: unassigned
next_task: baseline-01
next_task_file: assessments/baseline.md
next_task_status: ready
last_session: null
completed_sessions: 0
partial_sessions: 0
total_minutes: 0
effective_sessions_since_review: 0
effective_sessions_since_assessment: 0
review_due: false
assessment_due: false
recent_comprehension_pct: []
baseline_wpm: null
recent_summary_score: null
vocabulary_due: 0
---

# 当前学习状态

## 下一任务

**基线诊断 1：限时阅读与理解**

位置：`assessments/baseline.md` 的“诊断 1”。

启动方式：向 Codex 发送“开始今天的学习”。Codex 应只展示诊断 1 的说明、文章和问题，不展示评分参考。

## 当前判断

- 尚未完成正式诊断，不分配 CEFR 等级。
- 当前自评为基础阅读型，初始材料先使用 344 词的原创社会话题短文。
- 完成前三次诊断后，依据实际数据选择阅读基础期的起始难度。

## 最近指标

| 指标 | 数据 |
| --- | ---: |
| 最近 5 次理解率 | 尚无数据 |
| 基线 WPM | 尚未测量 |
| 最近摘要评分 | 尚无数据 |
| 到期词汇 | 0 |

## 状态维护约定

- `complete` 和 `minimum` 增加 `completed_sessions`。
- `partial` 只增加 `partial_sessions` 和实际分钟；继续同一任务时更新原记录。
- 每 5 次有效学习设置 `review_due: true`。
- 每 20 次有效学习设置 `assessment_due: true`。
- `recent_comprehension_pct` 最多保留最近 5 个有效数据点。
