# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [WIN]: 9 operational issue(s) (0 critical, 9 warning) across 8/12 week(s); operating cost €47,423.96, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €47,423.96
- **Active Labor Ticks:** 32136
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 46
- **Total Overtime Ticks:** 0
- **Hiring & Retraining Friction Cost:** €655.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 2 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 5 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 2 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 9 Issue(s): 0 Critical, 9 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (1 Z3) | 0->1 | 0->0 | 134/134 | 12 | 0 | €3,847.13 |
| 1 | baseline_steady | WARNING | bypass + maint (comm) | 4 (1 Z3) | 1->1 | 0->0 | 132/132 | 7 | 0 | €3,623.03 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 139/139 | 4 | 0 | €3,629.33 |
| 3 | fragile_promo | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 167/167 | 4 | 0 | €4,512.73 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 130/130 | 1 | 0 | €3,735.33 |
| 5 | pre_peak_prep | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 114/114 | 2 | 0 | €3,606.83 |
| 6 | early_holiday | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 141/141 | 1 | 0 | €3,683.63 |
| 7 | singles_day_wave | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 191/191 | 2 | 0 | €4,526.13 |
| 8 | black_friday_peak | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 192/192 | 5 | 0 | €4,437.03 |
| 9 | cyber_week_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 189/189 | 2 | 0 | €4,454.43 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 126/126 | 3 | 0 | €3,735.83 |
| 11 | quarter_close | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 138/138 | 3 | 0 | €3,632.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (12 jam(s), 12 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (7 jam(s), 7 assist(s)) with only 1 Zone-3 worker(s) assigned.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 06 (`early_holiday`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 2 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
