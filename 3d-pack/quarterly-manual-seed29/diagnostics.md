# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [FEASIBLE (NO WIN)]: 4 operational issue(s) (0 critical, 4 warning) across 4/12 week(s); operating cost €60,053.60, CapEx €0.00, peak wear 0.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €0.00
- **Total Operating Cost:** €60,053.60
- **Active Labor Ticks:** 45623
- **Peak Equipment Wear:** 0
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 0
- **Total Overtime Ticks:** 794
- **Hiring & Retraining Friction Cost:** €0.00
- **Evaluation Failure Reasons:** operating cost did not beat manual baseline, active labor ticks did not beat manual baseline, automated pack share below minimum threshold

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 0 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 4 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 4 Issue(s): 0 Critical, 4 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 134/134 | 0 | 0 | €4,693.60 |
| 1 | baseline_steady | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 132/132 | 0 | 0 | €4,684.20 |
| 2 | autumn_ramp | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 139/139 | 0 | 0 | €4,688.40 |
| 3 | fragile_promo | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 167/167 | 0 | 0 | €4,725.30 |
| 4 | mid_quarter | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 130/130 | 0 | 0 | €4,687.10 |
| 5 | pre_peak_prep | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 114/114 | 0 | 0 | €4,673.40 |
| 6 | early_holiday | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 141/141 | 0 | 0 | €4,710.10 |
| 7 | singles_day_wave | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 191/191 | 0 | 262 | €6,087.10 |
| 8 | black_friday_peak | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 192/192 | 0 | 290 | €6,154.70 |
| 9 | cyber_week_peak | WARNING | manual | 6 (3 Z3) | 0->0 | 0->0 | 189/189 | 0 | 242 | €5,569.00 |
| 10 | post_peak_steady | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 126/126 | 0 | 0 | €4,688.80 |
| 11 | quarter_close | OK | manual | 6 (3 Z3) | 0->0 | 0->0 | 138/138 | 0 | 0 | €4,691.90 |

## Detailed Weekly Operational Findings

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 65 late delivery(ies); 262 overtime tick(s).

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 67 late delivery(ies); 290 overtime tick(s).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 34 late delivery(ies); 242 overtime tick(s).
