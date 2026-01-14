# Product Best Practices Reference Guide

A comprehensive reference for AI agents and product practitioners, synthesized from 264+ Lenny's Podcast episodes with leading product experts.

> **Deep Dives Available:** For comprehensive explanations of each framework, see the [/frameworks](frameworks/README.md) folder with detailed 2-3 page guides including examples, common mistakes, and implementation steps.

---

## 1. Product Strategy & Vision

### Core Principles

- **Strategy is about making hard choices** - A real strategy says "no" to good opportunities to focus resources on the best ones. If your strategy doesn't require difficult trade-offs, it's not a strategy.
- **Long-term thinking compounds** - The best product decisions optimize for 10-year outcomes, not quarterly metrics.
- **Vision provides the "why"** - Teams need to understand the destination to make good autonomous decisions along the way.

### Key Frameworks

**[Three Levels of Product Work](frameworks/three-levels-of-product-work.md)** (Shreyas Doshi)
1. **Impact Level**: The actual outcomes your work creates for users and the business
2. **Execution Level**: The quality and efficiency of how you build and ship
3. **Optics Level**: How your work is perceived by stakeholders

*Insight: Most PMs over-index on optics while under-investing in impact. Focus on impact first.*

**[Pre-mortems](frameworks/pre-mortems.md)** (Shreyas Doshi)
Before starting a project, imagine it has failed spectacularly. Identify:
- **Tigers**: Real threats that will kill the project if not addressed
- **Paper Tigers**: Scary-looking risks that aren't actually dangerous
- **Elephants**: Obvious problems everyone sees but nobody discusses

*Action: Run a pre-mortem at project kickoff. Address tigers immediately, dismiss paper tigers explicitly, and name elephants to remove their power.*

### Do's and Don'ts

| Do | Don't |
|---|---|
| Define what you're NOT building | Try to be everything to everyone |
| Revisit strategy quarterly | Set strategy once and forget it |
| Connect daily work to long-term vision | Let teams operate without context |
| Make trade-offs explicit | Pretend you can have everything |
| Communicate strategy repeatedly | Assume one announcement is enough |

### Questions to Ask

- "If this strategy is right, what must be true?"
- "What are we deliberately choosing NOT to do?"
- "How does this decision look in 5 years?"
- "What would have to change for us to abandon this direction?"
- "Who is this NOT for?"

### Sources
- Shreyas Doshi (Former PM at Stripe, Twitter, Google)

---

## 2. Discovery & User Research

### Core Principles

- **Continuous discovery beats periodic research** - Weekly customer touchpoints prevent building products nobody wants.
- **Understand the job, not just the user** - People "hire" products to make progress in specific circumstances.
- **Separate problem space from solution space** - Validate that the problem is worth solving before designing solutions.

### Key Frameworks

**[Opportunity Solution Tree](frameworks/opportunity-solution-tree.md)** (Teresa Torres)

```
        [Desired Outcome]
              |
    +---------+---------+
    |         |         |
[Opportunity] [Opportunity] [Opportunity]
    |              |
+---+---+     +---+---+
|       |     |       |
[Solution] [Solution] [Solution]
```

*Process:*
1. Start with a clear, measurable outcome
2. Map opportunities (unmet needs, pain points, desires) through customer interviews
3. Generate multiple solutions for each opportunity
4. Run assumption tests to de-risk solutions before building

**[Jobs to Be Done (JTBD)](frameworks/jobs-to-be-done.md)** (Bob Moesta)

People don't buy products; they hire them to make progress. The JTBD formula:

**Progress = Struggling Moment + Desired Outcome**

Four forces that influence switching:
1. **Push**: Pain with current situation
2. **Pull**: Attraction of new solution
3. **Anxiety**: Fear of the new (will it work?)
4. **Habit**: Comfort with the current way

*Insight: You need strong push AND pull to overcome anxiety AND habit.*

**JTBD Interview Technique** (Bob Moesta)
- Start from the purchase/decision moment and work backwards
- Ask: "Take me back to when you first thought about this..."
- Dig into context: "Where were you? What time was it? What happened right before?"
- Look for the "struggling moment" that triggered the search
- Understand the "hiring criteria" - what made this solution win?

### [Continuous Discovery Habits](frameworks/continuous-discovery-habits.md) (Teresa Torres)

1. **Weekly customer interviews** - Talk to at least one customer per week
2. **Assumption mapping** - List assumptions behind every opportunity and solution
3. **Small, fast experiments** - Test riskiest assumptions with minimal investment
4. **Story mapping** - Visualize the customer journey to find opportunity gaps

### Do's and Don'ts

| Do | Don't |
|---|---|
| Interview customers weekly | Batch research into quarterly studies |
| Ask about past behavior | Ask hypothetical "would you..." questions |
| Look for struggling moments | Focus only on feature requests |
| Test assumptions before building | Assume your intuition is always right |
| Interview non-customers too | Only talk to happy existing users |
| Map the full context of decisions | Focus only on your product |

### Questions to Ask

- "What were you trying to accomplish when you [action]?"
- "Take me back to when you first started looking for a solution..."
- "What had you tried before? Why didn't that work?"
- "What almost stopped you from choosing this solution?"
- "If you couldn't use our product anymore, what would you do instead?"

### Sources
- Teresa Torres (Author of "Continuous Discovery Habits")
- Bob Moesta (Co-creator of Jobs to Be Done)

---

## 3. Product-Market Fit & Growth

### Core Principles

- **PMF is binary - you either have it or you don't** - If you have to ask if you have product-market fit, you don't.
- **Retention is the only metric that matters early on** - Acquisition without retention is a leaky bucket.
- **Growth comes from product, not just marketing** - The best growth loops are built into the product itself.

### Key Frameworks

**Sean Ellis PMF Test**
Ask users: "How would you feel if you could no longer use this product?"
- **40%+ saying "very disappointed"** = strong PMF signal
- Below 40% = keep iterating before scaling

**The Retention Curve**
A healthy product shows a flattening retention curve, meaning some percentage of users stick around long-term. If retention goes to zero over time, you don't have PMF.

**[Growth Loops](frameworks/growth-loops.md)** (Brian Balfour, Casey Winters)
Unlike funnels (which are linear), growth loops are cyclical:

```
User Action → Output → Input for New Users → User Action...
```

Types of loops:
1. **Viral loops**: Users invite other users (Dropbox referrals)
2. **Content loops**: User-generated content attracts new users (Pinterest)
3. **Paid loops**: Revenue funds acquisition (subscription → ad spend → subscribers)

*Insight: The best companies have multiple reinforcing loops.*

### Do's and Don'ts

| Do | Don't |
|---|---|
| Measure retention by cohort | Look only at aggregate metrics |
| Find your "aha moment" | Assume all users understand value |
| Focus on activation first | Spend on acquisition before activation works |
| Build growth into the product | Rely solely on paid marketing |
| Segment users to find PMF pockets | Assume PMF is uniform across all users |

### Questions to Ask

- "What percentage of users come back after day 1? Day 7? Day 30?"
- "What actions do retained users take that churned users don't?"
- "Where is there natural word-of-mouth happening?"
- "What would make users want to invite others?"
- "Which user segment shows the strongest retention?"

### Sources
- Brian Balfour (Former VP Growth at HubSpot)
- Casey Winters (Former Growth at Pinterest, Grubhub)
- Sean Ellis (Creator of "Growth Hacking")

---

## 4. Prioritization & Decision-Making

### Core Principles

- **Prioritization is about sequencing, not just scoring** - The order matters as much as what makes the list.
- **Saying no is the most important prioritization skill** - Your roadmap is defined as much by what's NOT on it.
- **High-leverage work deserves disproportionate attention** - Not all tasks are created equal.

### Key Frameworks

**[LNO Framework](frameworks/lno-framework.md)** (Shreyas Doshi)
Categorize every task as:
- **Leverage (L)**: High-impact work where quality dramatically affects outcomes. Do these excellently.
- **Neutral (N)**: Work where above-average effort doesn't meaningfully change outcomes. Do these adequately.
- **Overhead (O)**: Necessary work with minimal impact on outcomes. Do these quickly.

*Insight: Most people treat all work as "L" tasks. The best performers deliberately "satisfice" on N and O tasks to invest disproportionately in L tasks.*

**[ICE Scoring](frameworks/ice-scoring.md)**
Score opportunities on three dimensions (1-10 each):
- **Impact**: How much will this move the needle?
- **Confidence**: How sure are we about the impact?
- **Ease**: How quickly can we ship this?

*Multiply scores: ICE = Impact × Confidence × Ease*

**Opportunity Cost Thinking**
For every "yes," ask: "What are we saying no to?" Every resource spent on one thing cannot be spent on another.

### Do's and Don'ts

| Do | Don't |
|---|---|
| Make prioritization criteria explicit | Let the loudest voice win |
| Revisit priorities regularly | Set priorities once per year |
| Kill projects that aren't working | Let zombie projects linger |
| Consider opportunity cost | Evaluate projects in isolation |
| Distinguish reversible from irreversible decisions | Treat all decisions the same |
| Time-box decisions appropriately | Over-analyze low-stakes choices |

### Questions to Ask

- "Is this a Leverage, Neutral, or Overhead task?"
- "What's the opportunity cost of doing this?"
- "Is this decision reversible or irreversible?"
- "What would we have to believe for this to be our top priority?"
- "If we could only ship one thing this quarter, what would it be?"

### Sources
- Shreyas Doshi (Former PM at Stripe, Twitter, Google)

---

## 5. Execution & Shipping

### Core Principles

- **Shipping is a muscle** - Teams that ship frequently ship better.
- **Small batches reduce risk** - Smaller releases mean faster feedback and easier debugging.
- **Appetite, not estimates** - Set a time budget and shape the work to fit, rather than estimating how long work will take.

### Key Frameworks

**[Shape Up](frameworks/shape-up.md)** (Ryan Singer / Basecamp)

Core concepts:
1. **Shaping**: Senior people define the problem and rough solution at the right level of abstraction (not too vague, not too specified)
2. **Appetite**: Set a time budget (1, 2, or 6 weeks) and shape work to fit the appetite
3. **Betting**: Leadership bets on shaped pitches for the next cycle
4. **Building**: Teams have full autonomy during the cycle to solve the shaped problem
5. **Cool-down**: Buffer time between cycles for fixing, exploring, and recovery

*Key insight: Fixed time, variable scope beats fixed scope, variable time.*

**The Shaping Session** (Ryan Singer)

A well-run shaping session produces clarity where an engineer can say "I know what to build now."

Key principles:
- **Bring the right people**: Product person (understands the problem), senior engineer (knows the codebase), and designer - wrestling together
- **Frame the problem first**: Narrow down "calendar" to "seeing empty spaces" before solutioning
- **Fat marker sketches**: Draw rough enough to communicate the idea but not so detailed you can't change it
- **Breadboarding**: Map flows with simple boxes and arrows showing what connects to what
- **Test to break**: Try different approaches and have the technical person find holes
- **Nine boxes max**: If you can't describe implementation in 9 or fewer major chunks, it's not shaped well enough

*When shaping is done right, the team has clarity on both the problem (why) and the approach (how) - but full freedom on implementation details.*

**Signs You Need Better Shaping**:
- Projects keep dragging past deadlines
- Teams can't see the end from the beginning
- Beautiful Figma files blow up on first contact with engineering
- PRDs get written but nobody actually reads them
- Engineers keep coming back with questions during build

**Pitches vs. Backlogs**
- Backlogs grow forever and create guilt
- Pitches are self-contained proposals that either get bet on or discarded
- If an idea is important, it will come back; no need to warehouse it

### Do's and Don'ts

| Do | Don't |
|---|---|
| Ship small, ship often | Wait for the "big release" |
| Set an appetite first | Let scope creep expand timelines |
| Give teams full context and autonomy | Micromanage implementation details |
| Make scope cuts to hit deadlines | Extend timelines repeatedly |
| Celebrate shipped work | Only celebrate perfect work |
| Learn from what you shipped | Plan the next thing without retrospecting |

### Questions to Ask

- "What's our appetite for this problem?"
- "What's the simplest version that solves the core problem?"
- "What can we cut to ship on time?"
- "What did we learn from the last thing we shipped?"
- "Are we shipping to learn or shipping to scale?"

### Sources
- Ryan Singer (Former Head of Strategy at Basecamp, Author of "Shape Up")

---

## 6. Metrics & Experimentation

### Core Principles

- **Measure outcomes, not outputs** - Features shipped is vanity; user behavior changed is sanity.
- **Leading indicators predict; lagging indicators confirm** - Track both, but optimize for leading indicators.
- **Statistical significance requires patience** - Don't call experiments early or you'll fool yourself.

### Key Frameworks

**[North Star Metric](frameworks/north-star-metric.md)**
One metric that:
- Reflects customer value delivered
- Predicts long-term business success
- Aligns the entire company

Examples:
- Airbnb: Nights booked
- Spotify: Time spent listening
- Facebook: Daily active users

*Insight: The North Star should be a leading indicator of revenue, not revenue itself.*

**Input Metrics → North Star → Output Metrics**

```
[Input Metrics]          [North Star]          [Output Metrics]
Sign-ups     →
Activation   →    Active Users    →    Revenue
Engagement   →                         Retention
```

*Focus on the input metrics you can directly influence.*

**Experimentation Principles**
1. **Have a hypothesis**: "We believe [change] will cause [effect] because [reason]"
2. **Define success upfront**: What metric, what threshold, what timeframe?
3. **Wait for significance**: Don't peek and decide early
4. **Consider second-order effects**: A/B tests often miss long-term or ecosystem effects

### Do's and Don'ts

| Do | Don't |
|---|---|
| Define metrics before building | Retrofit metrics to justify decisions |
| Track cohorts, not aggregates | Let averages hide segment differences |
| Run experiments long enough | Call experiments early |
| Instrument everything | Guess at user behavior |
| Look for counter-metrics | Optimize one metric blindly |
| Document experiment learnings | Run and forget |

### Questions to Ask

- "What's our hypothesis and how would we know if it's wrong?"
- "What leading indicators would show this is working?"
- "What could this metric miss?"
- "How long do we need to run this experiment?"
- "What's the counter-metric we should watch?"

### Sources
- Gibson Biddle (Former VP Product at Netflix)
- Casey Winters (Former Growth at Pinterest, Grubhub)

---

## 7. Team & Cross-Functional Leadership

### Core Principles

- **Product is a team sport** - The best products come from true collaboration between product, design, and engineering.
- **Context over control** - Give teams the "why" and let them figure out the "how."
- **Influence without authority** - Product managers lead through alignment, not hierarchy.

### Key Frameworks

**[Empowered Teams](frameworks/empowered-teams.md) vs. Feature Teams** (Marty Cagan)

| Empowered Teams | Feature Teams |
|---|---|
| Given problems to solve | Given features to build |
| Own outcomes | Deliver outputs |
| Have autonomy | Follow instructions |
| Trusted to find solutions | Treated as implementers |

**The PM's Stakeholder Map**
Identify and nurture relationships with:
- Engineering (build partnership, understand constraints)
- Design (collaborate early, respect craft)
- Data (define metrics together, share learnings)
- Leadership (manage up, bring solutions not problems)
- Sales/Support (they hear customer pain directly)

**[Feedback as Daily Practice](frameworks/feedback-as-daily-practice.md)** (Julie Zhuo)

Feedback should happen constantly, not just in performance reviews.

**Establishing feedback culture:**
1. **Opt-in early**: When starting with someone new, establish that you both want to help each other grow
2. **Check your intention**: Only give feedback if genuinely trying to help (not to be right or punish)
3. **Name the difficulty**: "I'm nervous to share this because I value our relationship, but I think it would help you to hear..."

*The best teams get 1% better every week. Feedback is the tool that makes that possible.*

**[Win-Win Thinking](frameworks/win-win-thinking.md)** (Julie Zhuo)

If you're approaching any situation as adversarial (I win, they lose), you're unlikely to succeed.

Examples of reframing:
- **Letting someone go**: Not "I'm hurting them" but "I'm freeing them to find a role where they can succeed"
- **Pushing for productivity**: Not "squeezing more out of people" but "helping them achieve more impact"
- **Giving hard feedback**: Not "criticizing them" but "sharing a gift that helps them grow"

*When things feel adversarial, ask: "How could this be a win for everyone?"*

### Do's and Don'ts

| Do | Don't |
|---|---|
| Include eng & design in discovery | Hand off specs to "implement" |
| Share customer context liberally | Keep insights to yourself |
| Make decisions transparent | Make decisions in private |
| Give credit to the team | Take credit individually |
| Address conflicts directly | Let tensions fester |
| Build relationships before you need them | Only engage when you need something |

### Questions to Ask

- "Does everyone understand WHY we're building this?"
- "Where is there misalignment we're not discussing?"
- "What does success look like for each function?"
- "How can I support each team member's goals?"
- "What context is the team missing?"

### Sources
- Marty Cagan (Author of "Inspired" and "Empowered")
- Julie Zhuo (Former VP Design at Facebook)

---

## 8. Positioning & Go-to-Market

### Core Principles

- **Positioning is context setting** - It tells customers why they should care and how to categorize you.
- **You don't get to pick your competitors** - Customers compare you to their current alternative, not your preferred competitive set.
- **Positioning is not permanent** - As markets evolve, so should your positioning.

### Key Frameworks

**[5 Components of Positioning](frameworks/five-components-of-positioning.md)** (April Dunford)

1. **Competitive Alternatives**: What would customers do if you didn't exist?
2. **Unique Attributes**: What features/capabilities do you have that alternatives lack?
3. **Value**: What benefit do those attributes enable for customers?
4. **Target Customers**: Who cares most about that value?
5. **Market Category**: What context helps customers understand your value fastest?

*Process: Work through these in order. Your competitive alternative determines everything else.*

**[The Sales Pitch Framework](frameworks/sales-pitch-framework.md)** (April Dunford)

Structure your pitch in two phases:

**Phase 1: Setup** (Establish context, not about your product)
1. **Insight**: Your unique point of view on the market/problem ("Customer service is a growth driver for digital businesses, not a cost center")
2. **Alternative approaches**: Walk through pros/cons of other ways to solve this (shared inbox, help desk software, etc.)
3. **Perfect world**: Get agreement on what an ideal solution should deliver ("Can we agree you want X, Y, and Z?")

**Phase 2: Follow-through** (Your differentiated value)
4. **Introduction**: Brief intro of who you are and your market category
5. **Differentiated value**: The bulk of the pitch - show how you deliver what was agreed in "perfect world"
6. **Proof**: Case studies, data, third-party validation that you deliver
7. **Objections**: Handle silent concerns (cost, IT approval, adoption difficulty)
8. **The ask**: What's the next step in the buying process?

*Key insight: Teach customers how to buy. 40-60% of B2B deals end in "no decision" - not because competitors won, but because buyers couldn't confidently choose.*

**[Strategic Narrative](frameworks/strategic-narrative.md)** (Andy Raskin)
Structure your story:
1. Name a relevant change in the world
2. Show there will be winners and losers
3. Tease the promised land (not your product, the outcome)
4. Introduce your approach as the path to the promised land
5. Present evidence you can deliver

*Insight: Lead with the change in the world, not your product.*

**[Bowling Pin Strategy](frameworks/bowling-pin-strategy.md)** (Geoffrey Moore / April Dunford)

The path to market dominance:
1. **Lead pin**: Define a narrow segment underserved by the market leader
2. **Dominate the pin**: Become the obvious choice for that segment
3. **Adjacent pins**: Use that beachhead to expand into neighboring segments
4. **Challenge the leader**: Eventually grow large enough to compete broadly

*Most successful companies follow this pattern - even "category creators" usually started as niche players in existing categories.*

### Do's and Don'ts

| Do | Don't |
|---|---|
| Understand your real competitors | Assume competitors are who you want them to be |
| Position against what customers actually consider | Position against what's convenient |
| Update positioning as market evolves | Treat positioning as permanent |
| Test positioning with customers | Assume internal consensus means market fit |
| Lead with customer outcomes | Lead with features |

### Questions to Ask

- "What would our target customer do if we didn't exist?"
- "What do we do better than any alternative?"
- "What kind of customer cares most about our differentiation?"
- "What market category makes our value obvious?"
- "Is our positioning still true? Has the market changed?"

### Sources
- April Dunford (Author of "Obviously Awesome")
- Andy Raskin (Strategic narrative consultant)

---

## 9. Creating Delightful Products

### Core Principles

- **Details are not details - they make the design** - Excellence is achieved through fanatical attention to every interaction.
- **Functional, then delightful** - A product must work well before it can delight. Delight without function frustrates.
- **Beauty is a feature** - Aesthetic quality affects perceived quality, trust, and willingness to pay.

### Key Frameworks

**[Founder Mode](frameworks/founder-mode.md)** (Brian Chesky / Airbnb)

Core principles:
1. **Be in the details**: CEOs/product leaders should review work deeply, not just get summaries
2. **Single roadmap**: One company roadmap reviewed weekly, not fragmented team roadmaps
3. **Functional model**: Organize by function (design, engineering) not just product areas
4. **Live the product**: Leaders must be power users of their own products
5. **Ship less, better**: Fewer launches with higher quality beats many mediocre releases

*Insight: "World-class results come from world-class effort at every level."*

**[The First Mile](frameworks/first-mile-framework.md)** (Scott Belsky)

The first experience with your product is disproportionately important. Optimize for:
1. **Lazy users**: Minimize effort required to get value
2. **Vain users**: Make users look/feel good immediately
3. **Selfish users**: Deliver clear personal benefit fast

*80% of onboarding effort should go to the first 20% of the experience.*

**[Design Excellence Principles](frameworks/design-excellence-principles.md)** (Katie Dill / Stripe)

1. **Craft at every layer**: From micro-interactions to system architecture
2. **Sweat the details users won't consciously notice**: They affect perception subconsciously
3. **Consistency builds trust**: Design systems and patterns create familiarity
4. **Polish is not optional**: The difference between good and great is finishing touches

**[The Delight Model](frameworks/delight-model.md)** (Nesrine Changuel / Google)

A systematic approach to building products users love, based on the insight that **delight = joy + surprise**.

**Three Pillars of Delight:**
1. **Remove Friction**: Eliminate obstacles and annoyances in the user journey
2. **Anticipate Needs**: Predict what users need before they ask (e.g., Spotify Discover Weekly)
3. **Exceed Expectations**: Deliver more value than anticipated (e.g., Uber auto-refunds)

**The Delight Grid** categorizes features:
- **Low Delight**: High functional, low emotional (table stakes features)
- **Surface Delight**: Low functional, high emotional (confetti, Easter eggs)
- **Deep Delight**: High functional AND high emotional (differentiators users remember)

**50-40-10 Roadmap Allocation:**
- 50% Low Delight (core functionality)
- 40% Deep Delight (differentiating features)
- 10% Surface Delight (moments of joy)

*Insight: "Remove friction first. You can't delight someone who's frustrated."*

### Do's and Don'ts

| Do | Don't |
|---|---|
| Obsess over the first-time experience | Assume users will figure it out |
| Review designs at full fidelity | Approve based on mockups alone |
| Test with real users, not just power users | Only test happy paths |
| Invest in micro-interactions | Treat animations as "polish for later" |
| Make errors helpful and human | Show cryptic error messages |
| Design for emotional response | Focus only on task completion |

### Questions to Ask

- "Would I be proud to show this to the world?"
- "What would make this moment feel magical?"
- "How does this make the user feel?"
- "What's the first 30 seconds like for a new user?"
- "What details have we skipped that users will notice (consciously or not)?"
- "Is this our best work?"

### Sources
- Brian Chesky (CEO of Airbnb)
- Scott Belsky (Chief Product Officer at Adobe, Author of "The Messy Middle")
- Katie Dill (Head of Design at Stripe)
- Nesrine Changuel (Former PM at Skype, Spotify, Google Chrome, Google Meet)

---

## 10. Organizing Product Teams for AI

### Core Principles

- **AI changes the optimal team structure** - Traditional squad models may not be optimal when AI can do significant individual contributor work.
- **Taste and judgment become more valuable** - When AI can execute, humans must provide direction and quality control.
- **Experimentation speed increases dramatically** - AI enables testing more ideas faster, changing the exploration/exploitation balance.
- **Managing AI uses the same skills as managing people** - Clear goals, understanding strengths, providing context, and defining success criteria.

### Key Frameworks

**[AI Product Development Principles](frameworks/ai-product-development.md)** (Chip Huyen)

1. **Evals are the foundation**: You cannot improve what you cannot measure. Build evaluation systems before building AI features.
2. **Prompt engineering before fine-tuning**: Most applications don't need custom models - better prompts and RAG get you far.
3. **AI engineering is a new discipline**: It's not ML engineering. It focuses on building applications on top of foundation models.

**AI Development Hierarchy**:
```
[Try First] Better Prompts → RAG → Fine-tuning → Custom Models [Try Last]
```

**Emerging Team Models for AI**

1. **Smaller, senior teams**: AI handles grunt work; humans provide judgment and creativity
2. **IC + AI pairing**: Individual contributors amplified by AI tools rather than large teams
3. **Quality-first, quantity-second**: With faster execution, competitive advantage shifts to taste and vision
4. **Increased specialization**: Deep expertise in specific AI capabilities (agents, RAG, multi-modal)

**[Management Skills for AI](frameworks/management-skills-for-ai.md)** (Julie Zhuo)

The same fundamentals that make great people managers make great AI managers:

1. **Define outcomes clearly**: Just as teams need clear goals, AI needs crystal-clear success criteria. "What does success look like?" is harder to answer than it seems - different models/people may interpret it differently.

2. **Understand strengths**: Different AI models have different strengths, just like people. Develop intuition for which tool/model fits which task.

3. **Provide context**: The more context you give (to AI or people), the better the output. Don't assume the AI knows what you know.

4. **Process matters**: How you orchestrate tools, people, and AI working together determines outcomes.

**The "Builder" Mindset**
- Dissolve traditional role boundaries (PM, designer, engineer)
- Everyone becomes a "builder" who can do a bit of everything with AI assistance
- Individual output can 2-5x with good AI tooling
- Teams of 2-3 can now do what previously required 8-10

*"If you don't have a PM on the team, communication becomes everyone's responsibility. If you don't have a data analyst, figuring out metrics is everyone's responsibility. This actually makes everyone more well-rounded."*

**AI Integration Questions for Product Teams** (Scott Belsky)

1. Where can AI reduce time-to-value in onboarding?
2. What manual tasks can AI automate for users?
3. How can AI personalize the experience?
4. What "jobs" can AI do that users currently hire your product for?

### Do's and Don'ts

| Do | Don't |
|---|---|
| Build evals before AI features | Ship AI features without measurement |
| Start with prompts, add complexity as needed | Jump to fine-tuning before trying simpler approaches |
| Measure AI output quality systematically | Assume AI output is "good enough" |
| Invest in human oversight for AI | Trust AI outputs without verification |
| Redesign workflows, not just add AI | Bolt AI onto existing processes unchanged |
| Experiment with AI rapidly | Wait for AI to be perfect before shipping |

### Questions to Ask

- "What would our team look like if individual output doubled?"
- "Which tasks should AI do vs. humans verify?"
- "How do we measure AI feature quality?"
- "What new capabilities does AI enable that were previously impossible?"
- "How does AI change our competitive moat?"
- "What human skills become more valuable as AI capabilities increase?"

### Sources
- Chip Huyen (AI Engineer, Author of "AI Engineering")
- Scott Belsky (Chief Product Officer at Adobe)
- Julie Zhuo (Former VP Design at Facebook)

---

## Quick Reference: The Essential Frameworks

| Framework | Use When | Source |
|-----------|----------|--------|
| [**Pre-mortems**](frameworks/pre-mortems.md) | Starting any significant project | Shreyas Doshi |
| [**LNO Framework**](frameworks/lno-framework.md) | Prioritizing tasks and allocating effort | Shreyas Doshi |
| [**Opportunity Solution Tree**](frameworks/opportunity-solution-tree.md) | Planning discovery and ideation | Teresa Torres |
| [**Jobs to Be Done**](frameworks/jobs-to-be-done.md) | Understanding user motivation | Bob Moesta |
| [**Shape Up**](frameworks/shape-up.md) | Planning and executing work | Ryan Singer |
| [**ICE Scoring**](frameworks/ice-scoring.md) | Prioritizing a backlog | Common |
| [**5 Components of Positioning**](frameworks/five-components-of-positioning.md) | Defining go-to-market | April Dunford |
| [**Sales Pitch Framework**](frameworks/sales-pitch-framework.md) | Structuring sales conversations | April Dunford |
| [**Bowling Pin Strategy**](frameworks/bowling-pin-strategy.md) | Market expansion planning | Geoffrey Moore |
| [**North Star Metric**](frameworks/north-star-metric.md) | Aligning team around outcomes | Gibson Biddle |
| [**First Mile Framework**](frameworks/first-mile-framework.md) | Designing onboarding | Scott Belsky |
| [**Founder Mode**](frameworks/founder-mode.md) | Maintaining quality at scale | Brian Chesky |
| [**Delight Model**](frameworks/delight-model.md) | Creating products users love | Nesrine Changuel |
| [**Feedback as Daily Practice**](frameworks/feedback-as-daily-practice.md) | Building high-performance teams | Julie Zhuo |

---

## Applying This Guide

### For AI Agents

When doing product or strategy work, use this guide to:
1. **Identify the right framework** for the problem type
2. **Ask the recommended questions** to gather necessary context
3. **Apply do's and don'ts** to evaluate options
4. **Reference sources** for deeper exploration if needed

### For Product Practitioners

Use this as a:
- **Training resource** for new team members
- **Decision-making reference** during product debates
- **Interview prep** for product management roles
- **Framework catalog** for common product challenges

---

*Document synthesized from 264+ Lenny's Podcast episodes featuring: Shreyas Doshi, Teresa Torres, Bob Moesta, Ryan Singer, April Dunford, Brian Chesky, Scott Belsky, Katie Dill, Chip Huyen, Nesrine Changuel, Marty Cagan, Gibson Biddle, Casey Winters, Julie Zhuo, and many others.*
