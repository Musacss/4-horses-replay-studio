# Quarterly Rollout Operational Diagnostics (Seed 11)

**Summary:** Quarter seed 11 [WIN]: 10 operational issue(s) (1 critical, 9 warning) across 8/12 week(s); operating cost €48,284.26, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €48,284.26
- **Active Labor Ticks:** 32855
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 42
- **Total Overtime Ticks:** 110
- **Hiring & Retraining Friction Cost:** €655.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 2 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 5 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 3 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 10 Issue(s): 1 Critical, 9 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (1 Z3) | 0->1 | 0->0 | 140/140 | 12 | 0 | €3,848.43 |
| 1 | baseline_steady | WARNING | bypass + maint (comm) | 4 (1 Z3) | 1->1 | 0->0 | 133/133 | 9 | 0 | €3,632.13 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 134/134 | 2 | 0 | €3,628.93 |
| 3 | fragile_promo | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 169/169 | 2 | 0 | €4,510.43 |
| 4 | mid_quarter | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 129/129 | 1 | 0 | €3,798.83 |
| 5 | pre_peak_prep | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 115/115 | 3 | 0 | €3,607.73 |
| 6 | early_holiday | CRITICAL | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 144/145 | 3 | 0 | €3,975.73 |
| 7 | singles_day_wave | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 176/176 | 4 | 0 | €4,516.73 |
| 8 | black_friday_peak | WARNING | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 197/197 | 2 | 110 | €4,971.23 |
| 9 | cyber_week_peak | OK | bypass + maint | 5 (2 Z3) | 1->1 | 0->0 | 175/175 | 0 | 0 | €4,421.73 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 134/134 | 0 | 0 | €3,738.93 |
| 11 | quarter_close | OK | bypass + maint | 4 (1 Z3) | 1->1 | 0->0 | 139/139 | 4 | 0 | €3,633.43 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (12 jam(s), 12 assist(s)) with only 1 Zone-3 worker(s) assigned.
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `commissioning_jam_unassisted`**: Commissioning jam spike (9 jam(s), 9 assist(s)) with only 1 Zone-3 worker(s) assigned.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 04 (`mid_quarter`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 3 late delivery(ies).

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s); 1 late delivery(ies).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 08 (`black_friday_peak`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 24 late delivery(ies); 110 overtime tick(s).

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
