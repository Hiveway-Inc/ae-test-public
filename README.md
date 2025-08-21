# Agentic Engineering Assessment

## Welcome

**This is not a conventional coding test.**

Welcome to our agentic engineering assessment - an exercise designed to evaluate how effectively you work with AI tools to extract signal from noise and deliver working solutions. We actively encourage what traditional tests would call "cheating": use multiple AI tools, multiple screens, screen recorders, whatever helps you process information effectively. We want to see how you really work.

**Important:** There is no single correct answer to this assessment. The outcome of your final solution will entirely depend on the decisions you make throughout each phase. We're evaluating your ability to use AI to disseminate positive signals from noise, make reasonable decisions when faced with ambiguity, and justify your choices.

**Time Limit:** 45-60 minutes total

**Note on Expectations:** We value quality of thinking over completeness. We'd rather see clear reasoning and good use of AI tools than rushed, complete documents. Focus on demonstrating your process and decision-making  

**Your Mission:** 
You will navigate through three phases:
1. **EXPLORE** - Extract requirements from intentionally messy, contradictory stakeholder communications
2. **PLAN** - Design your technical approach based on what you discovered
3. **EXECUTE** - Build a working Discount Engine Validator

**The Business Context:**
Your company processes e-commerce orders. When customers place orders with coupon codes, the payment processor needs to know the exact amount to charge AFTER discounts are applied. While a hold may be placed for the full amount on the customer's card, the actual charge must reflect the validated discount. Your Discount Engine Validator will determine the final amounts before payment capture.

The challenge: You'll encounter conflicting requirements, evolving decisions, and noise mixed with critical information. Your job is to use AI to efficiently extract what matters and build something that works based on your interpretation.

## Assessment Structure

**Why three phases?** Could you dump all the information into AI and get a working solution in one shot? Perhaps. But that wouldn't demonstrate your business acumen, technical decision-making, or ability to manage complexity across a full development lifecycle. We want to see how you break down problems, translate business needs into technical requirements, and carry decisions through to implementation.

**Important:** Every phase requires a deliverable. Simply place your document in the corresponding phase folder - we care about the content, not the filename or format. Use whatever format works best for you (markdown, text, etc.).

### Phase 1: EXPLORE (15-20 minutes)
Start by reading `1_explore/README.md` for instructions.

You'll find realistic business documentation including meeting transcripts, emails, Slack messages, and JIRA tickets. Your task will be to extract clear requirements from intentionally messy, sometimes contradictory documentation.

**Deliverable:** A comprehensive findings document that captures all requirements from a customer/sales perspective. Think of this as a Statement of Work (SOW) that clearly articulates what needs to be built, the business context, and all functional requirements discovered during exploration.

### Phase 2: PLAN (15-20 minutes)
Read `2_plan/README.md` for instructions.

Based on your extracted requirements, you'll design your technical approach. This phase focuses on the technical implementation details - resolve all ambiguities and open questions, and create a clear technical blueprint. Every decision point should be addressed with your chosen approach (remember: there's no wrong answer, we want to see your reasoning).

**Deliverable:** A Product Requirements Document (PRD) or Technical Implementation Plan. This may include elements such as:
- Technical architecture and data structures
- Algorithms and processing logic
- Edge case handling strategies

Bring your own expertise and include whatever you think is relevant for a solid technical plan. The language you choose, any libraries you decide to use - these decisions are entirely up to you.

### Phase 3: EXECUTE (10-15 minutes)
Read `3_execute/README.md` for instructions and test data.

Transform your exploration findings and technical plan into working code. This should be a straightforward implementation if you've resolved all decisions in the previous phases.

**Deliverable:** An executable script in the `3_execute` directory that:
- Implements the requirements you discovered
- Follows the technical approach you planned
- Processes the provided test data (orders.csv and coupons.json)
- Generates the output files you specified in your plan

This is simply translating your decisions into code - no new requirements or surprises, just execution of your plan.

## How to Succeed
This assessment is designed to test your ability to work effectively with AI tools. Consider:
- How can AI help you navigate conflicting information and extract signal from noise?
- What's the most efficient way to synthesize requirements from multiple, messy sources?
- How do you verify your understanding is correct before moving forward?
- When should you progress to the next phase? This is ultimately your decision - move forward when confident.

You'll have access to your AI tools - use them strategically to explore, understand, and implement the solution. We value candidates who demonstrate intimate knowledge of their chosen AI tools and can leverage them effectively.

## Technical Pre-Setup
- **Repository:** You will be required to clone a public repository to your local machine
- **AI Tools:** Have your AI tools at your disposal throughout the assessment
  - **Note:** If you have token limits, please ensure you haven't exhausted them before the interview.
- **Language:** Your choice - use what you're comfortable with for implementing the solution
- **Libraries:** External packages are allowed (but not required)

## Assumptions
This is a simulated real-world scenario. To keep you focused:
- You're building a standalone validation script, not a full system
- Don't worry about environment variables, configuration files, or deployment
- Focus on the core logic and correctness of the discount calculations
- Assume the script will be run manually with the provided test data
- External integrations (databases, APIs, etc.) are out of scope

## What We're Evaluating

1. **AI Tool Mastery:** How effectively you use AI to deal with overwhelming amounts of information and extract the important pieces. We're looking for strategic, efficient use of AI capabilities.

2. **Business Acumen:** Your ability to apply practical business sense to the information. Where there are open questions or conflicts, we want to see you make reasonable decisions with clear justifications. There's no single right answer - we're interested in your reasoning.

3. **Productivity with AI:** Your ability to deliver a substantial amount of work when empowered with AI tools. We expect to see significant output across all three phases within the time limit.

4. **Technical Understanding:** Your lower-level technical knowledge. To successfully complete this assessment, you need to understand systems, standards, and programming fundamentals. While AI assists you, you still need technical prowess to guide it effectively.