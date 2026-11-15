# Quarterly Rollout Operational Diagnostics (Seed 11)

**Summary:** Quarter seed 11 [FEASIBLE (NO WIN)]: 6 operational issue(s) (1 critical, 5 warning) across 4/12 week(s); operating cost €59,609.70, CapEx €0.00, peak wear 0.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €0.00
- **Total Operating Cost:** €59,609.70
- **Active Labor Ticks:** 45920
- **Peak Equipment Wear:** 0
- **Peak Backlog Carryover Out:** 5
- **Total Robot Jams:** 0
- **Total Overtime Ticks:** 710
- **Hiring & Retraining Friction Cost:** €0.00
- **Evaluation Failure Reasons:** operating cost did not beat manual baseline, active labor ticks did not beat manual baseline, automated pack share below minimum threshold

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 0 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 4 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 2 |

## Week-by-Week Telemetry (12 Weeks, 6 Issue(s): 1 Critical, 5 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 140/140 | 0 | 0 | €4,689.00 |
| 1 | baseline_steady | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 133/133 | 0 | 0 | €4,688.90 |
| 2 | autumn_ramp | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 134/134 | 0 | 0 | €4,689.50 |
| 3 | fragile_promo | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 169/169 | 0 | 0 | €4,710.50 |
| 4 | mid_quarter | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 129/129 | 0 | 0 | €4,702.90 |
| 5 | pre_peak_prep | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 115/115 | 0 | 0 | €4,674.00 |
| 6 | early_holiday | CRITICAL | manual | 6 (3 Z3) | 0->0 | 0->0 | 144/145 | 0 | 0 | €5,017.00 |
| 7 | singles_day_wave | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 176/176 | 0 | 33 | €4,915.95 |
| 8 | black_friday_peak | WARNING | manual | 6 (3 Z3) | 0->0 | 0->5 | 192/197 | 0 | 657 | €7,022.05 |
| 9 | cyber_week_peak | WARNING | manual | 6 (3 Z3) | 0->0 | 5->0 | 180/180 | 0 | 20 | €5,122.00 |
| 10 | post_peak_steady | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 134/134 | 0 | 0 | €4,685.40 |
| 11 | quarter_close | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 139/139 | 0 | 0 | €4,692.50 |

## Detailed Weekly Operational Findings

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 10 late delivery(ies); 33 overtime tick(s).

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 90 late delivery(ies); 657 overtime tick(s).
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=0, carryover_out=5 (shift unfinished=5).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 24 late delivery(ies); 20 overtime tick(s).
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=5, carryover_out=0 (shift unfinished=0).
