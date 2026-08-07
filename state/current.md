---
updated: 2026-08-07
phase: diagnostic
phase_label: 诊断期
difficulty_band: unassigned
cefr_reference: unassigned
next_task: baseline-03
next_task_file: assessments/baseline.md
next_task_status: ready
last_session: 2026-08-07-001
completed_sessions: 2
partial_sessions: 0
total_minutes: 34
effective_sessions_since_review: 2
effective_sessions_since_assessment: 2
review_due: false
assessment_due: false
recent_comprehension_pct: [50, 40]
baseline_wpm: 45.9
recent_summary_score: 2
vocabulary_due: 0
---

# 当前学习状态

## 下一任务

**基线诊断 3：英文复述与延迟回忆**

位置：`assessments/baseline.md` 的“诊断 3”。

启动方式：至少下一天向 Codex 发送“开始今天的学习”。Codex 应先复习到期词汇，并测试 `represent`、`participation`、`overlooked` 的延迟回忆，再展示诊断 3 的文章和问题。

## 当前判断

- 已完成诊断 1 和诊断 2，暂不分配 CEFR 等级。
- 诊断 1：344 词，阅读 450 秒，45.9 WPM，理解率 50%，摘要 2/4。
- 诊断 2：189 词，阅读 240 秒，查词 1 次，理解率 40%，一句摘要 2/4；未确认查词时点，因此不计算 WPM。
- 两次理解率均低于 70%；诊断 3 使用句式更直接的材料，按降低一个难度档处理。诊断 2 的精力为 4/5、挫败感为 1/5。
- 当前重点是先识别主语和带时态的谓语，再处理 `which`、`when`、`where` 等从句。
- 完成前三次诊断后，依据实际数据选择阅读基础期的起始难度。

## 最近指标

| 指标 | 数据 |
| --- | ---: |
| 最近 5 次理解率 | 50%, 40% |
| 基线 WPM | 45.9 |
| 最近摘要评分 | 2/4 |
| 到期词汇 | 0 |

## 状态维护约定

- `complete` 和 `minimum` 增加 `completed_sessions`。
- `partial` 只增加 `partial_sessions` 和实际分钟；继续同一任务时更新原记录。
- 每 5 次有效学习设置 `review_due: true`。
- 每 20 次有效学习设置 `assessment_due: true`。
- `recent_comprehension_pct` 最多保留最近 5 个有效数据点。
