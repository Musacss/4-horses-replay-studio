# Quarterly Rollout Operational Diagnostics (Seed 47)

**Summary:** Quarter seed 47 [INFEASIBLE]: 33 operational issue(s) (27 critical, 6 warning) across 12/12 week(s); operating cost €162,179.06, CapEx €15,300.00, peak wear 12.

## Quarter Totals & Category Counts

- **CapEx Purchase:** €15,300.00
- **Total Operating Cost:** €162,179.06
- **Active Labor Ticks:** 26917
- **Peak Equipment Wear:** 12
- **Peak Backlog Carryover Out:** 80
- **Total Robot Jams:** 605
- **Total Overtime Ticks:** 5262
- **Hiring & Retraining Friction Cost:** €110.00
- **Evaluation Failure Reasons:** completed good-order volume below SLA threshold, pooled on-time delivery rate below SLA threshold, escaped defect rate exceeds SLA maximum

| Mistake Category | Key | Issues Flagged |
|---|---|---:|
| Commissioning Jam / Unassisted Robot | `commissioning_jam_unassisted` | 0 |
| Route='all' / Unmaintained Wear Buildup | `route_all_unmaintained_wear` | 12 |
| Hiring / Retraining Crew Friction | `hiring_retraining_friction` | 1 |
| SLA / Overtime / Defect Breach | `sla_overtime_breach` | 11 |
| Backlog Carryover Surge | `backlog_carryover_surge` | 9 |

## Week-by-Week Telemetry (12 Weeks, 33 Issue(s): 27 Critical, 6 Warning)

| Week | Label | Status | Route / Maint | Crew (Z3) | Wear | Carry In->Out | Good / Total | Jams | Overtime | Week Cost |
|---:|---|---|---|---|---|---:|---:|---:|---:|---:|
| 0 | baseline_open | WARNING | all (comm) | 5 (2 Z3) | 0->3 | 0->0 | 131/131 | 18 | 0 | €4,414.43 |
| 1 | baseline_steady | WARNING | all (comm) | 5 (2 Z3) | 3->6 | 0->0 | 140/140 | 21 | 0 | €4,709.23 |
| 2 | autumn_ramp | CRITICAL | all | 5 (2 Z3) | 6->9 | 0->0 | 144/144 | 42 | 61 | €5,445.08 |
| 3 | fragile_promo | CRITICAL | all | 5 (2 Z3) | 9->12 | 0->58 | 109/170 | 49 | 582 | €7,689.33 |
| 4 | mid_quarter | CRITICAL | all | 5 (2 Z3) | 12->12 | 58->80 | 100/190 | 57 | 580 | €9,045.73 |
| 5 | pre_peak_prep | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 124/211 | 64 | 588 | €8,965.03 |
| 6 | early_holiday | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 106/218 | 66 | 552 | €13,121.23 |
| 7 | singles_day_wave | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 101/271 | 55 | 571 | €23,214.58 |
| 8 | black_friday_peak | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 99/282 | 55 | 565 | €25,116.88 |
| 9 | cyber_week_peak | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 89/263 | 58 | 594 | €23,552.73 |
| 10 | post_peak_steady | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->80 | 101/200 | 59 | 597 | €10,650.68 |
| 11 | quarter_close | CRITICAL | all | 5 (2 Z3) | 12->12 | 80->0 | 125/232 | 61 | 572 | €26,254.13 |

## Detailed Weekly Operational Findings

### Week 00 (`baseline_open`) — WARNING
- **[WARNING] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 0 to 3 (delta +3).
- **[WARNING] `hiring_retraining_friction`**: Crew roster changed (5 -> 5 worker(s)), incurring €110.00 in hiring/retraining friction.

### Week 01 (`baseline_steady`) — WARNING
- **[WARNING] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 3 to 6 (delta +3).
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 23 late delivery(ies).

### Week 02 (`autumn_ramp`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 6 to 9 (delta +3).
- **[WARNING] `sla_overtime_breach`**: SLA/overtime pressure: 64 late delivery(ies); 61 overtime tick(s).

### Week 03 (`fragile_promo`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 9 to 12 (delta +3).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 64.11% (109/170) below 90.00% weekly floor; escaped rate 1.76% (3/170) above 1.20% weekly cap; 80 late delivery(ies); 582 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=0, carryover_out=58 (shift unfinished=58).

### Week 04 (`mid_quarter`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 52.63% (100/190) below 90.00% weekly floor; 1 escaped defect(s); 100 late delivery(ies); 580 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=58, carryover_out=80 (hit carryover_cap) (shift unfinished=89).

### Week 05 (`pre_peak_prep`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 58.76% (124/211) below 90.00% weekly floor; 1 escaped defect(s); 124 late delivery(ies); 588 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=86).

### Week 06 (`early_holiday`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 48.62% (106/218) below 90.00% weekly floor; 2 escaped defect(s); 106 late delivery(ies); 552 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=110).

### Week 07 (`singles_day_wave`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 37.26% (101/271) below 90.00% weekly floor; 2 escaped defect(s); 101 late delivery(ies); 571 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=168).

### Week 08 (`black_friday_peak`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 35.10% (99/282) below 90.00% weekly floor; 99 late delivery(ies); 565 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=183).

### Week 09 (`cyber_week_peak`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 33.84% (89/263) below 90.00% weekly floor; 1 escaped defect(s); 89 late delivery(ies); 594 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=173).

### Week 10 (`post_peak_steady`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 50.50% (101/200) below 90.00% weekly floor; 1 escaped defect(s); 101 late delivery(ies); 597 overtime tick(s).
- **[CRITICAL] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=80 (hit carryover_cap) (shift unfinished=98).

### Week 11 (`quarter_close`) — CRITICAL
- **[CRITICAL] `route_all_unmaintained_wear`**: Robot ran route='all' without preventive maintenance while wear rose from 12 to 12 (delta +0).
- **[CRITICAL] `sla_overtime_breach`**: SLA/overtime pressure: good rate 53.87% (125/232) below 90.00% weekly floor; escaped rate 1.29% (3/232) above 1.20% weekly cap; 125 late delivery(ies); 572 overtime tick(s); 104 terminal unfulfilled order(s) at quarter end.
- **[WARNING] `backlog_carryover_surge`**: Backlog carryover_in=80, carryover_out=0 (shift unfinished=104).
