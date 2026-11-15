# Quarterly Rollout Operational Diagnostics (Seed 11)

**Summary:** Quarter seed 11 [INFEASIBLE]: 34 operational issue(s) (28 critical, 6 warning) across 12/12 week(s); operating cost €152,673.16, CapEx €15,300.00, peak wear 12.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €152,673.16
- **Active Labor Ticks:** 26958
- **Peak Equipment Wear:** 12
- **Peak Backlog Carryover Out:** 80
- **Total Robot Jams:** 616
- **Total Overtime Ticks:** 5202
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
| 0 | baseline_open | WARNING | all (comm) | 5 (2 Z3) | 0->3 | 0->0 | 140/140 | 19 | 0 | €5,122.83 |
| 1 | baseline_steady | WARNING | all (comm) | 5 (2 Z3) | 3->6 | 0->0 | 133/133 | 32 | 0 | €5,027.03 |
| 2 | autumn_ramp | CRITICAL | all | 5 (2 Z3) | 6->9 | 0->0 | 133/134 | 42 | 91 | €5,978.28 |
| 3 | fragile_promo | CRITICAL | all | 5 (2 Z3) | 9->12 | 0->56 | 113/169 | 53 | 573 | €6,871.68 |
| 4 | mid_quarter | CRITICAL | all | 5 (2 Z3) | 12->12 | 56->67 | 117/185 | 58 | 556 | €7,649.13 |
| 5 | pre_peak_prep | CRITICAL | all | 5 (2 Z3) | 12->12 | 67->71 | 108/182 | 66 | 541 | €7,983.58 |
| 6 | early_holiday | CRITICAL | all | 5 (2 Z3) | 12->12 | 71->80 | 117/216 | 63 | 563 | €11,024.48 |
| 7 | singles_day_wave | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 105/256 | 54 | 577 | €19,662.88 |
| 8 | black_friday_peak | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 92/277 | 55 | 568 | €25,386.03 |
| 9 | cyber_week_peak | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 94/255 | 56 | 563 | €21,183.98 |
| 10 | post_peak_steady | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 107/214 | 55 | 585 | €12,148.48 |
| 11 | quarter_close | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->0 | 118/219 | 63 | 585 | €24,634.78 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 0 to 3 (delta +3).
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 5 worker(s)), incurring €110.00 in hiring/retraining friction.
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 43 late delivery(ies).

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 3 to 6 (delta +3).
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 43 late delivery(ies).

### Week 02 (`autumn_ramp`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 6 to 9 (delta +3).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: 1 escaped defect(s); 76 late delivery(ies); 91 overtime tick(s).

### Week 03 (`fragile_promo`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 9 to 12 (delta +3).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 66.86% (113/169) below 90.00% weekly floor; 92 late delivery(ies); 573 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=0, carryover_out=56 (shift unfinished=56).

### Week 04 (`mid_quarter`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 63.24% (117/185) below 90.00% weekly floor; 1 escaped defect(s); 117 late delivery(ies); 556 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=56, carryover_out=67 (shift unfinished=67).

### Week 05 (`pre_peak_prep`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 59.34% (108/182) below 90.00% weekly floor; 2 escaped defect(s); 1 scrapped order(s); 108 late delivery(ies); 541 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=67, carryover_out=71 (shift unfinished=71).

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 54.16% (117/216) below 90.00% weekly floor; 2 escaped defect(s); 117 late delivery(ies); 563 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=71, carryover_out=80 (hit carryover_cap) (shift unfinished=97).

### Week 07 (`singles_day_wave`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 41.01% (105/256) below 90.00% weekly floor; 1 scrapped order(s); 105 late delivery(ies); 577 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=150).

### Week 08 (`black_friday_peak`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 33.21% (92/277) below 90.00% weekly floor; 92 late delivery(ies); 568 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=185).

### Week 09 (`cyber_week_peak`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 36.86% (94/255) below 90.00% weekly floor; 94 late delivery(ies); 563 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=161).

### Week 10 (`post_peak_steady`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 50.00% (107/214) below 90.00% weekly floor; 1 escaped defect(s); 107 late delivery(ies); 585 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=106).

### Week 11 (`quarter_close`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 53.88% (118/219) below 90.00% weekly floor; 1 scrapped order(s); 118 late delivery(ies); 585 overtime tick(s); 100 terminal unfulfilled order(s) at quarter end.
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=0 (shift unfinished=100).
