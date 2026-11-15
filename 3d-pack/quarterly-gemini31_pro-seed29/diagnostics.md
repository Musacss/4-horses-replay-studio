# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [WIN]: 3 operational issue(s) (0 critical, 3 warning) across 3/12 week(s); operating cost €52,619.21, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €52,619.21
- **Active Labor Ticks:** 31460
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 46
- **Total Overtime Ticks:** 45
- **Hiring & Retraining Friction Cost:** €110.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 1 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 2 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 3 Issue(s): 0 Critical, 3 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 5 (2 Z3) | 0->1 | 0->0 | 134/134 | 12 | 0 | €4,417.13 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 5 (2 Z3) | 1->1 | 0->0 | 132/132 | 7 | 0 | €4,338.03 |
| 2 | autumn_ramp | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 139/139 | 4 | 0 | €4,344.33 |
| 3 | fragile_promo | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 167/167 | 4 | 0 | €4,377.73 |
| 4 | mid_quarter | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 130/130 | 1 | 0 | €4,340.33 |
| 5 | pre_peak_prep | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 114/114 | 2 | 0 | €4,321.83 |
| 6 | early_holiday | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 141/141 | 1 | 0 | €4,366.63 |
| 7 | singles_day_wave | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 191/191 | 2 | 0 | €4,391.13 |
| 8 | black_friday_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 192/192 | 5 | 1 | €4,441.28 |
| 9 | cyber_week_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 189/189 | 2 | 44 | €4,592.43 |
| 10 | post_peak_steady | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 126/126 | 3 | 0 | €4,340.83 |
| 11 | quarter_close | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 138/138 | 3 | 0 | €4,347.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 5 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 3 late delivery(ies); 1 overtime tick(s).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 9 late delivery(ies); 44 overtime tick(s).
