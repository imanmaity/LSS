# Inventory Management (Parahouse Warehousing): analysis summary

Flow followed: Pre-DMAIC → Define → Measure → Analyze → Improve → Control (toolkit grid from Book1.xlsx, Sheet4).
Reference photo: not in the upload; the Sheet4 grid was used as the scope checklist. Book1 Sheet1/Sheet2/RACI (hospital OPD and school examples) belong to other projects and were not used.

## 1. Verified baseline KPIs (Apr 1 – May 31, 2021, 61 days)
| Metric | Numerator | Denominator | Rate |
|---|---|---|---|
| Picking error rate | 243 | 13,039 sampled items | 1.864% |
| Damage rate | 299 | 13,039 sampled items | 2.293% |
| Inventory variance rate | 315 units | 29,740 actual units | 1.059% (accuracy 98.94%) |
| Days with mismatch | 57 | 61 days | 93.4% |

Sigma (short-term, 1.5 shift): picking 3.58, damage 3.50, inventory units 3.80, mismatch days ≈ 0.

## 2. Verified Pareto results
- Picking (243): manual errors 102 (42.0%) + poor labels 85 (35.0%) = 77.0%; + pick lists 17 = 84.0%.
- Damage (299): handling training 119 (39.8%), stacking 74 (24.7%), no fragile SOP 42 (14.0%) = 78.6% (top three).
- Mismatch (315 variance units, not days): receiving errors 98 (31.1%), duplicate SKUs 76 (24.1%), cycle counts 64 (20.3%) = 75.6% (top three).
- All three totals tie to the Measure sheet (243 / 299 / 315).

## 3. Major findings
- Damage rose April to May 2021 (1.80% to 2.92%, p < 0.001); picking flat (p = 0.74).
- Damage rate is higher on low-volume days (rho = −0.40): "rushed operations" is not supported (4 cases).
- Actual > SAP on all 62 mismatch days: SAP systematically under-records.
- Process: 74 min cycle; 60.8% NVA; packing-station wait 17 min, near takt (17.8 min at 700 orders/month, 26 days).
- Fishbone: People, Method, Information = 76% of 857 recorded cause occurrences.
- Priority: damage and inventory accuracy first; picking relabelling as quick win; picking is the largest residual after.

## 4. Before / after (Improve period Oct 1 – Nov 30, 2025, 61 days, 15,365 items)
| Metric | Baseline | Improve | Change | Relative |
|---|---|---|---|---|
| Picking rate | 1.86% (243) | 0.10% (16) | −1.76 pp | −94.4% |
| Damage rate | 2.29% (299) | 0.04% (6) | −2.25 pp | −98.3% |
| Inventory variance rate | 1.06% (315 units) | 0.06% (21 units) | −1.00 pp | −94.7% |
| Mismatch days | 57 | 5 | −52 | −91.2% |

Two-proportion z-tests: all p < 0.0001. Sigma now: picking 4.58, damage 4.86, inventory 4.76, mismatch days 2.89.
Illustrative cost at the case's unit losses ($330 / $800 / $1,100): $382,090–$665,890 baseline vs $15,580–$33,180 improve per 61 days (scenario, not audited).

## 5. Main limitations
- Periods are 4+ years apart (different months, volumes, unknown process changes); no log of implemented solutions; causation not established.
- Rates are per sampled item; case costs are per order (700 orders a month vs ~6,400 sampled items a month).
- Picking errors track sample size (r = 0.96): check how they were recorded.
- No repeat measurements: GRR / attribute agreement study not possible.
- No operator, shift, SKU, training or cost-actual data.
- Improve period has few events (6–21), so sigma estimates are imprecise.

## 6. Recommended actions
Relabel bins; scan-to-confirm at pick; handling training and sign-off; stacking standard and fragile SOP; blind receiving; SKU master clean-up and scheduled cycle counts; dashboard with triggers (see deck, Control section); pilot-versus-control validation.

## 7. Slide sequence (41 slides)
1 Title · 2 Executive summary · 3 Coverage map · **Pre-DMAIC** 4 VOC/VOB, 5 CTQ, 6 As-Is Y · **Define** 7 Charter, 8 SIPOC, 9 As-Is flow, 10 Estimated benefits, 11 Approval email (draft) · **Measure** 12 Data collection plan, 13 Audit and MSA, 14 Baseline KPIs, 15 Daily performance and normality, 16 Capability and sigma · **Analyze** 17–19 Pareto (picking, damage, mismatch), 20 Fishbone, 21 Process time and takt, 22 Data tracker, 23 Control-impact matrix, 24 Hypothesis tests, 25 Impacted X's · **Improve** 26 Prioritisation, 27 Cause-to-solution map, 28 FMEA, 29 Roadmap · **Control** 30 Pre and post, 31 Statistical test and limits, 32 To-Be sigma, 33 Control charts, 34 To-Be map, 35 Benefits, 36 Sustainment plan, 37 Dashboard and RACI, 38 Closure email (draft), 39 Conclusion · Appendix 40 Verification log, 41 Limitations.
