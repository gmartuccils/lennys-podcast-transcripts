# Opportunity Solution Tree

**Source:** Teresa Torres (Product Discovery Coach, Author of "Continuous Discovery Habits")
**Best for:** Structuring discovery work and connecting solutions to outcomes

## Overview

The Opportunity Solution Tree (OST) is a visual framework that maps the path from business outcomes to customer opportunities to potential solutions. It provides structure to product discovery by making explicit the logical connections between what you're trying to achieve, the customer needs you could address, and the solutions you might build.

The power of the OST is that it prevents two common product failures: building solutions that don't connect to real customer needs, and pursuing customer needs that don't ladder up to business outcomes. By visualizing the full tree, teams can see gaps in their thinking and make more intentional choices about where to invest.

The framework also creates a shared artifact that aligns product, design, engineering, and stakeholders around a common understanding of the opportunity space.

## How It Works

### The Tree Structure

```
                    [Desired Outcome]
                           |
            +--------------+--------------+
            |              |              |
      [Opportunity]  [Opportunity]  [Opportunity]
            |              |
       +----+----+    +----+----+
       |         |    |         |
  [Solution] [Solution] [Solution] [Solution]
       |
  +----+----+
  |         |
[Experiment] [Experiment]
```

### Level 1: Desired Outcome
Start with a clear, measurable business outcome. This is what success looks like - typically a metric you're trying to move.

**Good outcomes:**
- "Increase new user activation from 30% to 45%"
- "Reduce churn from 5% to 3% monthly"
- "Increase NPS from 35 to 50"

**Poor outcomes:**
- "Build a better product" (not measurable)
- "Ship feature X" (that's a solution, not an outcome)
- "Make users happy" (too vague)

### Level 2: Opportunities
Opportunities are unmet customer needs, pain points, or desires that, if addressed, would contribute to the desired outcome. These come from customer research - interviews, observations, data analysis.

**What makes a good opportunity:**
- Framed from the customer's perspective
- Specific enough to act on
- Connected logically to the outcome
- Something you discovered through research (not assumed)

**Example opportunities for "Increase activation":**
- "New users don't understand what the product does in first 30 seconds"
- "Users can't find the one feature that would hook them"
- "Setup takes too long and users abandon before seeing value"
- "Users don't know what to do after signing up"

### Level 3: Solutions
For each opportunity, brainstorm multiple potential solutions. The key word is "multiple" - you should have 3+ solutions per opportunity before evaluating any of them.

**Why multiple solutions matter:**
- Your first idea is rarely the best
- Having options enables comparison
- It prevents solution attachment
- It encourages creative thinking

**Example solutions for "Users don't understand what product does":**
- Interactive onboarding tour
- Value-proposition video on landing page
- Personalized "why this matters to you" messaging
- Sample project showing the product in action
- AI-powered "what do you want to accomplish?" router

### Level 4: Experiments (Assumption Tests)
Before building any solution, identify the riskiest assumptions and design small experiments to test them.

**Types of assumptions to test:**
- Desirability: Do customers want this?
- Usability: Can customers use this?
- Feasibility: Can we build this?
- Viability: Does this make business sense?

## Building Your Tree

### Step 1: Set Your Outcome
Work with leadership to define the outcome you're accountable for. Make sure it's:
- Within your influence (not entirely outside your control)
- Measurable in a reasonable timeframe
- Important enough to focus on

### Step 2: Discover Opportunities
Conduct customer research to populate the opportunity layer:
- **Weekly customer interviews** - Talk to users regularly
- **Data analysis** - Where do users struggle? Drop off?
- **Support tickets** - What do customers complain about?
- **Session recordings** - What behavior indicates confusion?

**Important:** Opportunities come from research, not brainstorming. You're discovering what customers actually need, not inventing what you think they need.

### Step 3: Generate Solutions
For each promising opportunity, brainstorm many solutions before evaluating:
- Do individual brainstorming first (avoids groupthink)
- Combine and build on ideas
- Include wild ideas - they can spark better ones
- Aim for quantity before quality

### Step 4: Prioritize and Test
Choose which branch to pursue based on:
- Opportunity size (how many users affected?)
- Solution feasibility (can you build it?)
- Strategic fit (does it align with company direction?)

Then test your riskiest assumptions before building.

## When to Use

**Ideal situations:**
- Starting work on a new outcome/OKR
- Feeling stuck on what to build next
- Team is solution-first instead of problem-first
- Need to align stakeholders on priorities
- Want to visualize the discovery work you've done

**Ongoing use:**
The OST is a living document. Update it as you:
- Learn from customer interviews (add opportunities)
- Brainstorm solutions (add solution branches)
- Validate or invalidate assumptions (prune or expand branches)
- Ship features (mark as shipped, track results)

## Common Mistakes

### 1. Starting with solutions
Many teams start by brainstorming features and then try to retrofit them to opportunities. This is backwards. Always start with the outcome, discover opportunities through research, then generate solutions.

### 2. Too few opportunities
If you only have 2-3 opportunities, you haven't done enough discovery. A rich opportunity space comes from extensive customer research. Keep interviewing until patterns emerge.

### 3. One solution per opportunity
Having only one solution per opportunity means you've fallen in love with your first idea. Force yourself to generate at least 3 solutions before evaluating any.

### 4. Opportunities that are really solutions
"Users need a dashboard" is a solution disguised as an opportunity. The opportunity might be: "Users can't see the status of their projects at a glance."

**Test:** Can you imagine multiple different solutions to this opportunity? If not, it might be a solution in disguise.

### 5. Not connecting to a real outcome
Every OST needs a measurable outcome at the top. Without it, you can't tell if your work matters. "Build great things" isn't an outcome.

### 6. Treating it as a static document
The OST should evolve weekly as you learn. If your tree looks the same as it did a month ago, you're not learning fast enough.

## Example Application

**Outcome:** Increase 7-day retention from 25% to 40%

**Opportunities discovered through research:**
1. "Users sign up but never complete setup" (40% drop-off at step 3)
2. "Users complete setup but don't understand core value prop"
3. "Users return once but don't form a habit"
4. "Users forget about us after first session"

**Solutions for Opportunity #1 (setup drop-off):**
- Reduce setup from 7 steps to 3 steps
- Add progress indicator showing "almost done"
- Allow skipping optional fields
- Pre-fill fields using data we already have
- Send reminder email to incomplete signups

**Assumptions to test for "Reduce to 3 steps":**
- Users will still provide enough info for personalization (desirability)
- We can still deliver value with less setup data (feasibility)
- Completion rate will increase meaningfully (viability)

**Experiment:**
A/B test with 10% of users, measure completion rate and subsequent engagement.

## Key Quotes

> "Most teams are drowning in solutions but starving for opportunities. They have a backlog full of features but no clear view of the customer problems they're solving."

> "An opportunity is something you discover, not something you invent. If you haven't talked to customers, you're guessing at opportunities."

> "The goal isn't to have the best solution. It's to have the best solution for the opportunity you've chosen to address."

> "Your first solution is almost never your best solution. But if you only have one solution, it looks pretty good by comparison."

— Teresa Torres

## Related Frameworks

- [Continuous Discovery Habits](continuous-discovery-habits.md) - The practices that populate the OST
- [Jobs to Be Done](jobs-to-be-done.md) - A complementary way to understand opportunities
- [Pre-mortems](pre-mortems.md) - For testing assumptions about solutions

## Further Reading

- **Book:** "Continuous Discovery Habits" by Teresa Torres
- **Lenny's Podcast:** Teresa Torres episode on product discovery
- **Website:** producttalk.org - Teresa's blog with OST examples and templates
- **Tools:** Miro, FigJam, and others have OST templates
