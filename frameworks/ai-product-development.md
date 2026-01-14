# AI Product Development

**Source:** Chip Huyen (AI Engineer, Author of "AI Engineering")
**Best for:** Building AI-powered features and products effectively

## Overview

AI Product Development is a framework for building products on top of foundation models (like GPT, Claude, etc.). This is distinct from traditional ML engineering, which focused on training custom models. Modern AI product development is about leveraging existing models and building applications that use them well.

The key insight: most AI applications don't need custom models. Better prompts, retrieval-augmented generation (RAG), and good evaluation systems will get you further than fine-tuning. The hierarchy of AI development starts simple and adds complexity only when needed.

This framework helps teams avoid common mistakes: over-engineering before proving the concept, shipping without evaluation, and jumping to complex solutions before trying simple ones.

## How It Works

### The AI Development Hierarchy

Always try simpler approaches before moving to more complex ones:

```
[Try First]
     ↓
Better Prompts
     ↓
RAG (Retrieval-Augmented Generation)
     ↓
Fine-tuning
     ↓
Custom Models
     ↓
[Try Last]
```

**1. Better Prompts**
Before anything else, optimize your prompts:
- Clearer instructions
- Better examples (few-shot)
- Chain-of-thought reasoning
- Structured outputs

*Most applications can be significantly improved just through prompt engineering.*

**2. RAG (Retrieval-Augmented Generation)**
Connect the model to external data:
- Retrieve relevant documents
- Feed them into the model's context
- Model uses retrieved information to respond

*RAG addresses hallucination by grounding responses in real data.*

**3. Fine-tuning**
Train the model on your specific data:
- Requires high-quality training data
- Expensive and time-consuming
- Results need careful evaluation

*Only fine-tune after prompts and RAG have been exhausted.*

**4. Custom Models**
Build or train from scratch:
- Rarely necessary for most applications
- Requires significant ML expertise
- Reserved for unique, high-value use cases

### The Foundation: Evals

**You cannot improve what you cannot measure.**

Before building AI features, build evaluation systems:

**Types of Evals:**
- **Automated metrics:** Measurable outputs (accuracy, latency, cost)
- **Human evaluation:** Quality judgments by experts
- **User feedback:** Thumbs up/down, corrections
- **Regression tests:** Known inputs with expected outputs

**Eval Process:**
1. Define what "good" looks like
2. Build a test set with labeled examples
3. Run model outputs against test set
4. Measure performance
5. Iterate and re-evaluate

**Without evals:**
- You don't know if prompts are improving
- You ship regressions without noticing
- You can't compare approaches objectively

### The Development Process

**Phase 1: Define the Use Case**
- What task is the AI doing?
- What does success look like?
- What's the cost of errors?

**Phase 2: Build Evals First**
- Create test cases
- Define success metrics
- Build evaluation pipeline

**Phase 3: Start Simple**
- Implement with basic prompts
- Measure against evals
- Iterate on prompts

**Phase 4: Add Complexity (If Needed)**
- If prompts plateau, try RAG
- If RAG plateaus, consider fine-tuning
- Always measure improvement vs. complexity cost

**Phase 5: Ship with Monitoring**
- Monitor quality in production
- Capture feedback for evals
- Iterate based on real-world performance

## When to Use

**AI features make sense when:**
- The task is well-defined but variable (can't hard-code)
- Acceptable error rate exists (imperfect is okay)
- Value exceeds cost of errors
- Traditional programming is impractical

**AI features are risky when:**
- Errors are extremely costly
- Perfect accuracy is required
- The task is too vague to evaluate
- User expectations exceed current capabilities

## Common Mistakes

### 1. Shipping without evals
"It seems to work" is not a quality standard. Without evals, you're guessing.

### 2. Jumping to fine-tuning
Fine-tuning is expensive and often unnecessary. Try prompt optimization and RAG first.

### 3. Underestimating prompt engineering
Teams often give up on prompts too quickly. Weeks of prompt iteration can be more effective than months of fine-tuning.

### 4. Ignoring latency and cost
AI features have real computational costs. A feature that works but costs $10 per user interaction isn't viable.

### 5. No human oversight
AI outputs should have appropriate human review. Fully automated AI without guardrails creates risk.

### 6. Overpromising capabilities
AI has limitations. Setting wrong expectations leads to user disappointment and product failure.

### 7. Static prompts
Prompts should evolve based on eval results and user feedback. Treat prompts as living code, not one-time writing.

## Example Application

**Scenario:** Building an AI-powered customer support assistant

**Phase 1: Define Use Case**
- Task: Answer product questions based on documentation
- Success: 80%+ questions answered correctly without human escalation
- Error cost: Moderate (wrong answer frustrating, not catastrophic)

**Phase 2: Build Evals**
Create test set:
- 100 real customer questions with correct answers
- Categories: pricing, features, troubleshooting, account
- Scoring: Correct, partially correct, incorrect, hallucinated

**Phase 3: Start Simple**
Basic prompt approach:
```
You are a customer support assistant for [Product].
Answer the customer's question based on your knowledge.
Be concise and helpful.
```
*Eval result: 45% correct, 20% hallucinated*

**Phase 4: Iterate on Prompts**
Improved prompt:
```
You are a customer support assistant for [Product].
Answer ONLY if you are confident. If unsure, say "I'm not sure"
and offer to connect them with a human agent.
Be concise. Don't make up information.
```
*Eval result: 52% correct, 5% hallucinated, 30% appropriate "not sure"*

**Phase 5: Add RAG**
- Index product documentation
- Retrieve relevant docs for each question
- Include in context

*Eval result: 78% correct, 2% hallucinated*

**Phase 6: Ship with Monitoring**
- Deploy with human escalation path
- Track user satisfaction ratings
- Feed errors back into eval set
- Iterate monthly

**Result:** 80%+ of inquiries handled, human agents focus on complex cases.

## The AI Product Stack

**Components to consider:**
- **Model selection:** Which foundation model for which task?
- **Prompt management:** Version control for prompts
- **Retrieval system:** Vector database, search
- **Evaluation system:** Automated and human evals
- **Monitoring:** Production quality tracking
- **Feedback loops:** User feedback collection

## Key Quotes

> "Evals are the foundation. You cannot improve what you cannot measure. Build your evaluation system before you build your AI feature."

> "Most applications don't need custom models. Better prompts and RAG will get you further than fine-tuning. Try simple first."

> "AI engineering is a new discipline. It's not ML engineering - it's about building applications on top of foundation models."

> "The prompt is the interface to the model. Treat prompt engineering with the same rigor you'd treat code. Version control it. Test it. Iterate on it."

— Chip Huyen

## Related Frameworks

- [Management Skills for AI](management-skills-for-ai.md) - Team structures for AI work
- [North Star Metric](north-star-metric.md) - AI features should tie to outcomes
- [Shape Up](shape-up.md) - AI work fits well in cycles with clear appetite

## Further Reading

- **Book:** "AI Engineering" by Chip Huyen
- **Lenny's Podcast:** Chip Huyen episode on AI products
- **Course:** AI Engineering courses by Chip Huyen
- **Newsletter:** Chip Huyen's Substack on AI/ML
