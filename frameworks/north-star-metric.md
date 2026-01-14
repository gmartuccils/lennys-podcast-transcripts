# North Star Metric

**Source:** Gibson Biddle (Former VP Product at Netflix, Chegg)
**Best for:** Aligning entire teams around a single outcome that matters

## Overview

The North Star Metric (NSM) is a single metric that best captures the core value your product delivers to customers. Unlike revenue or vanity metrics, the North Star reflects actual customer value - and predicting long-term business success.

The power of having one North Star is focus. When every team, every decision, every experiment ties back to the same metric, alignment becomes effortless. Without it, different teams optimize for different things, often at cross-purposes.

The North Star isn't about ignoring other metrics - you'll still track many things. It's about having one primary measure that everyone agrees represents success.

## How It Works

### Characteristics of a Good North Star

**1. Reflects customer value delivered**
The NSM should measure value customers receive, not just company revenue. Revenue is an output of delivering customer value.

*Good:* "Weekly active learners completing lessons" (education app)
*Poor:* "Monthly revenue" (doesn't reflect if learners are succeeding)

**2. Predicts long-term business success**
If the NSM goes up, the business should get healthier. If it goes down, there should be trouble ahead.

*Test:* If we doubled this metric, would we be confident the business is thriving?

**3. Measurable and actionable**
The metric must be something you can track and something teams can influence.

*Good:* "Weekly active projects"
*Poor:* "Customer happiness" (hard to measure directly)

**4. Understandable by everyone**
From CEO to new hire, everyone should intuitively understand what the metric means.

*Good:* "Nights booked" (Airbnb)
*Poor:* "Engagement-adjusted revenue per user session"

### Finding Your North Star

**Step 1: Define your product's core value**
What is the main thing customers get from your product?
- Spotify: Music enjoyment
- Airbnb: Unique travel experiences
- Slack: Team communication

**Step 2: How do you measure that value?**
What behavior indicates customers are receiving that value?
- Spotify: Time spent listening
- Airbnb: Nights booked
- Slack: Messages sent

**Step 3: Validate the connection to business outcomes**
Does improvement in this metric correlate with business health (retention, revenue, growth)?

**Step 4: Test for manipulation resistance**
Could teams game this metric in ways that don't create real value?

### The Metric Hierarchy

```
                    [North Star]
                         |
        +----------------+----------------+
        |                |                |
   [Input Metric]  [Input Metric]  [Input Metric]
        |                |                |
   [Features]      [Features]      [Features]
```

**North Star:** The primary outcome (e.g., weekly active users)

**Input Metrics:** Leading indicators that drive the North Star
- Activation rate
- Feature adoption
- Session frequency

**Features:** What you build to move input metrics

Teams can own different input metrics while all pointing toward the same North Star.

## Examples by Industry

| Company | North Star Metric | Why It Works |
|---------|------------------|--------------|
| Airbnb | Nights booked | Represents actual value delivered (travel) |
| Spotify | Time spent listening | Indicates music is satisfying users |
| Facebook | Daily active users | Measures ongoing engagement |
| Slack | Messages sent per workspace | Shows communication happening |
| Netflix | Hours watched | Reflects entertainment value delivered |
| Shopify | Merchant GMV | Success of merchants = platform success |
| Uber | Rides completed | Core value: getting people from A to B |
| Figma | Weekly collaborators per doc | Captures collaboration value |

## When to Use

**You need a North Star when:**
- Teams are working on disconnected goals
- Hard to tell if the product is succeeding
- Leadership can't agree on priorities
- Metrics feel arbitrary or change frequently
- Different parts of the company measure success differently

**Signs your North Star is wrong:**
- Teams can game it without creating real value
- It doesn't move when business health changes
- It doesn't connect to customer value
- No one remembers what it is

## Common Mistakes

### 1. Using revenue as North Star
Revenue is an output, not a driver. Focusing on revenue directly often leads to short-term thinking that damages customer value.

*Better:* Find what drives revenue (engaged users, successful outcomes) and use that.

### 2. Too many North Stars
If you have 5 North Stars, you have none. The whole point is focus. Pick one.

### 3. A North Star that's too lagging
If the metric only moves after 6 months, it's too slow to guide decisions. You need input metrics that lead the North Star.

### 4. Optimizing North Star at expense of other metrics
The North Star shouldn't be optimized by harming things like user trust, profitability, or team health. Set guardrail metrics for things you don't want to damage.

### 5. Set it and forget it
The right North Star can change as the business evolves. Review periodically - is this still the best measure of customer value?

### 6. Teams can't affect it
If teams can't influence the North Star through their work, they'll disengage. Make sure input metrics connect clearly to the North Star.

## Implementing North Star Thinking

### Step 1: Executive alignment
Leadership must agree on one metric. This is harder than it sounds. Use the criteria above to facilitate the debate.

### Step 2: Break down into input metrics
Identify 3-5 input metrics that lead the North Star. Assign these to teams.

### Step 3: Make it visible
Display the North Star prominently. Talk about it in all-hands. Reference it in planning.

### Step 4: Connect decisions to it
In roadmap discussions, ask: "How does this move the North Star?" In experiment reviews, show North Star impact.

### Step 5: Set guardrails
Define metrics you don't want to sacrifice. Revenue, user trust, quality, and team health often serve as guardrails.

### Step 6: Review regularly
Monthly: Are we moving the North Star? Why or why not?
Quarterly: Are input metrics predicting the North Star correctly?
Annually: Is this still the right North Star?

## Example Application

**Scenario:** B2B project management tool selecting North Star

**Option 1:** Monthly active users
- *Pro:* Easy to measure
- *Con:* Doesn't indicate if users get value; could include casual browsers

**Option 2:** Projects completed
- *Pro:* Indicates real work getting done
- *Con:* Might incentivize small projects; doesn't capture ongoing use

**Option 3:** Weekly active projects (projects with activity in last 7 days)
- *Pro:* Shows ongoing value delivery
- *Pro:* Correlates with retention
- *Pro:* Teams can influence through activation and engagement

**Decision:** Weekly active projects

**Input metrics:**
1. New project activation rate (% of new users who create first project)
2. Teammate invitation rate (% of project creators who add others)
3. Weekly project engagement (% of projects with activity)

**Guardrails:**
- NPS > 40
- Churn < 5%
- Gross margin > 70%

## Key Quotes

> "The North Star isn't about having the perfect metric. It's about everyone rowing in the same direction."

> "Revenue is the scoreboard. The North Star is what's happening on the field that determines the score."

> "If your teams are arguing about priorities, you probably don't have a clear North Star - or different teams have different North Stars."

> "The right North Star makes prioritization obvious. If something doesn't move the North Star, why are you doing it?"

— Gibson Biddle

## Related Frameworks

- [Growth Loops](growth-loops.md) - Loops should drive the North Star
- [Three Levels of Product Work](three-levels-of-product-work.md) - Impact level work moves the North Star
- [OKRs](../product-best-practices.md#6-metrics--experimentation) - North Star informs OKR setting

## Further Reading

- **Lenny's Podcast:** Gibson Biddle episodes on product strategy
- **Essay:** "Intro to Product Strategy" by Gibson Biddle
- **Amplitude blog:** "North Star Playbook" - detailed implementation guide
- **Book:** "Measure What Matters" by John Doerr (OKRs complement North Star)
