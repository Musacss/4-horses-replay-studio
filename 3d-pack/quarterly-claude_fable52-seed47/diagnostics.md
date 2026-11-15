# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [WIN]: 7 operational issue(s) (0 critical, 7 warning) across 6/12 week(s); operating cost €47,841.11, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €47,841.11
- **Active Labor Ticks:** 33133
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 39
- **Total Overtime Ticks:** 39
- **Hiring & Retraining Friction Cost:** €655.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 1 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 5 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 1 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 7 Issue(s): 0 Critical, 7 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (1 Z3) | 0->1 | 0->0 | 131/131 | 9 | 0 | €3,840.33 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 4 (1 Z3) | 1->1 | 0->0 | 140/140 | 3 | 0 | €3,634.33 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 144/144 | 2 | 0 | €3,642.03 |
| 3 | fragile_promo | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 170/170 | 3 | 0 | €4,507.23 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 132/132 | 5 | 0 | €3,733.03 |
| 5 | pre_peak_prep | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 131/131 | 4 | 0 | €3,630.33 |
| 6 | early_holiday | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 138/138 | 0 | 0 | €3,628.43 |
| 7 | singles_day_wave | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 191/191 | 2 | 0 | €4,530.23 |
| 8 | black_friday_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 202/202 | 1 | 39 | €4,898.88 |
| 9 | cyber_week_peak | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 183/183 | 4 | 0 | €4,428.93 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 120/120 | 2 | 0 | €3,722.23 |
| 11 | quarter_close | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 152/152 | 4 | 0 | €3,645.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (9 jam(s), 9 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 25 late delivery(ies); 39 overtime tick(s).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
