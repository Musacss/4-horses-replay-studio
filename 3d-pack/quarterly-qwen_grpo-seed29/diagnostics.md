# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [WIN]: 10 operational issue(s) (0 critical, 10 warning) across 9/12 week(s); operating cost €47,357.56, CapEx €15,300.00, peak wear 4.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €47,357.56
- **Active Labor Ticks:** 31806
- **Peak Equipment Wear:** 4
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 77
- **Total Overtime Ticks:** 204
- **Hiring & Retraining Friction Cost:** €620.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 2 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 5 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 3 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 10 Issue(s): 0 Critical, 10 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (1 Z3) | 0->1 | 0->0 | 134/134 | 12 | 0 | €3,767.13 |
| 1 | baseline_steady | WARNING | bypass (comm) | 4 (1 Z3) | 1->2 | 0->0 | 132/132 | 9 | 0 | €3,537.13 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 139/139 | 4 | 0 | €3,584.33 |
| 3 | fragile_promo | WARNING | bypass | 5 (2 Z3) | 1->2 | 0->0 | 167/167 | 7 | 0 | €4,422.73 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 130/130 | 1 | 0 | €3,690.33 |
| 5 | pre_peak_prep | OK | bypass | 4 (1 Z3) | 1->2 | 0->0 | 114/114 | 4 | 0 | €3,520.93 |
| 6 | early_holiday | WARNING | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 141/141 | 1 | 0 | €3,638.63 |
| 7 | singles_day_wave | WARNING | bypass | 5 (2 Z3) | 1->2 | 0->0 | 191/191 | 4 | 0 | €4,436.13 |
| 8 | black_friday_peak | WARNING | bypass | 5 (2 Z3) | 2->3 | 0->0 | 192/192 | 13 | 41 | €4,638.28 |
| 9 | cyber_week_peak | WARNING | bypass | 5 (2 Z3) | 3->4 | 0->0 | 189/189 | 12 | 163 | €4,888.58 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (1 Z3) | 4->1 | 0->0 | 126/126 | 3 | 0 | €3,690.83 |
| 11 | quarter_close | OK | bypass | 4 (1 Z3) | 1->2 | 0->0 | 138/138 | 7 | 0 | €3,542.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (12 jam(s), 12 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €220.00 in hiring/retraining friction.

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (9 jam(s), 9 assist(s)) with only 1 Zone-3 worker(s) assigned.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 06 (`early_holiday`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 2 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 15 late delivery(ies); 41 overtime tick(s).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 20 late delivery(ies); 163 overtime tick(s).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
