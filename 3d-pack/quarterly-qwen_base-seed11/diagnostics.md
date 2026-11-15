# Quarterly Rollout Operational Diagnostics (Seed 11)

**Summary:** Quarter seed 11 [FEASIBLE (NO WIN)]: 2 operational issue(s) (1 critical, 1 warning) across 2/12 week(s); operating cost €84,123.76, CapEx €15,300.00, peak wear 1.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €84,123.76
- **Active Labor Ticks:** 35651
- **Peak Equipment Wear:** 1
- **Peak Backlog Carryover Out:** 0
- **Total Robot Jams:** 42
- **Total Overtime Ticks:** 0
- **Hiring & Retraining Friction Cost:** €355.00
- **Evaluation Failure Reasons:** operating cost did not beat manual baseline

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 0 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 1 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 1 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 0 |

## Week-by-Week Telemetry (12 Weeks, 2 Issue(s): 1 Critical, 1 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | bypass + maint (comm) | 8 (4 Z3) | 0->1 | 0->0 | 140/140 | 12 | 0 | €7,303.43 |
| 1 | baseline_steady | OK | bypass + maint (comm) | 8 (4 Z3) | 1->1 | 0->0 | 133/133 | 9 | 0 | €6,942.13 |
| 2 | autumn_ramp | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 134/134 | 2 | 0 | €6,938.93 |
| 3 | fragile_promo | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 169/169 | 2 | 0 | €6,970.43 |
| 4 | mid_quarter | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 129/129 | 1 | 0 | €6,950.83 |
| 5 | pre_peak_prep | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 115/115 | 3 | 0 | €6,917.73 |
| 6 | early_holiday | CRITICAL | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 144/145 | 3 | 0 | €7,269.73 |
| 7 | singles_day_wave | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 176/176 | 4 | 0 | €6,976.73 |
| 8 | black_friday_peak | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 197/197 | 2 | 0 | €6,999.73 |
| 9 | cyber_week_peak | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 175/175 | 0 | 0 | €6,971.73 |
| 10 | post_peak_steady | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 134/134 | 0 | 0 | €6,938.93 |
| 11 | quarter_close | OK | bypass + maint | 8 (4 Z3) | 1->1 | 0->0 | 139/139 | 4 | 0 | €6,943.43 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (8 -> 8 worker(s)), incurring €355.00 in hiring/retraining friction.

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s).
