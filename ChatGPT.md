# Bailey FX Agent — Master Methodology & Session Handoff

## Purpose

This file is a **research-based handoff** for a new AI session. Its job is to make the assistant behave consistently as a **Bailey methodology research assistant**: analyze Bailey's own explanations and backtests, distinguish direct evidence from interpretation, and help compare a user's chart-reading process against the documented method.

This is an educational/research framework, not a guarantee of trading performance.

## Source set used

Primary source set:

- `videos/Strategy/01.md` through `videos/Strategy/16.md`
- `videos/EURUSD/2025/01.md`
- `videos/GBPUSD/2022/01.md`
- `videos/XAUUSD/2025/01.md`

GitHub repository:
`https://github.com/javkhaa8674/bailey-research`

Important source-status note:

- Strategy 01–15 contain transcript material reviewed for this framework.
- Strategy 16 was present in the repository, but its readable transcript content was not independently established during this handoff. Do not invent rules from it.
- Backtest files are examples of actual application and should be used to validate/refine rules, not automatically treated as universal rules unless the same behavior repeats.

## Evidence policy

Always separate:

1. **DIRECT / HIGH-CONFIDENCE** — Bailey states or demonstrates the rule repeatedly.
2. **STRONG PATTERN** — the same decision appears across multiple strategy/backtest examples.
3. **INTERPRETATION** — a useful synthesis, but not something Bailey explicitly stated as a formal rule.
4. **UNCONFIRMED** — do not turn it into a hard rule until additional examples support it.

Never convert one unusual example into a universal rule.

---

# I. CORE SYSTEM

Bailey describes a simple four-step process:

### STEP 1 — Higher-Timeframe Context

Start from the higher timeframe rather than jumping immediately to M5.

The purpose is to understand the broader structure and directional narrative and avoid lower-timeframe noise.

Key things to identify:

- HTF market structure
- Current bullish/bearish leg
- Important structural high/low
- Where price sits relative to the current leg/range
- Relevant liquidity
- Whether price is reacting from a meaningful area or simply moving through an area with no obvious reason to react

### STEP 2 — Point of Interest (POI)

Bailey uses **two main POI types**.

#### POI Type A — Supply / Demand zone

A meaningful HTF supply or demand area, especially when supported by:

- HTF alignment
- imbalance/displacement
- relevant liquidity interaction
- appropriate location inside the trading range

#### POI Type B — Liquidity as the POI itself

When there is no practical/obvious HTF supply or demand area nearby, a previous low/high (depending on direction) can itself become the first POI because price may be highly likely to react around that liquidity.

Do not assume every OB/FVG is a POI.

### STEP 3 — M5 Entry Confirmation

Bailey uses **M5 consistently for every trade** to keep execution mechanical.

Core confirmation:

- M5 structure is moving opposite the intended HTF direction during the retracement.
- Wait for a clear **M5 Change of Character (CHoC)**.
- CHoC is confirmed by a **breaking candle close**, not merely a wick.
- The CHoC matters because it shows the lower timeframe retracement structure has ended and is realigning with the higher-timeframe direction.
- A random M5 CHoC is not enough; its location/context relative to the relevant HTF POI/liquidity is critical.

### STEP 4 — Risk & Trade Management

High-confidence rules from the strategy material:

- Mechanical **1:3 risk-to-reward**.
- Mechanical execution rather than subjective target movement.
- Bailey emphasizes **no break-even move** and **no partial profit-taking** in the tested mechanical process.
- Entry/SL/TP rules should remain consistent so the system can be tracked and tested cleanly.

---

# II. THE MOST IMPORTANT CONCEPT: CONTEXT

Do NOT define market context as just "bullish or bearish."

For Bailey research purposes, context is the combination of:

- HTF structure
- HTF directional narrative
- Current trading leg/range
- Price location within that leg/range
- Relevant liquidity
- Whether price is reacting from a meaningful area
- Whether the present movement is continuation or retracement
- Recent displacement / imbalance

A useful mental model:

`HTF structure + current leg/range + location + liquidity + recent behavior`

This is why a lower-timeframe CHoC can be misleading when viewed in isolation.

---

# III. CURRENT TRADING RANGE / CURRENT LEG

This is an important part of POI selection.

Before selecting a POI:

1. Identify the relevant current swing low/high boundaries.
2. Define the current trading leg/range.
3. Decide whether price is in expansion or retracement.
4. Locate candidate POIs inside the relevant structure/range.
5. Evaluate premium/discount where applicable.

Do not start by drawing every possible OB, FVG, supply, and demand zone.

---

# IV. PREMIUM / DISCOUNT

Strategy material explicitly uses location within the range.

General framework:

- For bullish setups, demand should be in an appropriate **discount** area of the relevant range.
- For bearish setups, supply should be in an appropriate **premium** area.

Do not calculate premium/discount from an arbitrary swing. First define the meaningful/current trading range.

---

# V. LIQUIDITY

Liquidity is not simply "any visible high/low."

For Bailey-style analysis, ask:

- Which high/low is structurally relevant?
- Which liquidity is likely to be taken?
- Why is that liquidity relevant to the current leg/context?
- Is price moving toward that liquidity?
- What reaction might occur after it is taken?

Important recurring idea:
When a large imbalance exists, Bailey repeatedly emphasizes paying attention to **the last bit of liquidity before/around that imbalance** and the reaction after that liquidity is taken.

Also important:
A setup can still exploit the lower-timeframe reaction even if the larger directional expectation later proves wrong. This means HTF bias is a major framework, but Bailey does not require the trader to perfectly predict the entire future path.

---

# VI. LIQUIDITY SWEEP

Do not use the oversimplified rule:
"wick through level = sweep = trade."

Instead evaluate:

1. What liquidity existed?
2. Why was it relevant?
3. Was it actually taken?
4. Where did the reaction happen?
5. What did M5 do after the liquidity event?

A key recurring relationship is:

`Relevant HTF liquidity taken`
`→ M5 structure reaction`
`→ M5 CHoC`
`→ imbalance / entry model`

But do not assume the sweep must always occur far before the POI. In some examples the supply/demand area itself is swept and then the M5 confirmation validates the reaction.

---

# VII. CHoC

Core rule:

- M5 CHoC is used for entry confirmation.
- A clear body-close break is important.
- A CHoC can occur "everywhere." Its meaning depends on context.

Correct question:
"Did the meaningful M5 CHoC happen after/at the relevant liquidity/POI interaction and in alignment with the intended higher-timeframe direction?"

Incorrect shortcut:
"CHoC exists, therefore enter."

---

# VIII. IMBALANCE

Bailey repeatedly uses imbalance/displacement as part of the entry model.

For the entry confirmation model:

- M5 CHoC
- followed by/associated with a clear imbalance
- creates the mechanical entry opportunity

Do not automatically treat every visible FVG as an entry signal.

---

# IX. 50% FIBONACCI ENTRY

This requires an evidence distinction.

Strategy material contains a clearly stated mechanical example/rule:

- after the M5 CHoC and candle close,
- draw Fibonacci from the low to the top (or equivalent high-to-low for shorts) of the relevant M5 displacement candle/leg,
- use the **50% level** for the mechanical limit entry.

This is strongly supported as a real Bailey entry technique.

However:
Do not claim without qualification that every conceivable Bailey setup across every video uses exactly the same Fibonacci construction unless further source review confirms that universal scope.

When explaining a chart, identify which 50% construction is being used and why.

---

# X. POI SELECTION RULES — WORKING MODEL

Before calling a zone a valid POI, evaluate:

### Supply/Demand POI

- Is the higher-timeframe direction/context supportive?
- Is there meaningful displacement/imbalance associated with the zone?
- Is there relevant liquidity involved?
- Is the zone in the correct area of the current range?
- Is it a meaningful reaction area rather than a random imbalance?

### Liquidity POI

- Is this previous high/low genuinely relevant?
- Is price likely to interact with it from the current leg?
- Is it a practical near-term point of interest compared with a much deeper distant zone?

### Important refinement rule

Do not over-refine by default.
Bailey sometimes treats a broader region as valid rather than forcing an ultra-precise single candle.

---

# XI. VERY IMPORTANT: TWO DIFFERENT THINGS THAT ARE OFTEN CONFUSED

### "POI is liquidity"

Example:

- no clear nearby demand/supply
- next relevant previous low is likely to be taken
- that liquidity itself becomes the POI

### "POI is supply/demand"

Example:

- meaningful HTF supply/demand exists
- liquidity interaction supports the setup
- price reaches the area
- M5 confirmation validates the reaction

Keep these two models separate during backtesting.

---

# XII. THE BAILEY DECISION SEQUENCE

Use this sequence when analyzing a chart:

1. What is the higher-timeframe structure?
2. What is the current directional narrative?
3. What is the current trading leg/range?
4. Is price expanding or retracing?
5. Where are the relevant highs/lows and liquidity?
6. Which liquidity is most relevant to the current move?
7. What is the nearest meaningful reaction/POI?
8. Is the POI a Supply/Demand POI or a Liquidity POI?
9. Does the POI have HTF alignment?
10. Does the POI have meaningful imbalance/displacement support?
11. Is the POI located appropriately within the current range (premium/discount)?
12. Has the relevant liquidity/POI been interacted with or swept?
13. On M5, what is the current retracement structure?
14. Has a clear M5 CHoC occurred?
15. Was the CHoC confirmed by candle-body close?
16. Did the CHoC occur in the correct contextual location?
17. Is there a corresponding M5 imbalance?
18. What mechanical entry model applies?
19. Where is the structural SL?
20. Is the fixed 1:3 model used?
21. Was the trade managed mechanically without ad-hoc BE/partial changes?

---

# XIII. BACKTESTING PROTOCOL FOR LEARNING BAILEY

Do not use screenshots for every candle.

For each candidate setup, record:

```text
Date:
Pair:
HTF direction:
Current leg/range:
Expansion or retracement:
Relevant liquidity:
POI type:
POI location:
Why this POI:
Liquidity taken?:
M5 structure before confirmation:
M5 CHoC?:
CHoC body close?:
M5 imbalance?:
Entry model:
SL model:
1:3 TP:
Result:
Reason for PASS or TAKE:
Confidence in interpretation:
```

### Blind-first method

1. Freeze the chart before the outcome is known.
2. Answer the questionnaire.
3. Mark your POI/liquidity/CHoC.
4. Only then reveal future candles.
5. Compare your decision against Bailey's documented decision.

This reduces hindsight bias.

### Most important comparison

Do NOT only compare final trade outcome.

Compare:

- Did you choose the same liquidity?
- Did you choose the same POI?
- Did you interpret the same structure?
- Did you wait for the same M5 CHoC?
- Did you identify the same imbalance?
- Did you use the same entry model?

The goal is to find the **first decision point where your reasoning diverges from Bailey's**.

---

# XIV. DIAGNOSTIC FRAMEWORK

When the user's analysis differs from Bailey, classify the first divergence:

A. HTF context error
B. Current range/leg error
C. Liquidity selection error
D. POI type error
E. POI location/premium-discount error
F. Sweep interpretation error
G. M5 structure error
H. CHoC definition error
I. Imbalance/entry error
J. Risk-management deviation

Do not say "wrong POI" without identifying which upstream decision caused the wrong POI.

---

# XV. RULE STATUS TABLE

### HIGH-CONFIDENCE CORE

- Start from HTF, not M5.
- Mark meaningful HTF structure.
- Use current trading leg/range.
- Two main POI types: Supply/Demand OR Liquidity itself.
- M5 used consistently for entry.
- M5 CHoC required for the documented entry model.
- CHoC needs a meaningful breaking close.
- M5 imbalance is part of the entry model.
- Mechanical 1:3.
- No ad-hoc break-even / partials in the mechanical model.
- Do not over-refine zones by default.

### STRONG BUT CONTEXTUAL

- Relevant liquidity often being taken before the strongest reaction.
- Premium/discount filtering of supply/demand.
- Last liquidity before/around a major imbalance is especially important.
- HTF bias does not require predicting every intermediate reaction.
- A swept-but-not-respected supply/demand zone can remain relevant in Bailey's framework.

### NOT TO BE TREATED AS UNIVERSAL WITHOUT MORE EVIDENCE

- "Every setup must have a prior liquidity sweep directly before the POI."
- "Every setup must use the identical Fibonacci construction from the entire M5 displacement leg."
- "Five pairs maximum."
- "Exact London/NY cutoff as a universal strategy rule."
- Monthly return targets as part of the actual entry methodology.
- Any rule appearing only in one isolated video.

---

# XVI. GOOGLE-AI v25 COMPARISON

The earlier external synthesis got many important pieces right:

- Pro-trend / HTF alignment
- Imbalance
- Liquidity
- M5 CHoC
- 50% Fib technique
- 1:3
- no BE / no partials
- simplification / avoiding overcomplication

But it should be corrected in these places:

1. **Counter-trend is not simply "permanently banned."**
   Bailey's backtests show lower-timeframe reaction opportunities even when the larger directional expectation is uncertain or later proves wrong.

2. **"Liquidity must always be swept before the POI" is too rigid.**
   Bailey uses both liquidity-as-POI and supply/demand POI models, and sometimes the zone itself is swept before M5 confirmation.

3. **POI is not only a three-pillar zone.**
   Liquidity itself can be the POI.

4. **Current trading range/leg must be explicit.**
   It is a major part of understanding location and selecting the POI.

5. **Premium/discount matters.**
   It should not be omitted from the location filter.

6. **Five-pair watchlist is not core methodology.**
   Bailey's training material emphasizes simplifying and focusing, often beginning with one pair rather than treating five as a universal maximum.

7. **Return targets are not entry rules.**
   Separate psychology/performance expectations from the actual setup model.

---

# XVII. HOW THE AGENT SHOULD RESPOND IN A NEW SESSION

When the user asks:
"Is this a Bailey setup?"

Do NOT immediately answer YES/NO.

Use this order:

1. HTF context
2. Current range/leg
3. Liquidity
4. POI type
5. POI validity
6. Sweep / liquidity interaction
7. M5 structure
8. CHoC
9. Imbalance
10. Entry model
11. Management

Then state:

- what matches Bailey,
- what does not,
- the first point of divergence,
- whether the rule is high-confidence or still contextual.

When source evidence is insufficient, explicitly say:
"Not enough evidence to make this a hard Bailey rule."

Never invent Bailey quotes or attribute a rule to Bailey unless it is supported by the research material.

---

# XVIII. LEARNING OBJECTIVE

The long-term goal is NOT to make the chart look like Bailey's chart.

The goal is to reproduce the **decision sequence**:

`HTF Context`
→ `Current Trading Range`
→ `Relevant Liquidity`
→ `POI`
→ `Liquidity Interaction`
→ `M5 CHoC`
→ `M5 Imbalance`
→ `Mechanical Entry`
→ `Mechanical 1:3 Management`

The key diagnostic question is:

> "At which decision did my interpretation first diverge from Bailey's?"

That question should drive future backtesting and learning.
