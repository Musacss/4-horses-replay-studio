# Quarterly Rollout Operational Diagnostics (Seed 11)

**Summary:** Quarter seed 11 [WIN]: 13 operational issue(s) (1 critical, 12 warning) across 9/12 week(s); operating cost €48,722.86, CapEx €15,300.00, peak wear 4.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €48,722.86
- **Active Labor Ticks:** 32545
- **Peak Equipment Wear:** 4
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 73
- **Total Overtime Ticks:** 420
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
| 0 | baseline_open | WARNING | bypass (comm) | 4 (1 Z3) | 0->1 | 0->0 | 140/140 | 12 | 0 | €3,848.43 |
| 1 | baseline_steady | WARNING | bypass (comm) | 4 (1 Z3) | 1->2 | 0->0 | 133/133 | 10 | 0 | €3,546.23 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 134/134 | 2 | 0 | €3,583.93 |
| 3 | fragile_promo | WARNING | bypass | 5 (2 Z3) | 1->2 | 0->0 | 169/169 | 5 | 0 | €4,424.53 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 129/129 | 1 | 0 | €3,817.83 |
| 5 | pre_peak_prep | OK | bypass | 4 (1 Z3) | 1->2 | 0->0 | 115/115 | 7 | 0 | €3,521.83 |
| 6 | early_holiday | CRITICAL | bypass + maint | 4 (1 Z3) | 2->1 | 0->0 | 144/145 | 3 | 0 | €3,994.73 |
| 7 | singles_day_wave | WARNING | bypass | 5 (2 Z3) | 1->2 | 0->0 | 176/176 | 7 | 47 | €4,621.68 |
| 8 | black_friday_peak | WARNING | bypass | 5 (2 Z3) | 2->3 | 0->0 | 197/197 | 6 | 373 | €5,762.18 |
| 9 | cyber_week_peak | WARNING | bypass | 5 (2 Z3) | 3->4 | 0->0 | 175/175 | 14 | 0 | €4,360.03 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (1 Z3) | 4->1 | 0->0 | 134/134 | 0 | 0 | €3,693.93 |
| 11 | quarter_close | OK | bypass | 4 (1 Z3) | 1->2 | 0->0 | 139/139 | 6 | 0 | €3,547.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (12 jam(s), 12 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €220.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 5 late delivery(ies).

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (10 jam(s), 10 assist(s)) with only 1 Zone-3 worker(s) assigned.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 7 late delivery(ies).

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s); 5 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 8 late delivery(ies); 47 overtime tick(s).

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 58 late delivery(ies); 373 overtime tick(s).

### Week 09 (`cyber_week_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 1 late delivery(ies).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
