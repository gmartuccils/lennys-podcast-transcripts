# ICE Scoring

**Source:** Sean Ellis (Creator of "Growth Hacking", Former Head of Growth at Dropbox, LogMeIn)
**Best for:** Quickly prioritizing a backlog of ideas and experiments

## Overview

ICE Scoring is a simple prioritization framework that scores ideas on three dimensions: Impact, Confidence, and Ease. Each dimension is rated 1-10, and the scores are multiplied to create a single prioritization number.

The framework's power is its simplicity. In minutes, a team can score dozens of ideas and create a ranked list. It's particularly useful for growth experiments and feature ideas where you have many options and limited resources.

ICE doesn't replace deep strategic thinking, but it's excellent for initial triage and for making prioritization discussions concrete rather than political.

## How It Works

### The Three Dimensions

**Impact (1-10)**
How much will this move the needle if it works?

Questions to ask:
- What metric does this affect?
- How many users will be impacted?
- How significant is the change per user?
- Does this affect a critical part of the funnel?

*10 = Game-changing effect on key metrics*
*5 = Moderate improvement*
*1 = Marginal or uncertain impact*

**Confidence (1-10)**
How sure are we about the impact estimate?

Questions to ask:
- Do we have data supporting this hypothesis?
- Have we seen similar things work elsewhere?
- Is this based on user research or gut feeling?
- How much uncertainty is there?

*10 = Strong evidence, we've seen this work before*
*5 = Reasonable hypothesis, some supporting data*
*1 = Pure guess, no supporting evidence*

**Ease (1-10)**
How quickly and cheaply can we ship this?

Questions to ask:
- How much engineering time?
- Does this require design work?
- Are there dependencies or blockers?
- Can this be done in days or months?

*10 = Can ship in a day, minimal resources*
*5 = A few weeks of work, standard effort*
*1 = Major project, many dependencies*

### The Formula

**ICE Score = Impact × Confidence × Ease**

This creates a single number between 1 and 1,000 that represents the expected return on investment.

### Scoring Process

**Step 1: List all ideas**
Get everything on the table. Don't filter yet.

**Step 2: Score individually first**
Each stakeholder scores independently to avoid anchoring bias.

**Step 3: Compare and discuss**
Where scores differ significantly, discuss why. This surfaces different assumptions.

**Step 4: Finalize scores**
Agree on final scores (or average them).

**Step 5: Rank and prioritize**
Sort by ICE score. The top items are your focus.

**Step 6: Re-score periodically**
As you learn, scores change. Re-score your backlog regularly.

## Example Scoring

| Idea | Impact | Confidence | Ease | ICE Score |
|------|--------|------------|------|-----------|
| Simplify signup form | 8 | 8 | 9 | 576 |
| Add social login | 6 | 7 | 6 | 252 |
| Redesign pricing page | 7 | 4 | 3 | 84 |
| Build referral program | 9 | 5 | 2 | 90 |
| Fix mobile bugs | 5 | 9 | 8 | 360 |
| Add chat support | 4 | 6 | 4 | 96 |

**Prioritization:** Simplify signup form > Fix mobile bugs > Add social login > ...

## When to Use

**ICE is ideal for:**
- Growth experiment prioritization
- Feature backlog triage
- Deciding between many small bets
- Making prioritization discussions objective
- Quick initial sorting before deeper analysis

**ICE is NOT ideal for:**
- Major strategic decisions (too simplistic)
- Comparing very different types of work
- When you have fewer than 5 options
- When confidence is very low across the board

## Common Mistakes

### 1. Scoring inflation
Teams often give everything high scores to justify their pet ideas. Combat this by forcing distribution - require some ideas to be below 5 on each dimension.

### 2. Inconsistent scales
If one person's "8" is another person's "5", scores aren't comparable. Calibrate by scoring a few examples together first.

### 3. Ignoring confidence
High impact × low confidence × high ease should not beat medium impact × high confidence × high ease. The confidence multiplier exists to prevent wishful thinking.

### 4. Treating scores as precise
An ICE score of 320 isn't meaningfully different from 340. The precision is false. Use scores for bucketing (high/medium/low) not exact ranking.

### 5. Not re-scoring
Yesterday's 8 Impact might be today's 5 after you learn more. Re-score regularly as context changes.

### 6. Using ICE for everything
ICE is great for tactical prioritization of similar-sized bets. It's not a substitute for strategy. Don't ICE-score your company's strategic direction.

### 7. Politics in scoring
If scores become a way to justify predetermined conclusions, the framework loses value. Have people score independently first, then discuss differences.

## Variations and Extensions

**RICE Scoring** (Intercom)
Adds "Reach" as a fourth dimension:
- **Reach:** How many users will this affect per quarter?
- **Impact:** How much will it affect each user?
- **Confidence:** How sure are we?
- **Effort:** How much work is required?

Formula: RICE = (Reach × Impact × Confidence) / Effort

**PIE Framework** (Chris Goward)
Similar concept, different dimensions:
- **Potential:** How much improvement is possible?
- **Importance:** How valuable is the traffic/page?
- **Ease:** How hard is the test to run?

**Weighted ICE**
Multiply each dimension by a weight reflecting its importance:
- ICE = (Impact × 2) × (Confidence × 1) × (Ease × 1)

This emphasizes impact over ease.

## Example Application

**Scenario:** Growth team prioritizing Q1 experiments

**Brainstormed ideas:**
1. A/B test pricing tiers
2. Add customer testimonials to landing page
3. Implement exit-intent popup
4. Create onboarding email sequence
5. Add live chat
6. Optimize page load speed
7. Create comparison landing page
8. Add annual billing option

**Team scoring (after discussion):**

| Experiment | Impact | Confidence | Ease | ICE |
|------------|--------|------------|------|-----|
| Onboarding email sequence | 8 | 7 | 7 | 392 |
| Customer testimonials | 6 | 8 | 9 | 432 |
| Page load speed | 5 | 8 | 6 | 240 |
| Exit-intent popup | 4 | 6 | 8 | 192 |
| Annual billing option | 7 | 5 | 5 | 175 |
| Pricing tier A/B test | 8 | 3 | 4 | 96 |
| Live chat | 5 | 5 | 3 | 75 |
| Comparison landing page | 6 | 4 | 3 | 72 |

**Q1 Focus (top 3):**
1. Customer testimonials (432) - Quick win
2. Onboarding email sequence (392) - High impact
3. Page load speed (240) - High confidence

## Key Quotes

> "ICE is not about finding the 'right' priority. It's about making your assumptions explicit so you can have better conversations about priorities."

> "A good ICE process makes disagreements productive. Instead of arguing 'I think we should do X,' you argue 'I think the impact is 7, not 5, because...'

> "Don't let perfect be the enemy of good. A quick ICE score gets you 80% of the way. You can always go deeper on the top candidates."

— Sean Ellis

## Related Frameworks

- [LNO Framework](lno-framework.md) - Categorizes work before ICE scoring
- [Pre-mortems](pre-mortems.md) - Can inform confidence scores
- [North Star Metric](north-star-metric.md) - Impact should tie to North Star

## Further Reading

- **GrowthHackers:** Sean Ellis's writing on ICE scoring
- **Intercom blog:** RICE scoring methodology
- **Amplitude:** "The Definitive Guide to Prioritization Frameworks"
- **Book:** "Hacking Growth" by Sean Ellis
