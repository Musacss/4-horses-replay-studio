# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [FEASIBLE (NO WIN)]: 1 operational issue(s) (0 critical, 1 warning) across 1/12 week(s); operating cost €83,817.36, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €83,817.36
- **Active Labor Ticks:** 36139
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 39
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
| 0 | baseline_open | WARNING | bypass + maint (comm) | 8 (4 Z3) | 0->1 | 0->0 | 131/131 | 9 | 0 | €7,295.33 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 8 (4 Z3) | 1->1 | 0->0 | 140/140 | 3 | 0 | €6,944.33 |
| 2 | autumn_ramp | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 144/144 | 2 | 0 | €6,952.03 |
| 3 | fragile_promo | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 170/170 | 3 | 0 | €6,967.23 |
| 4 | mid_quarter | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 132/132 | 5 | 0 | €6,933.03 |
| 5 | pre_peak_prep | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 131/131 | 4 | 0 | €6,940.33 |
| 6 | early_holiday | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 138/138 | 0 | 0 | €6,938.43 |
| 7 | singles_day_wave | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 191/191 | 2 | 0 | €6,990.23 |
| 8 | black_friday_peak | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 202/202 | 1 | 0 | €7,000.13 |
| 9 | cyber_week_peak | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 183/183 | 4 | 0 | €6,978.93 |
| 10 | post_peak_steady | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 120/120 | 2 | 0 | €6,922.23 |
| 11 | quarter_close | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 152/152 | 4 | 0 | €6,955.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (8 -> 8 worker(s)), incurring €355.00 in hiring/retraining friction.
