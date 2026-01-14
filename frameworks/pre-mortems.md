# Pre-mortems

**Source:** Shreyas Doshi (Former PM at Stripe, Twitter, Google, Yahoo)
**Best for:** Risk identification before starting any significant project

## Overview

A pre-mortem is a proactive risk assessment technique where you imagine that your project has already failed spectacularly, then work backwards to identify what could have caused that failure. Unlike a post-mortem (which happens after failure), a pre-mortem happens before work begins, when you still have time to prevent problems.

The power of the pre-mortem lies in its psychological reframing. Instead of asking "what could go wrong?" (which triggers defensive thinking), you ask "what DID go wrong?" This subtle shift unlocks more honest, creative identification of risks because the failure is treated as a given rather than a possibility to defend against.

Shreyas Doshi extends the traditional pre-mortem with a categorization system that helps teams distinguish between different types of risks, ensuring that energy is spent on the threats that actually matter.

## How It Works

### Step 1: Set the Scene
Gather the project team at kickoff. Set a clear timeframe (e.g., "It's six months from now") and declare that the project has failed completely.

### Step 2: Individual Brainstorm (5-10 minutes)
Each person silently writes down all the reasons the project might have failed. Encourage wild ideas - the goal is volume, not precision. Prompts to use:
- "What went wrong?"
- "What did we miss?"
- "What surprised us?"
- "What did we know but ignore?"

### Step 3: Share and Categorize
Go around the room and share items. As you collect them, categorize each into one of three buckets:

**Tigers** 🐅
Real threats that will kill the project if not addressed. These are genuine risks with high probability and high impact. Examples:
- "We don't have the engineering expertise for this technology"
- "Legal hasn't approved this approach and might block us"
- "The key integration partner hasn't committed"

**Paper Tigers** 🐯
Risks that look scary but aren't actually dangerous upon closer examination. Often these are things the team worries about excessively but that won't materially affect outcomes. Examples:
- "Competitor X might launch something similar" (but you have distribution advantage)
- "The technology is unproven" (but similar tech is working elsewhere)
- "Stakeholder Y might not like it" (but they don't have decision authority)

**Elephants** 🐘
Obvious problems that everyone sees but nobody wants to discuss. These are the "elephant in the room" issues - often politically sensitive or uncomfortable truths. Examples:
- "The executive sponsor doesn't actually believe in this project"
- "Our timeline is unrealistic and everyone knows it"
- "The PM and tech lead fundamentally disagree on the approach"

### Step 4: Action Planning
- **For Tigers:** Create immediate mitigation plans. Assign owners. These are non-negotiable.
- **For Paper Tigers:** Explicitly dismiss them. Name them as non-threats so the team stops wasting mental energy.
- **For Elephants:** Name them out loud. The act of acknowledging them often removes their power. Then decide: address it, accept it, or escalate it.

## When to Use

**Ideal situations:**
- Project kickoffs for any initiative lasting more than 2-4 weeks
- Before major strategic decisions
- When launching into uncertain territory
- When the team seems overly optimistic or has groupthink
- After a project pivot or scope change

**Signs you need a pre-mortem:**
- The team is excited but hasn't discussed risks
- There are unspoken concerns people are hinting at
- You've had similar projects fail before
- Key stakeholders aren't aligned
- The timeline feels aggressive but nobody's challenged it

## Common Mistakes

### 1. Not distinguishing between tiger types
Treating all risks the same leads to either paranoia (treating paper tigers as real threats) or complacency (dismissing real tigers). The categorization is essential.

### 2. Skipping the individual brainstorm
If you go straight to group discussion, dominant voices take over and social pressure suppresses honest concerns. The silent writing phase is crucial for surfacing elephants.

### 3. Failing to name paper tigers explicitly
If you don't explicitly call out that something is a paper tiger, people will continue worrying about it. Say out loud: "We've decided competitor X is a paper tiger because..."

### 4. Not addressing elephants
The whole point of identifying elephants is to acknowledge them. If you collect elephants but then don't discuss them, you've made things worse by highlighting what you're avoiding.

### 5. Running it too late
A pre-mortem at project kickoff is great. A pre-mortem three months into a six-month project is a post-mortem in disguise. Run it early.

### 6. Not assigning owners to tigers
Identifying tigers without assigning someone to mitigate them is theater. Every tiger needs an owner and a deadline.

## Example Application

**Scenario:** A B2B SaaS company is launching a new AI-powered feature that requires integration with customer data systems.

**Pre-mortem results:**

*Tigers identified:*
- "Customer IT teams blocked the integration due to security concerns" → **Action:** Schedule security review with top 3 customers before development starts. Owner: PM
- "The ML model accuracy wasn't good enough for enterprise customers" → **Action:** Define minimum accuracy threshold upfront, build evaluation suite. Owner: ML Lead
- "We didn't have enough training data" → **Action:** Audit available data this week. Owner: Data Engineer

*Paper Tigers dismissed:*
- "AWS costs will be too high" → Dismissed: We've modeled this at 10x expected usage and it's within budget
- "Competitor Y has something similar" → Dismissed: Their solution doesn't integrate with the systems our customers use

*Elephants named:*
- "The VP of Sales promised this to customers for Q2, but engineering thinks Q3 is realistic" → **Action:** Have honest conversation with VP Sales this week. Either get Q3 agreement or define cut-down Q2 scope.

## Key Quotes

> "The pre-mortem is one of the highest-leverage activities you can do as a PM. Spending two hours on it can save you months of wasted work."

> "Paper tigers are incredibly common. Teams waste enormous energy worrying about threats that will never materialize while ignoring the real dangers."

> "The elephant is the most important category. If you can get people to name the elephants, you've already solved half the problem."

— Shreyas Doshi

## Related Frameworks

- [LNO Framework](lno-framework.md) - For prioritizing the mitigation work that comes out of a pre-mortem
- [Three Levels of Product Work](three-levels-of-product-work.md) - For understanding how pre-mortems fit into impact-focused work
- [Shape Up](shape-up.md) - The shaping phase serves a similar de-risking function

## Further Reading

- **Lenny's Podcast:** Shreyas Doshi episode on product strategy and PM frameworks
- **Original concept:** Gary Klein's "Performing a Project Premortem" (Harvard Business Review, 2007)
- **Twitter/X:** @shreyas regularly posts about pre-mortems and risk management
