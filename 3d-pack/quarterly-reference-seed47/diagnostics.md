# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [WIN]: 5 operational issue(s) (0 critical, 5 warning) across 5/12 week(s); operating cost €47,958.21, CapEx €15,300.00, peak wear 2.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €47,958.21
- **Active Labor Ticks:** 33517
- **Peak Equipment Wear:** 2
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 65
- **Total Overtime Ticks:** 115
- **Hiring & Retraining Friction Cost:** €455.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 3 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 2 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 5 Issue(s): 0 Critical, 5 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (2 Z3) | 0->1 | 0->0 | 131/131 | 9 | 0 | €3,840.33 |
| 1 | baseline_steady | OK | bypass (comm) | 4 (2 Z3) | 1->2 | 0->0 | 140/140 | 7 | 0 | €3,597.53 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 144/144 | 2 | 0 | €3,642.03 |
| 3 | fragile_promo | WARNING | bypass | 4 (2 Z3) | 1->2 | 0->0 | 170/170 | 6 | 107 | €4,998.48 |
| 4 | mid_quarter | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 132/132 | 5 | 0 | €3,623.03 |
| 5 | pre_peak_prep | OK | bypass | 4 (2 Z3) | 1->2 | 0->0 | 131/131 | 7 | 0 | €3,593.53 |
| 6 | early_holiday | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 138/138 | 0 | 0 | €3,628.43 |
| 7 | singles_day_wave | WARNING | bypass | 5 (3 Z3) | 1->2 | 0->0 | 191/191 | 7 | 0 | €4,530.23 |
| 8 | black_friday_peak | WARNING | bypass + maint | 5 (3 Z3) | 2->1 | 0->0 | 202/202 | 1 | 8 | €4,745.13 |
| 9 | cyber_week_peak | OK | bypass | 5 (3 Z3) | 1->2 | 0->0 | 183/183 | 8 | 0 | €4,437.13 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 120/120 | 2 | 0 | €3,722.23 |
| 11 | quarter_close | OK | bypass | 4 (2 Z3) | 1->2 | 0->0 | 152/152 | 11 | 0 | €3,600.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 77 late delivery(ies); 107 overtime tick(s).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 15 late delivery(ies); 8 overtime tick(s).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
