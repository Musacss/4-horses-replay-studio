# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [WIN]: 13 operational issue(s) (1 critical, 12 warning) across 10/12 week(s); operating cost €50,142.71, CapEx €15,300.00, peak wear 4.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €50,142.71
- **Active Labor Ticks:** 33053
- **Peak Equipment Wear:** 4
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 85
- **Total Overtime Ticks:** 539
- **Hiring & Retraining Friction Cost:** €620.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 2 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 5 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 6 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 13 Issue(s): 1 Critical, 12 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (1 Z3) | 0->1 | 0->0 | 131/131 | 9 | 0 | €3,760.33 |
| 1 | baseline_steady | WARNING | bypass (comm) | 4 (1 Z3) | 1->2 | 0->0 | 140/140 | 7 | 0 | €3,584.53 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 144/144 | 2 | 0 | €3,597.03 |
| 3 | fragile_promo | WARNING | bypass | 5 (2 Z3) | 1->2 | 0->0 | 170/170 | 6 | 0 | €4,437.73 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 132/132 | 5 | 0 | €3,688.03 |
| 5 | pre_peak_prep | WARNING | bypass | 4 (1 Z3) | 1->2 | 0->0 | 131/131 | 7 | 0 | €3,564.53 |
| 6 | early_holiday | WARNING | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 138/138 | 0 | 0 | €3,599.43 |
| 7 | singles_day_wave | WARNING | bypass | 5 (2 Z3) | 1->2 | 0->0 | 191/191 | 7 | 59 | €4,721.98 |
| 8 | black_friday_peak | CRITICAL | bypass | 5 (2 Z3) | 2->3 | 0->0 | 201/202 | 12 | 419 | €7,141.18 |
| 9 | cyber_week_peak | WARNING | bypass | 5 (2 Z3) | 3->4 | 0->0 | 183/183 | 17 | 61 | €4,815.58 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (1 Z3) | 4->1 | 0->0 | 120/120 | 2 | 0 | €3,677.23 |
| 11 | quarter_close | OK | bypass | 4 (1 Z3) | 1->2 | 0->0 | 152/152 | 11 | 0 | €3,555.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (9 jam(s), 9 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €220.00 in hiring/retraining friction.

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (7 jam(s), 7 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 2 late delivery(ies).

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 05 (`pre_peak_prep`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).

### Week 06 (`early_holiday`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 13 late delivery(ies); 59 overtime tick(s).

### Week 08 (`black_friday_peak`) — CRITICAL
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s); 120 late delivery(ies); 419 overtime tick(s).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 24 late delivery(ies); 61 overtime tick(s).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
