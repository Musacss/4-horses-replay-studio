# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [FEASIBLE (NO WIN)]: 1 operational issue(s) (0 critical, 1 warning) across 1/12 week(s); operating cost €83,800.96, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €83,800.96
- **Active Labor Ticks:** 34924
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 46
- **Total Overtime Ticks:** 0
- **Hiring & Retraining Friction Cost:** €355.00
- **Evaluation Failure Reasons:** operating cost did not beat manual baseline

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 1 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 0 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 1 Issue(s): 0 Critical, 1 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass + maint (comm) | 8 (4 Z3) | 0->1 | 0->0 | 134/134 | 12 | 0 | €7,302.13 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 8 (4 Z3) | 1->1 | 0->0 | 132/132 | 7 | 0 | €6,933.03 |
| 2 | autumn_ramp | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 139/139 | 4 | 0 | €6,939.33 |
| 3 | fragile_promo | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 167/167 | 4 | 0 | €6,972.73 |
| 4 | mid_quarter | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 130/130 | 1 | 0 | €6,935.33 |
| 5 | pre_peak_prep | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 114/114 | 2 | 0 | €6,916.83 |
| 6 | early_holiday | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 141/141 | 1 | 0 | €6,961.63 |
| 7 | singles_day_wave | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 191/191 | 2 | 0 | €6,986.13 |
| 8 | black_friday_peak | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 192/192 | 5 | 0 | €6,987.03 |
| 9 | cyber_week_peak | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 189/189 | 2 | 0 | €6,988.43 |
| 10 | post_peak_steady | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 126/126 | 3 | 0 | €6,935.83 |
| 11 | quarter_close | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 138/138 | 3 | 0 | €6,942.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (8 -> 8 worker(s)), incurring €355.00 in hiring/retraining friction.
