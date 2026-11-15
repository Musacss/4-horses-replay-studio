# Quarterly Rollout Operational Diagnostics (Seed 11)

**Summary:** Quarter seed 11 [WIN]: 6 operational issue(s) (1 critical, 5 warning) across 6/12 week(s); operating cost €47,409.86, CapEx €15,300.00, peak wear 2.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €47,409.86
- **Active Labor Ticks:** 33149
- **Peak Equipment Wear:** 2
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 57
- **Total Overtime Ticks:** 62
- **Hiring & Retraining Friction Cost:** €455.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 3 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 3 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 6 Issue(s): 1 Critical, 5 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (2 Z3) | 0->1 | 0->0 | 140/140 | 12 | 0 | €3,848.43 |
| 1 | baseline_steady | OK | bypass (comm) | 4 (2 Z3) | 1->2 | 0->0 | 133/133 | 10 | 0 | €3,591.23 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 134/134 | 2 | 0 | €3,628.93 |
| 3 | fragile_promo | WARNING | bypass | 4 (2 Z3) | 1->2 | 0->0 | 169/169 | 5 | 0 | €4,035.53 |
| 4 | mid_quarter | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 129/129 | 1 | 0 | €3,640.83 |
| 5 | pre_peak_prep | OK | bypass | 4 (2 Z3) | 1->2 | 0->0 | 115/115 | 7 | 0 | €3,566.83 |
| 6 | early_holiday | CRITICAL | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 144/145 | 3 | 0 | €3,959.73 |
| 7 | singles_day_wave | WARNING | bypass | 5 (3 Z3) | 1->2 | 0->0 | 176/176 | 7 | 0 | €4,524.93 |
| 8 | black_friday_peak | WARNING | bypass + maint | 5 (3 Z3) | 2->1 | 0->0 | 197/197 | 2 | 62 | €4,860.23 |
| 9 | cyber_week_peak | OK | bypass | 5 (3 Z3) | 1->2 | 0->0 | 175/175 | 2 | 0 | €4,421.73 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 134/134 | 0 | 0 | €3,738.93 |
| 11 | quarter_close | OK | bypass | 4 (2 Z3) | 1->2 | 0->0 | 139/139 | 6 | 0 | €3,592.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 26 late delivery(ies).

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 18 late delivery(ies); 62 overtime tick(s).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
