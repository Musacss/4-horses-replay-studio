# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [WIN]: 9 operational issue(s) (0 critical, 9 warning) across 7/12 week(s); operating cost €48,361.86, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €48,361.86
- **Active Labor Ticks:** 32845
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 39
- **Total Overtime Ticks:** 6
- **Hiring & Retraining Friction Cost:** €925.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 7 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 2 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 9 Issue(s): 0 Critical, 9 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (2 Z3) | 0->1 | 0->0 | 131/131 | 9 | 0 | €3,840.33 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 4 (2 Z3) | 1->1 | 0->0 | 140/140 | 3 | 0 | €3,634.33 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (2 Z3) | 1->1 | 0->0 | 144/144 | 2 | 0 | €3,642.03 |
| 3 | fragile_promo | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 170/170 | 3 | 0 | €4,462.23 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (2 Z3) | 1->1 | 0->0 | 132/132 | 5 | 0 | €3,768.03 |
| 5 | pre_peak_prep | OK | bypass + maint | 4 (2 Z3) | 1->1 | 0->0 | 131/131 | 4 | 0 | €3,630.33 |
| 6 | early_holiday | OK | bypass + maint | 4 (2 Z3) | 1->1 | 0->0 | 138/138 | 0 | 0 | €3,628.43 |
| 7 | singles_day_wave | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 191/191 | 2 | 6 | €4,588.73 |
| 8 | black_friday_peak | WARNING | bypass + maint | 6 (3 Z3) | 1->1 | 0->0 | 202/202 | 1 | 0 | €5,255.13 |
| 9 | cyber_week_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 183/183 | 4 | 0 | €4,509.93 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (2 Z3) | 1->1 | 0->0 | 120/120 | 2 | 0 | €3,757.23 |
| 11 | quarter_close | OK | bypass + maint | 4 (2 Z3) | 1->1 | 0->0 | 152/152 | 4 | 0 | €3,645.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €145.00 in hiring/retraining friction.

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 6 late delivery(ies); 6 overtime tick(s).

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 6 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (6 -> 5 worker(s)), incurring €110.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €145.00 in hiring/retraining friction.
