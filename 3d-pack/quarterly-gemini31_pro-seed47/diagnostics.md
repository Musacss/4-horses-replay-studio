# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [WIN]: 4 operational issue(s) (0 critical, 4 warning) across 4/12 week(s); operating cost €54,479.11, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €54,479.11
- **Active Labor Ticks:** 32439
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 39
- **Total Overtime Ticks:** 291
- **Hiring & Retraining Friction Cost:** €110.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 1 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 3 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 4 Issue(s): 0 Critical, 4 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 5 (2 Z3) | 0->1 | 0->0 | 131/131 | 9 | 0 | €4,410.33 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 5 (2 Z3) | 1->1 | 0->0 | 140/140 | 3 | 0 | €4,349.33 |
| 2 | autumn_ramp | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 144/144 | 2 | 0 | €4,357.03 |
| 3 | fragile_promo | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 170/170 | 3 | 0 | €4,372.23 |
| 4 | mid_quarter | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 132/132 | 5 | 0 | €4,338.03 |
| 5 | pre_peak_prep | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 131/131 | 4 | 0 | €4,345.33 |
| 6 | early_holiday | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 138/138 | 0 | 0 | €4,343.43 |
| 7 | singles_day_wave | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 191/191 | 2 | 6 | €4,498.73 |
| 8 | black_friday_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 202/202 | 1 | 285 | €6,377.38 |
| 9 | cyber_week_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 183/183 | 4 | 0 | €4,399.93 |
| 10 | post_peak_steady | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 120/120 | 2 | 0 | €4,327.23 |
| 11 | quarter_close | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 152/152 | 4 | 0 | €4,360.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 5 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 6 late delivery(ies); 6 overtime tick(s).

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 101 late delivery(ies); 285 overtime tick(s).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).
