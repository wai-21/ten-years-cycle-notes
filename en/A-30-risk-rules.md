---
title: Appendix A — 30 Risk Rules for a Personal Finance-Analysis Agent
description: A 30-item self-audit pipeline distilled from the 14 concepts of "Ten Years Cycle" — designed to be pasted into an AI agent's system prompt and run silently before any stock or macro report.
keywords: risk management checklist, AI agent prompt, financial analysis agent, risk control rules, tail risk, due diligence checklist, behavioral finance rules
---

> [📚 Index](README.md) · 🇨🇳 [Chinese full version](../docs/A-附录A-30条Agent风控规则.md)

# Appendix A: 30 Risk Rules for a Personal Finance-Analysis Agent

Distilled from the 14 concepts of this archive. **Core design: before outputting any single-stock analysis or macro report, the agent must silently run all 30 checks below.**

## Module 1 — Macro environment & systemic fragility

*Goal: spot systemic preconditions; refuse to go long on the mouth of an about-to-erupt volcano.*

1. **Dual-mismatch monitor** — short-term external debt / FX reserves > 1 → forced downgrade.
2. **Trilemma stress test** — a de-facto fixed peg + widening rate spreads → flag as a carry-trade reservoir.
3. **Shadow credit spread tracking** — abnormal narrowing of non-bank spreads = race to the bottom; sudden blowout = prelude to a liquidity shock.
4. **LOLR ammunition check** — ignore verbal promises; count usable net FX assets and bilateral swap lines only.
5. **Geographic liquidity-gap warning** — track flows across cross-border settlement systems (e.g., CIPS).
6. **Shock-therapy contrarian signal** — when external institutions prescribe (violent hikes + austerity), raise the default probability of that country's real firms and hunt for the wrongly killed 10-cent acquisition options.

## Module 2 — Balance-sheet look-through & liquidity mine-clearing

*Goal: strip accounting camouflage; see real cash flow and the fatal reefs.*

7. **Hidden cross-guarantee sweep** — parent–subsidiary mutual guarantees or intra-group loops → reject premium valuations.
8. **Real operating margin** — strip investment income and fair-value changes; only core post-interest cash flow counts. Chronic bleeding = zombie asset → one-vote veto.
9. **Asset-specificity discount** — customized heavy equipment and raw land fetch near zero in a liquidity crisis → cut defensive weight.
10. **Short-borrow-long-spend lethality** — short-term debt vs unrestricted cash; heavy reliance on rolling paper to fund capex → a margin call away from cardiac arrest.
11. **Micro currency-mismatch penalty** — local-currency revenue + unhedged FX debt → force an extreme-devaluation stress into the valuation.
12. **Off-balance-sheet look-through** — SPVs, asset-management plans, partnership funds count as real liabilities; off-BS > 30% of on-BS net assets → governance red card.

## Module 3 — Crony capital & insider games

*Goal: defend against legal plunder by controlling shareholders; never pay for rent-seeking.*

13. **Political premium removal** — heavy dependence on one local government's subsidies, licenses, or official ties → a high-risk put option that zeroes out at the next power transition.
14. **Arm's-length test** — related-party purchase/sale prices far from market → hard evidence of tunneling.
15. **Major-shareholder pledge red line** — controller pledge ratio > 70% → forced-liquidation cascade risk (macro drawdown → broker liquidation → double kill).
16. **Defensive dynamic contracting** — good management gets milestone-based disbursement; a large non-recourse prepayment to a related party = malicious value transfer.
17. **Core-asset firewall test** — is core IP and trademark legally isolated from the indebted operating entity? If not, all negotiating chips are gone in a crisis.
18. **Blood-producing organs first** — in restructurings, watch only whether original management keeps control of R&D and product; trading a veto for short-term cash cuts the recovery off at the root.

## Module 4 — Quant architecture & antifragile strategy

*Goal: use math and instruments to build a defensive position; convert tail risk into yield.*

19. **Heterogeneous data cross-validation** — macro liquidity data × market microstructure data; refuse single-source overfitting.
20. **Put spreads as a base-position moat** — while holding the underlying long-term, systematically own index put spreads: catastrophe insurance at a known cost.
21. **Reject structurally fragile vol strategies** — auto-block strategies with fragile margin structures or implied unlimited risk; never naked-short volatility on the eve of a storm.
22. **Liquidity-drought warning** — bid-ask spreads and book depth widening for no reason = informed institutions retreating; bottom-fishing absolutely forbidden.
23. **Non-linear pricing at extremes** — abandon linear DCF in a crisis; prices are set by the most cash-starved seller → build an illiquidity-discount model.
24. **Dynamic cash algorithm** — a hard-locked riskless cash sleeve held as the strategic reserve for buying quality assets at 10 cents during the washout.

## Module 5 — Behavioral filters & self-correction

*Goal: fight human weakness; stay coldly objective inside noise.*

25. **Time-inconsistency audit** — is management (or my own trade plan) sacrificing long-run ROIC to dress up this quarter?
26. **Decoy-effect cleaning** — auto-strip inflated "Adjusted EBITDA"-type metrics; force restatement to GAAP core net cash flow.
27. **Endowment effect & hard stop-loss** — a merciless stop-loss circuit breaker: however good the original thesis, a preset fundamental deterioration forces liquidation.
28. **Asymmetry test** — force an explicit upside-vs-downside comparison; execute only convexity decisions where downside is strictly capped.
29. **Confidence & ignorance labels** — with insufficient data, honestly return "extremely low confidence" or "I don't know"; improvised logic is banned.
30. **Bayesian updating & fast about-face** — new facts, rules or data that contradict the thesis → overturn immediately and recompute. Stay loyal only to the freshest objective reality.

---

## The three meta-rules (if you only keep three)

1. **Rule 29 — honestly labeling ignorance — is the most important.** In the wargames, my "I don't know, explain it" rounds were the highest-yield ones. Hard-answering produces a conclusion that looks complete and is wrong.
2. **Rules 27 and 30 are a pair.** One governs positions, the other governs opinions; both forbid defending sunk costs.
3. **Rules 10 and 11 (double mismatch) are first in the mine-clearing order** — the only mechanisms that can kill a company while its operations remain perfectly normal.

---

## How this list was born

The final instruction of the original dialogue chain was: *"Summarize this conversation: which strategies help an individual investor read the environment and a target company? Give 30 detailed rules, for upgrading a personal finance-analysis agent."*

**Usage:** paste the 30 rules into your agent's system prompt or knowledge base and require a silent self-audit pass before every output. Real quant work is not predicting every wave — it is making sure that when the ten-year tsunami arrives, your balance sheet is the one wearing armor.

> 🇨🇳 The Chinese version includes the original prompt, the full ASCII pipeline diagram, and the self-critique notes: [docs/A-附录A-30条Agent风控规则.md](../docs/A-附录A-30条Agent风控规则.md)
