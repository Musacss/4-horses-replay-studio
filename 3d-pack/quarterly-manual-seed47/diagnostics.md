# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [FEASIBLE (NO WIN)]: 6 operational issue(s) (0 critical, 6 warning) across 4/12 week(s); operating cost €61,613.25, CapEx €0.00, peak wear 0.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €0.00
- **Total Operating Cost:** €61,613.25
- **Active Labor Ticks:** 46883
- **Peak Equipment Wear:** 0
- **Peak Backlog Carryover Out:** 4
- **Total Robot Jams:** 0
- **Total Overtime Ticks:** 1099
- **Hiring & Retraining Friction Cost:** €0.00
- **Evaluation Failure Reasons:** operating cost did not beat manual baseline, active labor ticks did not beat manual baseline, automated pack share below minimum threshold

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 0 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 4 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 2 |

## Week-by-Week Telemetry (12 Weeks, 6 Issue(s): 0 Critical, 6 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 131/131 | 0 | 0 | €4,687.70 |
| 1 | baseline_steady | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 140/140 | 0 | 0 | €4,689.00 |
| 2 | autumn_ramp | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 144/144 | 0 | 0 | €4,699.60 |
| 3 | fragile_promo | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 170/170 | 0 | 0 | €5,075.00 |
| 4 | mid_quarter | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 132/132 | 0 | 0 | €4,684.20 |
| 5 | pre_peak_prep | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 131/131 | 0 | 0 | €4,691.80 |
| 6 | early_holiday | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 138/138 | 0 | 0 | €4,687.80 |
| 7 | singles_day_wave | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 191/191 | 0 | 317 | €6,111.95 |
| 8 | black_friday_peak | WARNING | manual | 6 (3 Z3) | 0->0 | 0->4 | 198/202 | 0 | 645 | €7,400.55 |
| 9 | cyber_week_peak | WARNING | manual | 6 (3 Z3) | 0->0 | 4->0 | 187/187 | 0 | 137 | €5,512.45 |
| 10 | post_peak_steady | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 120/120 | 0 | 0 | €4,677.00 |
| 11 | quarter_close | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 152/152 | 0 | 0 | €4,696.20 |

## Detailed Weekly Operational Findings

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 23 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 62 late delivery(ies); 317 overtime tick(s).

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 115 late delivery(ies); 645 overtime tick(s).
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=0, carryover_out=4 (shift unfinished=4).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 39 late delivery(ies); 137 overtime tick(s).
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=4, carryover_out=0 (shift unfinished=0).
