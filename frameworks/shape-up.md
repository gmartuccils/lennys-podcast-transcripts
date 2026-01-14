# Shape Up

**Source:** Ryan Singer (Former Head of Strategy at Basecamp, Author of "Shape Up")
**Best for:** Planning and executing work in fixed-time cycles with variable scope

## Overview

Shape Up is a product development methodology created at Basecamp that inverts the traditional approach to planning. Instead of estimating how long work will take (fixed scope, variable time), Shape Up sets a fixed time budget and shapes the work to fit within it (fixed time, variable scope).

The methodology addresses common product development dysfunctions: projects that drag on forever, specs that blow up on contact with reality, and teams that can't see the end from the beginning. Shape Up solves these by doing more upfront work on shaping the problem, then giving teams complete autonomy to build within a fixed timeframe.

The key insight: don't ask "how long will this take?" Ask "how much time are we willing to spend?" Then shape a solution that fits.

## How It Works

### The Cycle Structure

Shape Up organizes work into cycles (typically 6 weeks) followed by a 2-week cool-down:

```
[6-Week Cycle] → [2-Week Cool-Down] → [6-Week Cycle] → ...
```

**The Cycle:**
- Teams work on shaped projects
- No interruptions or additions mid-cycle
- Goal: ship something complete

**The Cool-Down:**
- Fix bugs and edge cases
- Explore ideas for future shaping
- No scheduled project work
- Prevents burnout, creates slack

### The Three Phases

**Phase 1: Shaping (Before the cycle)**
Senior people shape raw ideas into projects ready for teams:

1. **Set the appetite:** How much time is this worth? 1 week? 6 weeks?
2. **Narrow the problem:** What specific problem are we solving?
3. **Outline the solution:** What's the approach at a high level?
4. **Address risks:** What could blow up? How do we de-risk?

Output: A "pitch" that describes the problem, solution boundaries, and known risks.

**Phase 2: Betting (Start of cycle)**
Leadership reviews pitches and "bets" on which ones to do:

- No infinite backlog - pitches either get bet on or discarded
- Clear commitment - if bet, team gets full 6 weeks
- No carry-over - if not done by cycle end, it's not automatically continued

**Phase 3: Building (During the cycle)**
Teams have full autonomy to solve the shaped problem:

- No daily standups or detailed tracking from outside
- Team discovers and solves implementation details
- Goal: get to "done" within the cycle

### The Shaping Session

Shaping is the core intellectual work that makes everything else possible. A good shaping session involves:

**Who:** Product person + senior engineer + designer (the "shapers")

**What they do:**
1. **Frame the problem narrowly:** Not "improve calendar" but "help users find open slots quickly"
2. **Sketch rough solutions:** Fat marker drawings, breadboards, not detailed mockups
3. **Find holes:** Senior engineer stress-tests the approach
4. **Identify risks:** What could blow up? What's unknown?
5. **Define boundaries:** What's out of scope?

**Output: A pitch with:**
- Problem statement
- Appetite (time budget)
- Solution sketch (rough enough to allow flexibility)
- Rabbit holes identified (risks to avoid)
- No-gos (explicit out-of-scope items)

### Key Concepts

**Appetite vs. Estimate**
- *Estimate:* "How long will this take?"
- *Appetite:* "How much time is this worth?"

Appetite is a business decision, not a technical prediction. You might want something, but if it's only worth 2 weeks and it would take 6, you don't do it.

**Fat Marker Sketches**
Drawings done at a high level of abstraction - you physically can't add too much detail because the marker is too thick. This forces focus on the structure, not the pixels.

**Breadboarding**
A technique borrowed from electronics: map out the flows and components without any visual design. Just boxes, arrows, and labels showing what connects to what.

**Rabbit Holes**
Risks that could consume unlimited time. Part of shaping is identifying these and either solving them upfront or explicitly excluding them from scope.

**The Hill Chart**
A visual showing where work is in two phases:
- Uphill: Figuring out the approach (uncertainty)
- Downhill: Executing the known approach (certainty)

Work moves from left (unknown) to right (done). If something is stuck uphill, there's still uncertainty to resolve.

## When to Use

**Shape Up works well when:**
- You want more predictable shipping
- Projects tend to drag on past estimates
- Teams feel micromanaged during build
- Leadership spends too much time in details
- You want to give teams more autonomy

**Signs you need better shaping:**
- Projects keep surprising everyone with complexity
- Beautiful Figma files fall apart in engineering
- Teams can't see the end from the beginning
- Specs are either too vague or too detailed
- Engineers ask lots of questions during build

## Common Mistakes

### 1. Shaping too abstract
"Make search better" isn't shaped. Shaped work has a specific problem and a rough solution approach. Teams shouldn't have to figure out what the project even is.

### 2. Shaping too concrete
Detailed mockups and comprehensive PRDs remove team autonomy and miss the point. Shaping provides direction, not specification.

### 3. Not de-risking
The shaping process should surface and address rabbit holes before the cycle starts. If you're discovering fundamental problems during build, shaping failed.

### 4. No real appetite
Saying "take as long as you need" isn't an appetite. Appetite is a constraint that forces prioritization and scope decisions.

### 5. Ignoring the cool-down
Skipping cool-down creates burnout and eliminates the slack needed for fix-up work. The 2 weeks is essential.

### 6. Carry-over as default
If work doesn't finish in a cycle, the default should be to stop and re-shape, not to continue. Automatic carry-over leads to zombie projects.

### 7. Interrupting the cycle
Adding work mid-cycle destroys the fixed-time commitment. Emergencies happen, but they should be rare exceptions.

## Example Application

**Scenario:** Team wants to add a notifications feature

**Bad approach (traditional):**
- Write comprehensive PRD
- Create detailed mockups
- Estimate: "4-6 weeks"
- Work expands to fill time available
- Scope creeps as new cases emerge

**Shape Up approach:**

**Setting appetite:**
Leadership decides: "This is worth 3 weeks maximum. If it takes more than that, we're over-investing."

**Shaping session output:**

*Problem:* Users miss important updates because they don't check the app regularly.

*Appetite:* 3 weeks (small batch)

*Rough solution:*
- Email digest of important events (daily)
- In-app notification center (simple list)
- NOT real-time push notifications (rabbit hole - too complex)
- NOT customizable notification preferences (V2)

*No-gos:*
- Push notifications
- Granular settings
- Notification history beyond 30 days

*Rabbit holes identified:*
- Email deliverability - address by using existing email service
- "Important" definition - define simple rules upfront, don't build ML system

**Result:**
Team ships a complete, working notification system in 3 weeks. It's not everything notifications could be, but it's a complete solution to the core problem.

## Key Quotes

> "Projects don't drag because engineers are slow. They drag because the problem wasn't understood before building started."

> "If you can't see the end from the beginning, you haven't shaped it enough."

> "Appetite is a business decision, not a technical estimate. It's 'how much is this worth' not 'how long will this take.'"

> "A well-shaped project tells the team exactly what to build without telling them how to build it."

> "No backlog. If an idea is important, it'll come back. You don't need to warehouse it."

— Ryan Singer

## Related Frameworks

- [Pre-mortems](pre-mortems.md) - Complements shaping's risk identification
- [LNO Framework](lno-framework.md) - Shaping is Leverage work
- [Empowered Teams](empowered-teams.md) - Shape Up enables empowerment

## Further Reading

- **Book:** "Shape Up" by Ryan Singer (free online at basecamp.com/shapeup)
- **Lenny's Podcast:** Ryan Singer episode on Shape Up
- **Basecamp blog:** Case studies of Shape Up in practice
- **Video:** Ryan Singer's talks on shaping techniques
