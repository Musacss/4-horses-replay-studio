# Quarterly Rollout Operational Diagnostics (Seed 29)

**Summary:** Quarter seed 29 [INFEASIBLE]: 34 operational issue(s) (28 critical, 6 warning) across 12/12 week(s); operating cost €157,792.96, CapEx €15,300.00, peak wear 12.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €157,792.96
- **Active Labor Ticks:** 26826
- **Peak Equipment Wear:** 12
- **Peak Backlog Carryover Out:** 80
- **Total Robot Jams:** 617
- **Total Overtime Ticks:** 5276
- **Hiring & Retraining Friction Cost:** €110.00
- **Evaluation Failure Reasons:** completed good-order volume below SLA threshold, pooled on-time delivery rate below SLA threshold, escaped defect rate exceeds SLA maximum

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 12 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 1 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 12 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 9 |

## Week-by-Week Telemetry (12 Weeks, 34 Issue(s): 28 Critical, 6 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | all (comm) | 5 (2 Z3) | 0->3 | 0->0 | 134/134 | 21 | 0 | €4,533.23 |
| 1 | baseline_steady | WARNING | all (comm) | 5 (2 Z3) | 3->6 | 0->0 | 132/132 | 29 | 0 | €4,877.63 |
| 2 | autumn_ramp | CRITICAL | all | 5 (2 Z3) | 6->9 | 0->0 | 136/139 | 38 | 22 | €6,386.93 |
| 3 | fragile_promo | CRITICAL | all | 5 (2 Z3) | 9->12 | 0->58 | 108/167 | 54 | 600 | €7,060.53 |
| 4 | mid_quarter | CRITICAL | all | 5 (2 Z3) | 12->12 | 58->80 | 102/188 | 58 | 581 | €8,543.98 |
| 5 | pre_peak_prep | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->78 | 114/194 | 62 | 560 | €7,824.83 |
| 6 | early_holiday | CRITICAL | all | 5 (2 Z3) | 12->12 | 78->80 | 122/219 | 62 | 584 | €10,512.13 |
| 7 | singles_day_wave | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 100/271 | 54 | 590 | €23,530.93 |
| 8 | black_friday_peak | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 98/272 | 57 | 596 | €23,869.63 |
| 9 | cyber_week_peak | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 102/269 | 55 | 587 | €22,419.68 |
| 10 | post_peak_steady | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 94/206 | 60 | 600 | €12,689.83 |
| 11 | quarter_close | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->0 | 113/218 | 67 | 556 | €25,543.63 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 0 to 3 (delta +3).
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 5 worker(s)), incurring €110.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 7 late delivery(ies).

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 3 to 6 (delta +3).
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 35 late delivery(ies).

### Week 02 (`autumn_ramp`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 6 to 9 (delta +3).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: escaped rate 2.15% (3/139) above 1.20% weekly cap; 65 late delivery(ies); 22 overtime tick(s).

### Week 03 (`fragile_promo`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 9 to 12 (delta +3).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 64.67% (108/167) below 90.00% weekly floor; 1 escaped defect(s); 81 late delivery(ies); 600 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=0, carryover_out=58 (shift unfinished=58).

### Week 04 (`mid_quarter`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 54.25% (102/188) below 90.00% weekly floor; 2 escaped defect(s); 102 late delivery(ies); 581 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=58, carryover_out=80 (hit carryover_cap) (shift unfinished=84).

### Week 05 (`pre_peak_prep`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 58.76% (114/194) below 90.00% weekly floor; 1 escaped defect(s); 1 scrapped order(s); 114 late delivery(ies); 560 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=78 (shift unfinished=78).

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 55.70% (122/219) below 90.00% weekly floor; 122 late delivery(ies); 584 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=78, carryover_out=80 (hit carryover_cap) (shift unfinished=97).

### Week 07 (`singles_day_wave`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 36.90% (100/271) below 90.00% weekly floor; 3 escaped defect(s); 100 late delivery(ies); 590 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=168).

### Week 08 (`black_friday_peak`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 36.02% (98/272) below 90.00% weekly floor; 2 escaped defect(s); 98 late delivery(ies); 596 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=172).

### Week 09 (`cyber_week_peak`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 37.91% (102/269) below 90.00% weekly floor; 102 late delivery(ies); 587 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=167).

### Week 10 (`post_peak_steady`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 45.63% (94/206) below 90.00% weekly floor; 94 late delivery(ies); 600 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=112).

### Week 11 (`quarter_close`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 51.83% (113/218) below 90.00% weekly floor; 2 escaped defect(s); 113 late delivery(ies); 556 overtime tick(s); 103 terminal unfulfilled order(s) at quarter end.
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=0 (shift unfinished=103).
