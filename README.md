# Academic & Research Projects

Coursework projects from the Faculty of Economics, Thammasat University, spanning applied econometrics, public policy analysis, and business/consumer research.

## 1. Determinants of ATK Test Kit Purchases — Introductory Econometrics (EC325)

**Objective:** Identify which factors affect the monthly quantity of ATK (antigen test kit) purchases, using a multiple regression model.

**Data & Method:** Survey data (n = 78) collected via Google Forms; analyzed with Ordinary Least Squares (OLS) regression in Stata, including a correlation check and a robust-standard-error re-estimation.

**Model:**
```
atk_i = β1 + β2·price_i + β3·fqy_i + β4·seven_i + β5·nasal_i + β6·2in1_i + u_i
```
- `price` — price of the test kit
- `fqy` — frequency of exposure risk
- `seven` — availability through 7-Eleven
- `nasal` — nasal-swab test type
- `2in1` — 2-in-1 test type

**Result:**
```
atk_i = 7.154391 − 0.0547985·price + 1.826338·fqy + 0.179888·seven − 2.056905·nasal − 3.192978·2in1 + u_i
```
A 1-baht increase in price is associated with a 0.0548-unit decrease in average monthly purchase quantity, holding other factors constant. `fqy` (risk exposure frequency) was the strongest positive driver of purchase quantity.

**Tools:** Stata, OLS regression, correlation matrix, robust standard errors

---

## 2. Thailand's Transition into an Aging Society — Public Economics (EC340)

**Objective:** Assess how prepared Thailand is for its transition into a full aged society (60+ population expected to reach ~13 million, roughly 1 in 5 people, by 2024) and identify policy directions from international case studies.

**Approach:** Analyzed the current demographic situation in Thailand, then examined the economic, social, healthcare, and infrastructure impacts of population aging, benchmarked against two case studies:
- **Japan** — extending the retirement age within private-sector companies
- **Iceland** — policies promoting continued social participation among older adults

**Key takeaway:** Aging impacts extend beyond healthcare spending — labor force size, household structure, and public infrastructure planning all need to adapt together, and other countries' policy responses offer a starting reference point for Thailand.

---

## 3. Five Forces Analysis: Starbucks — Business Economics (EC486)

**Objective:** Evaluate Starbucks' competitive position in the Thai coffee market using Porter's Five Forces framework.

**Approach:**
- **Competitive Rivalry** — market share analysis (Starbucks ~21.2% vs. Cafe Amazon ~39.4% in the Thai market) and concentration ratio
- **Threat of New Entry** — barriers facing new competitors
- **Bargaining Power of Buyers** — high, given low switching costs for consumers
- **Bargaining Power of Suppliers** — also high, examined via gross profit margin and accounts-payable turnover trends
- **Threat of Substitution** — alternative beverages (tea, other local drink options) as substitutes

**Key takeaway:** Despite a smaller market share than the leading local competitor, Starbucks' brand loyalty program and premium positioning offset high buyer power — supplier and substitute pressure were identified as the more structurally persistent risks.

---

## 4. Consumer Purchasing Behavior on Live Streaming Platforms — Consumer Behavior (MK311)

**Objective:** Examine what drives purchasing decisions during livestream shopping (TikTok, Shopee Live, Lazada Live), using consumer psychology theory.

**Framework applied:**
- **Perception** — how visuals, sound, and livestream format capture attention
- **Learning** — from others (reviews/comments) and direct experience (past order accuracy/speed)
- **Memory** — what makes a livestream seller memorable to shoppers
- **Motivation** — convenience, price, trust, and fear of missing a deal
- **Emotion & Involvement** — how livestream "fun + atmosphere" drives impulse purchases, especially during flash promotions
- **Attitude** — building trust and brand confidence
- **Personality/Values** — building long-term brand equity

**Key takeaway:** Livestream commerce converts attention into purchases primarily through urgency (flash deals) and parasocial trust in the host — a pattern that differs from traditional e-commerce browsing behavior.
