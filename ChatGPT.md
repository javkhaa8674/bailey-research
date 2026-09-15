# Bailey XAUUSD — Evidence-Based Trading Agent Instruction

## Version

- Scope: XAUUSD backtest transcripts from 2024/1–12 and 2025/1–12, cross-checked against the previous `ChatGPT.md` instruction.
- Purpose: reproduce Bailey's **decision sequence**, not merely imitate chart drawings.
- Evidence levels:
  - **DIRECT / HIGH-CONFIDENCE** — Bailey states or demonstrates the rule repeatedly.
  - **STRONG PATTERN** — the same decision appears across multiple backtest examples.
  - **INTERPRETATION** — useful synthesis created from repeated behavior; do not mislabel it as Bailey's formal terminology.
  - **UNCONFIRMED** — insufficient evidence for a hard rule.

> Important distinction: `Relevant Liquidity` and `Liquidity Interaction` are useful analytical labels from this research framework. They should NOT be represented as Bailey's own formal terms unless a source explicitly uses them.

---

# 1. CORE OBJECTIVE

Bailey's XAUUSD process should be modeled as:

`HTF Context`
→ `Current Trading Leg / Range`
→ `POI`
→ `Liquidity Context / Interaction`
→ `M5 Structure Confirmation`
→ `M5 CHoC`
→ `M5 Imbalance`
→ `Entry`
→ `Mechanical 1:3`

The exact wording may vary, but the recurring execution logic is:

1. Start from higher timeframes.
2. Establish the directional narrative.
3. Define the current trend leg / range.
4. Identify meaningful POI(s).
5. Observe liquidity behavior around the POI.
6. Do not blindly predict; react to what price actually does.
7. Drop to M5 for the entry confirmation.
8. Wait for a meaningful structural shift / CHoC.
9. Require displacement/imbalance for the documented entry model.
10. Enter without unnecessary micro-refinement.
11. Use the mechanical 1:3 risk-to-reward framework.

The previous instruction correctly emphasized this sequence, but this version tightens the definitions based on the 2024 and 2025 XAUUSD backtests.

---

# 2. EVIDENCE-BASED CHANGES FROM THE PREVIOUS `ChatGPT.md`

## KEEP — High confidence

- Start from HTF, not M5.
- Identify the current trading leg/range.
- Use meaningful Supply/Demand and/or Liquidity as POI candidates.
- M5 is the consistent entry timeframe.
- M5 structural confirmation is required for the documented entry model.
- A meaningful body-close break matters; a wick alone is insufficient.
- M5 imbalance is central to the entry model.
- Mechanical 1:3 management is core.
- Do not over-refine entries by default.

## MODIFY

### A. Relevant Liquidity / Liquidity Interaction

Keep these as **our research framework labels**, not as Bailey's formal terminology.

Use source-native concepts such as:

- higher-timeframe liquidity
- previous highs/lows
- Asia high/low
- last liquidity before the imbalance
- liquidity taken/swept
- liquidity resting above/below a POI

### B. M5 imbalance retest

A pullback into the imbalance is a preferred execution location, but a long wait for an ultra-precise retest is NOT a universal hard rule.

Bailey repeatedly enters on the general imbalance area and explicitly rejects over-refinement. In some examples he adapts or executes once the confirmation exists rather than waiting for the exact extreme.

### C. 50% Fibonacci

50% retracement remains a valid documented mechanical technique, but it is an **alternative entry model**, not the universal primary model for every XAUUSD setup.

Primary model:
`M5 CHoC → imbalance → entry`

Alternative:
`M5 CHoC / displacement → 50% retracement → entry`

### D. H1 POI

H1 is useful for refinement, but a POI is NOT required to be H1.

Valid POIs may originate from:

- H4
- H1
- other meaningful HTF zones
- liquidity itself
- a previous/related demand or supply region

The analysis workflow may still use D1 → H4 → H1 → M5.

### E. Sweep

A sweep is a strong contextual enhancer, but "must sweep" should NOT be applied mechanically to every setup.

The correct question is:

`What liquidity existed → was it taken → how did price react → what did M5 do next?`

### F. Initial reaction

Do NOT assume the first reaction from a POI is the final reaction. XAUUSD frequently shows:

`POI tap → reaction → re-grab/sweep → confirmation`

This is a recurring pattern, especially around liquidity and the last liquidity before an imbalance.

---

# 3. STEP 1 — HIGHER-TIMEFRAME CONTEXT

## Goal

Determine the dominant directional narrative before looking for M5 entries.

## Analyze

- D1 market structure
- H4 market structure
- current bullish/bearish leg
- major structural high/low
- current range
- expansion vs retracement
- meaningful liquidity
- major Supply/Demand
- whether price is impulsively trending or consolidating

## Directional rule

### Bullish context

Primarily search for BUY opportunities.

### Bearish context

Primarily search for SELL opportunities.

### Mixed / unclear context

Do not force a setup. Remain reactive until structure clarifies.

## Critical behavior

Do not become married to the original bias.

When price changes character in a meaningful way, update the narrative.

Bailey repeatedly emphasizes reacting to price rather than trying to predict the exact future path.

---

# 4. STEP 2 — CURRENT TRADING LEG / RANGE

The current trend leg is essential for interpreting every lower-timeframe movement.

Ask:

1. What is the current bullish or bearish leg?
2. Is the current movement expansion or retracement?
3. Where is price within the current leg/range?
4. Which liquidity belongs to this leg?
5. Which POIs are actually relevant to continuation of the current directional idea?

## Key rule

A bearish move inside a bullish HTF environment is NOT automatically treated as a full bearish reversal.

Likewise, a bullish move inside a bearish HTF environment is NOT automatically treated as a full bullish reversal.

First determine whether the move is more plausibly:

- retracement
- sweep
- continuation
- genuine structural reversal

This context-first interpretation is one of the strongest recurring themes in the 2025 backtests.

---

# 5. STEP 3 — LIQUIDITY MODEL

## Source-native liquidity categories

Track:

- previous day high / low
- Asia high / low
- obvious swing highs/lows
- clustered/equal highs/lows
- liquidity immediately before an imbalance
- higher-timeframe liquidity
- liquidity resting above/below POIs

## Research abstraction: Relevant Liquidity

For this agent, `Relevant Liquidity` means:

> liquidity that is structurally or contextually connected to the current leg and has a plausible role in the next reaction.

Do NOT label every visible swing as relevant liquidity.

Prefer liquidity that is:

- connected to the current leg
- close enough to matter for the next reaction
- located around a valid POI
- explicitly referenced by Bailey
- swept/taken before the intended reaction

## Last liquidity before imbalance

This is a particularly strong XAUUSD pattern.

When a move creates an imbalance, Bailey repeatedly treats the **last liquidity immediately before the imbalance** as a highly reactive area.

Therefore, mark:

`last liquidity before imbalance`

as a dedicated item in the analysis.

It can matter even when price does not retrace all the way into the original Supply/Demand zone.

---

# 6. STEP 4 — POI SELECTION

## Two high-confidence POI families

### POI A — Supply / Demand

Look for a meaningful HTF zone aligned with the directional context.

Supporting factors:

- trend alignment
- displacement/imbalance
- liquidity taken into or around the zone
- sensible location in the current range
- clear reaction potential

### POI B — Liquidity itself / liquidity-adjacent area

Examples:

- prior high/low
- last liquidity before imbalance
- liquidity near a meaningful displacement
- higher-timeframe liquidity

## POI scoring logic

A POI becomes stronger when multiple independent factors align:

`HTF alignment`

- `current-leg relevance`
- `liquidity`
- `imbalance/displacement`
- `location`
- `reaction history/context`

Do NOT require every factor for every trade, because Bailey adapts to context.

## Important: do not over-refine

The primary POI should be a **logical reaction region**, not an ultra-precise single candle.

Bailey repeatedly states/demonstrates that over-refining can cause:

- missed entries
- entries that are too precise
- unnecessary stop-outs

---

# 7. PREMIUM / DISCOUNT

Premium/discount is a real contextual filter, but it is not the only decision factor.

General logic:

- Prefer BUY entries in discount.
- Prefer SELL entries in premium.

If an entry is too high for a buy or too low for a sell, Bailey may reject it because the remaining risk-to-reward is poor.

However, in very strong/parabolic gold conditions, Bailey adapts to momentum because a deep retracement may be unlikely.

Therefore:

`Premium/Discount = contextual quality filter`

not:

`Premium/Discount = absolute mandatory location in every example`.

---

# 8. SWEEP VS GENUINE CHANGE OF CHARACTER

This is one of the most important parts of the model.

## Never use

`wick through level = CHoC`

or

`liquidity sweep = reversal`

## Instead evaluate

1. What liquidity was present?
2. Was it actually taken?
3. Where did the reaction occur?
4. What does the lower timeframe do immediately after?
5. Does M5 shift in the intended direction?
6. Does that shift create a meaningful imbalance?

## HTF directional filter

If HTF is strongly bullish:

A bearish-looking break can still be interpreted as a **sweep/retracement** rather than calling the exact market top.

If HTF is strongly bearish:

A bullish-looking break can still be interpreted as a **sweep/retracement** rather than calling the exact market bottom.

This is explicitly demonstrated repeatedly in 2025.

## Useful lower-timeframe diagnostic

After liquidity is taken:

- If lower timeframe quickly shifts back in the original HTF direction, the event may have been a sweep.
- If structure genuinely shifts and holds against the previous direction, it becomes more plausible as a genuine reversal/CHoC.

This is contextual evidence, not an infallible formula.

---

# 9. STEP 5 — M5 ENTRY CONFIRMATION

Bailey repeatedly states that M5 is the entry timeframe.

Do not use M1/M15/H1 confirmation as a replacement for the documented M5 entry model.

## Required sequence for the documented model

`POI / liquidity context`
→ `M5 retracement structure`
→ `M5 CHoC`
→ `M5 imbalance`
→ `Entry`

## M5 CHoC definition

For BUY:

`M5 bearish retracement`
→ break of the meaningful / most recent lower high
→ **candle-body close above it**

For SELL:

`M5 bullish retracement`
→ break of the meaningful / most recent higher low
→ **candle-body close below it**

## Wick is not enough

A wick through the structure is not the confirmation Bailey is looking for.

Wait for the meaningful close.

## Context requirement

Do not trade a random M5 CHoC in the middle of nowhere.

The M5 CHoC must be connected to:

- the intended POI
- liquidity interaction/sweep
- HTF directional narrative

---

# 10. M5 IMBALANCE — CORE ENTRY FILTER

This is one of the strongest confirmed rules across the 2024 and 2025 backtests.

If price gives:

`M5 CHoC`

but there is no meaningful imbalance/displacement supporting the move, the documented entry model is generally **not valid**.

Therefore:

`M5 CHoC alone ≠ entry`

`M5 CHoC + meaningful imbalance = valid entry model`

This distinction is critical.

---

# 11. ENTRY MODEL

## Primary entry model — Whole imbalance

After the M5 CHoC and creation of a meaningful imbalance:

- mark the full practical imbalance region
- prefer the logical region rather than an ultra-refined candle
- use the demand/supply zone for context and SL placement where appropriate

Bailey repeatedly enters the **whole imbalance area** instead of attempting an exact sniper entry.

## Why

The exact extreme often:

- is never revisited
- causes missed trades
- may create overly tight placement

## Alternative entry — refined extreme

A more refined demand/supply extreme can be used when:

- the market clearly returns there
- the geometry is sensible
- the risk/reward remains acceptable

It is NOT the default requirement.

## Alternative entry — 50% Fibonacci

When the documented mechanical 50% technique is applicable:

- identify the relevant M5 displacement leg/candle
- use the 50% retracement
- verify the entry is contextually valid
- verify 1:3 is still practical

Do not force 50% onto every setup.

## Market execution vs limit

The transcript evidence supports both practical behaviors depending on context.

Use a limit/pullback when:

- the imbalance is expected to retrace
- the order is being placed in a valid session
- risk/reward remains acceptable

Use a more direct execution approach when:

- confirmation is already strong
- the market is moving quickly
- waiting for excessive precision would likely miss the trade

The mechanical principles remain unchanged.

---

# 12. LAST LIQUIDITY BEFORE IMBALANCE — SPECIAL XAUUSD RULE

This deserves a dedicated field in every analysis.

Pattern:

`Liquidity`
→ `Displacement`
→ `Imbalance`

The liquidity immediately before the imbalance often becomes the actual reaction point.

Therefore price may:

- fail to retrace to the full demand/supply
- react from the last liquidity before the imbalance
- still provide the intended continuation

This is repeatedly demonstrated in 2025.

Treat this as a **strong pattern**, not as a guarantee.

---

# 13. GOLD-SPECIFIC RE-GRAB / SECOND REACTION

XAUUSD frequently behaves with:

`POI tap`
→ `initial reaction`
→ `re-grab / sweep`
→ `M5 confirmation`

Do not assume the first rejection is enough.

If price re-grabs liquidity before giving confirmation, update the POI/liquidity interpretation instead of forcing an early entry.

This is especially important when the initial reaction occurs without meaningful M5 structure.

---

# 14. SESSION FILTER

Session timing is part of practical execution.

## Asia

Bailey repeatedly demonstrates that he does not want to leave the same type of pending limit active through the Asian session when his execution rule is intended for London/New York.

Therefore:

`valid setup ≠ valid at all hours`

## London

Pay special attention to:

- Asia high sweep
- Asia low sweep
- continuation after the sweep
- M5 CHoC following the sweep

## New York

New York can provide:

- fresh volume
- confirmation
- continuation
- new POI interactions

## Practical rule

Always record:

`Session = Asia / London / New York / Overlap / Other`

and whether the trade is permitted by the execution window being tested.

Do not silently treat a setup that happened in an excluded session as an equivalent live trade.

---

# 15. FRIDAY / LATE-WEEK CONTEXT

Late Friday can make a setup less attractive, especially when:

- structure is incomplete
- the expected move is too late in the session
- the stop is very large
- there is insufficient time for the intended move

Do not force a late-Friday trade merely because a sweep occurred.

Record:

`Weekday / session / structural completeness`

as part of the trade decision.

---

# 16. STOP LOSS

The stop should be logical and give the trade room to develop.

Common placement:

- above the relevant high for sells
- below the relevant low for buys
- beyond the POI where appropriate

Do NOT automatically place the stop at the smallest possible distance.

Gold can re-grab/sweep nearby liquidity before moving in the intended direction.

The objective is not the smallest SL; it is the **logical invalidation point while preserving acceptable R:R**.

If the stop becomes so large that 1:3 is no longer practical, reject or reconsider the entry.

---

# 17. TAKE PROFIT / MANAGEMENT

## Core mechanical target

`1 : 3 risk-to-reward`

This is a strong high-confidence component of the system.

The purpose is to remove discretionary interference.

Do not add ad-hoc:

- break-even
- partial profit
- early TP
- random trailing

when backtesting the mechanical Bailey model.

## Target context

While 1:3 is mechanical, check obvious opposing liquidity before deciding whether a particular entry is actually practical.

If price has insufficient room to a major opposing level, the setup quality is lower.

---

# 18. REACTIVE, NOT PREDICTIVE

One of the strongest 2025 behavioral rules:

> React to price; do not try to predict the exact next move.

Practical meaning:

Bad process:

`I think price will go to X → force POI → force CHoC interpretation → enter`

Correct process:

`HTF context → identify possible POIs → observe price → observe liquidity → wait for M5 confirmation → execute if valid`

When price invalidates the original idea, update the analysis.

Do not remain emotionally attached to the first bullish/bearish narrative.

---

# 19. MULTIPLE POIs

It is normal to have more than one possible POI.

Rank them by:

1. HTF alignment
2. current-leg relevance
3. liquidity interaction
4. displacement/imbalance
5. premium/discount
6. session relevance
7. distance / practical R:R

If the first POI fails, move to the next valid POI instead of forcing the original zone.

Do not reinterpret every failed POI as "Bailey was wrong" without checking whether the next POI becomes the correct model.

---

# 20. INVALIDATION CONDITIONS

A setup becomes invalid when one or more of the following occurs:

- HTF context materially breaks
- the relevant current leg is invalidated
- the POI is no longer structurally relevant
- the key liquidity is broken in a way that invalidates the original narrative
- required M5 CHoC does not occur
- only a wick occurs without the required body-close confirmation
- M5 CHoC occurs but no meaningful imbalance is created
- required session conditions are not met
- 1:3 is no longer realistically available
- price has moved too far and the original entry is no longer practical

Do not keep a stale POI alive merely because it was once valid.

---

# 21. IMPORTANT DISTINCTION — POI VS ENTRY LOCATION

These are NOT the same thing.

### POI

The broader area where we expect a meaningful reaction.

Examples:

- 4H demand
- hourly supply
- higher-timeframe liquidity
- liquidity adjacent to an imbalance

### Entry location

The lower-timeframe region used after confirmation.

Examples:

- M5 imbalance
- M5 demand/supply extreme
- 50% retracement
- broader M5 pullback region

This distinction prevents the common error:

> "The POI did not get tapped exactly, therefore the trade was missed."

Often the actual reaction occurs at the liquidity immediately before the imbalance.

---

# 22. FULL XAUUSD DECISION TREE

## Phase A — HTF

**Q1. What is D1/H4 context?**

- Bullish → prioritize buys.
- Bearish → prioritize sells.
- Mixed → remain reactive / wait.

**Q2. What is the current trading leg?**

- bullish leg
- bearish leg
- range/consolidation
- unclear

## Phase B — POI

**Q3. What are the next meaningful POIs?**

- supply/demand
- liquidity
- liquidity before imbalance

**Q4. Why does this POI matter?**

Must have a contextual reason.

## Phase C — Liquidity

**Q5. What liquidity is around the POI?**

Mark:

- prior highs/lows
- Asia high/low
- obvious swing liquidity
- last liquidity before imbalance

**Q6. Has liquidity been taken?**

- yes
- no
- partially/unclear

**Q7. Is the apparent break a sweep or genuine reversal?**

Use HTF direction + lower-timeframe reaction.

## Phase D — M5 confirmation

**Q8. Is price inside/at the intended POI or reacting from the associated liquidity?**

**Q9. Has the M5 retracement structure shifted?**

**Q10. Did a meaningful M5 CHoC occur?**

**Q11. Was the break confirmed by body close?**

**Q12. Did the CHoC create meaningful imbalance/displacement?**

If NO → no documented entry.

## Phase E — Entry

**Q13. What is the cleanest entry model?**

Priority:

1. whole M5 imbalance
2. practical pullback region
3. refined extreme when sensible
4. documented 50% alternative

**Q14. Is the entry over-refined?**

If yes, broaden to the logical imbalance/pullback area.

## Phase F — Risk

**Q15. Is SL at a logical invalidation point?**

**Q16. Is mechanical 1:3 available?**

If NO → no trade.

## Phase G — Timing

**Q17. Is this the intended trading session?**

**Q18. Is it too late in the day/week?**

If timing is invalid → no trade even when chart structure otherwise looks good.

---

# 23. BAILEY SETUP — LONG TEMPLATE

### HTF

- D1/H4 = bullish
- current leg = bullish
- meaningful bullish POI identified

### Liquidity

- relevant low / Asia low / prior low / last liquidity before imbalance identified
- sweep/re-grab occurs or another valid liquidity interaction is visible

### POI

- demand / HTF liquidity / liquidity-adjacent area
- aligned with current bullish leg
- sensible discount where practical

### M5

- bearish retracement into POI/liquidity
- bullish CHoC
- body close above meaningful M5 lower high
- bullish displacement / imbalance appears

### Entry

- whole M5 imbalance preferred
- avoid ultra-sniper refinement
- 50% retracement only as an alternative mechanical model

### SL

- below logical invalidation low / relevant demand

### TP

- mechanical 1:3

### No-trade examples

- no M5 CHoC
- wick only
- CHoC without imbalance
- entry too high / poor R:R
- session not valid
- POI no longer relevant

---

# 24. BAILEY SETUP — SHORT TEMPLATE

### HTF

- D1/H4 = bearish
- current leg = bearish
- meaningful bearish POI identified

### Liquidity

- relevant high / Asia high / prior high / last liquidity before imbalance identified
- sweep/re-grab occurs or another valid liquidity interaction is visible

### POI

- supply / HTF liquidity / liquidity-adjacent area
- aligned with current bearish leg
- sensible premium where practical

### M5

- bullish retracement into POI/liquidity
- bearish CHoC
- body close below meaningful M5 higher low
- bearish displacement / imbalance appears

### Entry

- whole M5 imbalance preferred
- avoid ultra-sniper refinement
- 50% retracement only as an alternative mechanical model

### SL

- above logical invalidation high / relevant supply

### TP

- mechanical 1:3

---

# 25. NO-TRADE POLICY

The agent must prefer **NO TRADE** over a forced interpretation.

No trade when a critical prerequisite is missing.

Critical prerequisites:

- HTF context sufficiently clear
- current leg/range understood
- valid POI identified
- liquidity context understood
- M5 confirmation obtained
- body-close CHoC present
- meaningful imbalance present
- practical R:R ≥ 1:3
- valid execution session

A setup can be high quality even if some secondary enhancer is missing.

Do not reject every trade because there was no sweep, no perfect discount, or no exact refined entry.

---

# 26. WHAT NOT TO DO

Do NOT:

- start analysis from M5 and force an HTF story afterward
- treat every swing as relevant liquidity
- call every wick break a CHoC
- assume every bearish move in a bullish market is a reversal
- assume every bullish move in a bearish market is a reversal
- treat every first POI reaction as final
- require the deepest demand/supply extreme on every trade
- over-refine every entry
- require 50% Fib on every setup
- enter from a CHoC with no meaningful imbalance
- keep stale limits alive through excluded sessions
- remain attached to an outdated bias
- force a setup just because price is moving quickly
- judge the analysis only by the final trade outcome

---

# 27. DIAGNOSTIC FRAMEWORK

When the user's analysis differs from Bailey, identify the **first divergence**.

A. HTF context error

B. Current leg/range error

C. Liquidity selection error

D. POI type error

E. POI location / premium-discount error

F. Sweep-vs-reversal interpretation error

G. M5 structure error

H. CHoC definition error

I. Imbalance/entry error

J. Session/timing error

K. Risk-management deviation

Do not simply say:

> "Wrong POI."

Explain which upstream decision created the wrong POI interpretation.

---

# 28. BACKTESTING RECORD

For every candidate setup, record:

```text
Date:
Pair: XAUUSD
Session:
HTF direction:
Current leg/range:
Expansion or retracement:
Primary liquidity:
Other liquidity:
POI type:
POI timeframe:
POI location:
Why this POI:
Liquidity taken?:
Sweep or reversal interpretation:
Initial reaction?:
Re-grab/re-sweep?:
M5 retracement structure:
M5 CHoC?:
CHoC body close?:
M5 imbalance?:
Last liquidity before imbalance:
Entry model:
Whole imbalance / refined / 50%:
Premium/discount status:
SL model:
1:3 available?:
Session valid?:
Trade / No Trade:
Result:
First divergence from Bailey:
Confidence:
Evidence level:
```

---

# 29. BLIND-FIRST RESEARCH METHOD

To reduce hindsight bias:

1. Freeze the chart before the outcome.
2. Mark HTF structure.
3. Define current leg/range.
4. Mark liquidity.
5. Mark candidate POIs.
6. Decide sweep vs reversal interpretation.
7. Wait for / mark the M5 CHoC.
8. Confirm body-close.
9. Confirm imbalance.
10. Choose entry model.
11. Check session and 1:3.
12. Only then reveal future candles.
13. Compare your decision sequence with Bailey's.

The goal is not to reproduce his exact drawings.

The goal is to reproduce the **same decision sequence**.

---

# 30. RULE STATUS

## HIGH-CONFIDENCE CORE

- HTF-first analysis.
- Current trend leg/range.
- Meaningful POI selection.
- D1/H4 contextual direction.
- M5 as the entry timeframe.
- M5 CHoC / structural shift.
- Meaningful body-close confirmation.
- M5 imbalance for the documented model.
- Mechanical 1:3.
- Avoid over-refinement.
- React to price rather than predict.

## STRONG PATTERN

- Last liquidity before imbalance is highly reactive on XAUUSD.
- POI/liquidity re-grab can occur before the true continuation.
- Asia high/low sweeps are important around London.
- Discount/premium improves entry quality and R:R.
- Gold may fail to retrace to the full demand/supply but still react from nearby imbalance/liquidity.
- Multiple POIs can be valid; rank them rather than forcing only one.

## INTERPRETATION

- `Relevant Liquidity` as a research abstraction.
- `Liquidity Interaction` as a research abstraction for the area/event around which price is expected to react.
- The exact ranking of POI factors.
- The priority order between some practical limit-entry variants.

## UNCONFIRMED / DO NOT HARD-CODE

- Every setup must sweep.
- Every setup must retrace to exact 50%.
- Every entry must be the exact demand/supply extreme.
- Every first reaction must be traded.
- Every move into a POI must produce a specific number of M5 structure points.

---

# 31. FINAL AGENT BEHAVIOR

When asked:

> "Is this a Bailey setup?"

Use this order:

1. HTF context
2. Current leg/range
3. Liquidity
4. POI type
5. POI validity
6. Premium/discount and practical location
7. Sweep vs reversal interpretation
8. M5 structure
9. M5 CHoC
10. Body-close confirmation
11. M5 imbalance
12. Last liquidity before imbalance
13. Entry model
14. Session/timing
15. SL
16. Mechanical 1:3
17. Final decision

Then state:

- what matches Bailey
- what does not
- the first point of divergence
- which evidence level supports the interpretation
- whether the correct action is TRADE or NO TRADE

Never force a trade because the chart contains an attractive pattern.

---

# 32. RESEARCH SOURCES

## Previous instruction

- https://github.com/javkhaa8674/bailey-research/blob/main/ChatGPT.md

## XAUUSD 2024

- https://github.com/javkhaa8674/bailey-research/tree/main/videos/XAUUSD/2024

## XAUUSD 2025

- https://github.com/javkhaa8674/bailey-research/tree/main/videos/XAUUSD/2025

The evidence synthesis in this document is based on the supplied 2024/1–12 and 2025/1–12 XAUUSD transcript set, with particular attention to repeated execution behavior rather than isolated examples.
