# The Delight Model

**Source:** Nesrine Changuel (Former PM at Skype, Spotify, Google Chrome, Google Meet; "Delight PM" at Google)
**Best for:** Creating products that users love, not just tolerate

## Overview

The Delight Model is a systematic framework for building products that create genuine emotional connections with users. While most product frameworks focus on functionality and usability, the Delight Model addresses the layer above: making products that users actively enjoy using and recommend to others.

The core insight comes from psychology research: delight is the combination of **joy + surprise**. Based on Professor Robert Plutchik's wheel of emotions, delight emerges when users experience something unexpectedly positive. This means delight requires both an emotional payoff (joy) and an element of unexpectedness (surprise). Products that reliably deliver both create lasting loyalty.

Nesrine Changuel developed this framework through her work at Google, where she held the unique role of "Delight PM" - responsible for identifying and shipping features that went beyond functional requirements to create memorable user experiences. The framework applies equally to B2B and B2C products (she calls this "B2H" - Business to Human), because ultimately all products are used by people who have emotional responses.

## How It Works

### The Three Pillars of Delight

Every delightful feature falls into one of three categories:

**1. Remove Friction**
Eliminate obstacles, annoyances, and unnecessary steps in the user journey. Friction removal is often invisible when done well - users simply notice the absence of frustration.

*Examples:*
- Chrome's inactive tab management (tabs you haven't used fade, reducing visual clutter)
- Auto-saving documents so users never lose work
- One-click checkout instead of multi-page forms
- Pre-filling forms with known information

**2. Anticipate Needs**
Predict what users will need before they explicitly ask for it. This requires deep understanding of user context and behavior patterns.

*Examples:*
- Spotify Discover Weekly - new music recommendations every Monday based on listening habits
- Google Meet's "minimize self-view" - recognizing that seeing yourself is distracting
- Smart suggestions in email (reply suggestions, attachment reminders)
- Revolut's automatic eSIM suggestions when you're traveling internationally

**3. Exceed Expectations**
Deliver more value than users anticipated. This creates the "surprise" component of delight.

*Examples:*
- Uber's automatic refunds for bad rides before you even complain
- Google Meet reactions - emoji reactions during video calls
- Thoughtful empty states that entertain or educate instead of showing blank screens
- Delightful loading animations that make wait times feel shorter

### The Delight Grid

Not all delightful features are created equal. The Delight Grid helps categorize features based on their motivators:

```
                    EMOTIONAL MOTIVATOR
                    Low         High
                ┌───────────┬───────────┐
           High │   LOW     │   DEEP    │
FUNCTIONAL      │  DELIGHT  │  DELIGHT  │
MOTIVATOR       ├───────────┼───────────┤
           Low  │   N/A     │  SURFACE  │
                │ (Don't    │  DELIGHT  │
                │  Build)   │           │
                └───────────┴───────────┘
```

**Low Delight (High Functional, Low Emotional)**
Features users need to get their job done. Essential but not exciting.
- Examples: Search functionality, export features, settings pages
- *These are table stakes - you must have them, but they won't differentiate you.*

**Surface Delight (Low Functional, High Emotional)**
Features that create joy but don't serve a core functional need.
- Examples: Confetti animations, Easter eggs, playful copy, delightful sounds
- *These create memorable moments but shouldn't dominate your roadmap.*

**Deep Delight (High Functional, High Emotional)**
Features that serve a real need AND create emotional resonance. The holy grail.
- Examples: Spotify Discover Weekly (useful + surprising), Uber auto-refunds (solves problem + exceeds expectations)
- *Prioritize these - they're differentiators that users remember and share.*

### The 50-40-10 Model

A guideline for roadmap allocation:

| Type | Allocation | Purpose |
|------|------------|---------|
| Low Delight | 50% | Core functionality users expect |
| Deep Delight | 40% | Differentiating features that create loyalty |
| Surface Delight | 10% | Moments of unexpected joy |

*Don't invert this ratio. A product that's all surface delight without functionality frustrates users. A product with only functional features feels utilitarian and forgettable.*

### The Delight Checklist

Before shipping a delight-focused feature, evaluate it against these criteria:

1. **Inclusion** - Is this accessible to all users? Does it work for diverse contexts?
2. **Familiarity** - Does it use patterns users already understand, or does it require learning?
3. **User Impact** - Does this meaningfully improve the user experience?
4. **Business Impact** - Can we measure the benefit (engagement, retention, NPS)?
5. **Feasibility** - Can we build this within reasonable constraints?

## When to Use

**The Delight Model is valuable when:**
- Your product is functionally complete but retention/NPS is flat
- Competitors have similar features and you need differentiation
- Users describe your product as "fine" or "it works" but not enthusiastically
- You're planning roadmap allocation for a mature product
- You want to create word-of-mouth and organic growth

**Signs your product needs delight focus:**
- High acquisition but low retention
- NPS scores are mediocre (not bad, just unremarkable)
- Users don't recommend you to others
- Competitors are winning on "feel" despite similar functionality
- Your team builds features that test well but don't move metrics

## Common Mistakes

### 1. Surface delight without substance
Adding confetti and animations to a product that doesn't work well. Users see through this quickly and it feels manipulative.

### 2. Copying other products' delight features
What delights in one context falls flat in another. Spotify's Discover Weekly works because music discovery is personal - copying that format for enterprise software rarely succeeds.

### 3. Making delight a phase instead of a practice
"We'll add delight later after the MVP." Delight is most effective when designed in from the start, not bolted on afterward.

### 4. Ignoring context and diversity
A feature delightful for one user segment may confuse or frustrate another. Google Meet's reactions work because video calls are synchronous - the same feature in email would be odd.

### 5. Not measuring delight
Delight features often show up in qualitative metrics (NPS comments, user feedback, social mentions) before quantitative ones. If you only track conversion, you'll miss the signal.

### 6. Overloading on Low Delight features
Building only functional features creates a competent but forgettable product. Users won't complain, but they won't advocate either.

### 7. Removing features users love for "simplification"
Sometimes teams cut delightful small features for "focus." This often damages user sentiment more than expected. Test before removing.

## Example Application

**Scenario:** Improving a B2B project management tool

**Step 1: Assess Current State**
- Users say tool is "functional" and "gets the job done"
- NPS is 32 (decent, not great)
- Feature parity with competitors
- No viral growth or strong referrals

**Step 2: Apply Three Pillars**

*Remove Friction:*
- One-click task creation from Slack
- Auto-archive completed projects after 30 days
- Remember last-used settings for new projects

*Anticipate Needs:*
- Suggest task assignees based on past similar tasks
- Alert when deadline is approaching without progress
- Pre-populate recurring meeting tasks

*Exceed Expectations:*
- Weekly "wins" email showing completed tasks (celebrate progress)
- Automatic status updates to stakeholders without manual reporting
- Project completion celebration with team stats

**Step 3: Categorize on Delight Grid**

| Feature | Category | Priority |
|---------|----------|----------|
| One-click task creation | Deep Delight | High |
| Weekly wins email | Deep Delight | High |
| Project celebration | Surface Delight | Medium |
| Auto-archive | Low Delight | Medium |
| Suggest assignees | Deep Delight | High |

**Step 4: Apply 50-40-10**

Allocate roadmap:
- 50% to core improvements (speed, reliability, integrations)
- 40% to Deep Delight features (one-click creation, suggestions, wins email)
- 10% to Surface Delight (celebrations, fun empty states, micro-animations)

**Result:** After 6 months, NPS improved to 48, organic referrals increased, and users specifically mention "small touches" in feedback.

## Key Quotes

> "Delight is joy plus surprise. It's not enough to make something that works - you need to make something that works in a way that catches people off guard in a good way."

> "B2H - Business to Human. Whether you're building for consumers or enterprises, you're building for people. People have emotions. Your product should acknowledge that."

> "The 50-40-10 rule keeps you honest. If you're spending 80% of your time on surface delight, you're building a theme park, not a product. If you're spending 100% on low delight, you're building a tool people tolerate but don't love."

> "Anticipating needs is where the magic happens. When a product gives you something before you knew you needed it, that's when trust forms. That's when users become advocates."

> "Remove friction first. You can't delight someone who's frustrated. Fix the pain before adding the pleasure."

— Nesrine Changuel

## Related Frameworks

- [Design Excellence Principles](design-excellence-principles.md) - Building craft into every detail
- [First Mile Framework](first-mile-framework.md) - Where delight matters most
- [Founder Mode](founder-mode.md) - Attention to detail enables delight
- [Jobs to Be Done](jobs-to-be-done.md) - Understanding what users really want

## Further Reading

- **Lenny's Podcast:** Nesrine Changuel episode on building delightful products
- **Research:** Robert Plutchik's Wheel of Emotions
- **Book:** "The Design of Everyday Things" by Don Norman (foundations of user experience)
- **Case Study:** Google Meet's delight-focused feature development
