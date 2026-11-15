# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [WIN]: 4 operational issue(s) (0 critical, 4 warning) across 4/12 week(s); operating cost €47,372.41, CapEx €15,300.00, peak wear 2.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €47,372.41
- **Active Labor Ticks:** 32330
- **Peak Equipment Wear:** 2
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 62
- **Total Overtime Ticks:** 9
- **Hiring & Retraining Friction Cost:** €455.00

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 3 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 1 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 4 Issue(s): 0 Critical, 4 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass (comm) | 4 (2 Z3) | 0->1 | 0->0 | 134/134 | 12 | 0 | €3,847.13 |
| 1 | baseline_steady | OK | bypass (comm) | 4 (2 Z3) | 1->2 | 0->0 | 132/132 | 9 | 0 | €3,582.13 |
| 2 | autumn_ramp | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 139/139 | 4 | 0 | €3,629.33 |
| 3 | fragile_promo | WARNING | bypass | 4 (2 Z3) | 1->2 | 0->0 | 167/167 | 7 | 9 | €4,700.98 |
| 4 | mid_quarter | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 130/130 | 1 | 0 | €3,625.33 |
| 5 | pre_peak_prep | OK | bypass | 4 (2 Z3) | 1->2 | 0->0 | 114/114 | 4 | 0 | €3,565.93 |
| 6 | early_holiday | OK | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 141/141 | 1 | 0 | €3,651.63 |
| 7 | singles_day_wave | WARNING | bypass | 5 (3 Z3) | 1->2 | 0->0 | 191/191 | 4 | 0 | €4,526.13 |
| 8 | black_friday_peak | OK | bypass + maint | 5 (3 Z3) | 2->1 | 0->0 | 192/192 | 5 | 0 | €4,482.03 |
| 9 | cyber_week_peak | OK | bypass | 5 (3 Z3) | 1->2 | 0->0 | 189/189 | 5 | 0 | €4,438.43 |
| 10 | post_peak_steady | WARNING | bypass + maint | 4 (2 Z3) | 2->1 | 0->0 | 126/126 | 3 | 0 | €3,735.83 |
| 11 | quarter_close | OK | bypass | 4 (2 Z3) | 1->2 | 0->0 | 138/138 | 7 | 0 | €3,587.53 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 4 worker(s)), incurring €255.00 in hiring/retraining friction.

### Week 03 (`fragile_promo`) — WARNING
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 67 late delivery(ies); 9 overtime tick(s).

### Week 07 (`singles_day_wave`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (4 -> 5 worker(s)), incurring €90.00 in hiring/retraining friction.

### Week 10 (`post_peak_steady`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 4 worker(s)), incurring €110.00 in hiring/retraining friction.
