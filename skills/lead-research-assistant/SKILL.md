---
name: lead-research-assistant
description: Identifies and qualifies potential business leads by analyzing products/services and matching them with suitable target companies. Helps sales, business development, and marketing professionals find qualified prospects with personalized outreach strategies.
---

# Lead Research Assistant

This skill helps identify and qualify potential business leads by analyzing your product/service and matching it with suitable target companies.

## When to Use This Skill

- Finding potential customers for products/services
- Building partnership prospect lists
- Identifying target accounts for sales outreach
- Researching companies matching ideal customer profiles
- Preparing for business development activities

## What This Skill Does

1. **Business Analysis**: Examines your product/service, value proposition, and target market
2. **Company Identification**: Locates firms matching your ideal customer profile based on industry, size, location, technology stack, growth stage, and pain points
3. **Lead Prioritization**: Ranks companies by fit score (1-10) and relevance
4. **Contact Strategy Development**: Suggests personalized approaches for each lead
5. **Data Enrichment**: Gathers information about decision-makers and company context

## How to Use

### Basic Usage

Describe your product and desired location/industry:

```
Find potential customers for my SaaS analytics platform in the fintech space
```

### Codebase Integration

Run from your source code directory for automatic product analysis:

```
Analyze my codebase and find companies that would benefit from this product
```

### Advanced Usage

Provide detailed ideal customer profile specifications:

```
Find leads matching this profile:
- Industry: Healthcare technology
- Company size: 50-500 employees
- Location: US East Coast
- Pain points: Data integration challenges
- Technology: Currently using legacy systems
```

## Instructions

When a user requests lead research:

### 1. Understand the Product/Service

Gather information about:
- What the product/service does
- Key value proposition
- Target market positioning
- Unique differentiators
- Pricing tier (enterprise, SMB, startup)

If running from a codebase, analyze:
- README files
- Product documentation
- Marketing copy
- Feature lists

### 2. Define Ideal Customer Profile

Clarify target criteria:
- Industry/vertical focus
- Company size (employees, revenue)
- Geographic location
- Technology stack requirements
- Growth stage (startup, scaling, enterprise)
- Pain points being addressed
- Budget indicators

### 3. Research Matching Companies

Search for organizations that match the profile by:
- Industry alignment
- Size requirements
- Location constraints
- Technology usage signals
- Growth indicators (funding, hiring, expansion)

### 4. Identify Need Signals

Look for indicators of immediate need:
- Relevant job postings (hiring for related roles)
- Technology adoption patterns
- Recent news (expansion, new initiatives)
- Competitive product usage
- Pain point mentions in reviews/forums

### 5. Assess Fit and Budget

Evaluate each prospect on:
- Alignment with ideal customer profile
- Timing signals (immediate vs future need)
- Budget availability indicators
- Decision-making structure

### 6. Create Fit Scores

Assign priority scores (1-10) based on:
- Profile alignment (40%)
- Timing/urgency signals (30%)
- Budget indicators (30%)

### 7. Format Actionable Output

For each identified lead, provide:

```markdown
## [Company Name]
**Website**: [URL]
**Fit Score**: [X/10]

### Why They're a Good Fit
[Specific reasons this company matches the ideal customer profile]

### Target Decision Maker
- **Role**: [Title/Department]
- **LinkedIn**: [URL if available]

### Personalized Value Proposition
[How the product specifically solves their challenges]

### Outreach Strategy
[Recommended approach for initial contact]

### Conversation Starters
1. [Opening line referencing their specific situation]
2. [Question about their current challenges]
3. [Value-focused hook]
```

## Output Format

Present results in a structured, actionable format:

```markdown
# Lead Research Results

## Summary
- **Product Analyzed**: [Name/Description]
- **Target Profile**: [Brief description]
- **Leads Identified**: [Number]
- **High Priority (8-10)**: [Number]
- **Medium Priority (5-7)**: [Number]

## High Priority Leads

### 1. [Company Name] - Score: 9/10
[Full details as specified above]

### 2. [Company Name] - Score: 8/10
[Full details]

## Medium Priority Leads

### 3. [Company Name] - Score: 7/10
[Full details]

## Next Steps
1. [Recommended immediate actions]
2. [Follow-up research suggestions]
3. [Outreach sequence recommendations]
```

## Examples

### Example 1: SaaS Product Lead Research

**User**: "Find potential customers for my AI-powered code review tool. We target engineering teams at mid-size tech companies."

**Process**:
1. Analyze the code review tool's value proposition
2. Define profile: Tech companies, 100-1000 employees, active engineering hiring
3. Search for companies with growing engineering teams
4. Identify those using competing/complementary tools
5. Score based on team size, growth signals, tech stack
6. Provide personalized outreach for each

### Example 2: Consulting Services

**User**: "I offer DevOps consulting. Find companies struggling with deployment pipelines in the healthcare sector."

**Process**:
1. Understand DevOps consulting services offered
2. Define profile: Healthcare tech, compliance needs, legacy infrastructure
3. Search for healthcare companies with DevOps job postings
4. Look for signals of infrastructure challenges
5. Score based on urgency and budget indicators
6. Tailor outreach around compliance and reliability

### Example 3: Codebase Analysis

**User**: "Analyze my codebase and find companies that would benefit from this product"

**Process**:
1. Read README, docs, and marketing materials
2. Identify product category and key features
3. Determine ideal customer profile from product design
4. Research matching companies
5. Provide leads with context from product analysis

## Optimization Tips

- **Be specific**: Describe what makes your product unique
- **Run from codebase**: Provides automatic context for product analysis
- **Define clear criteria**: Specify industry, size, location constraints
- **Request depth**: Ask for deeper research on promising prospects
- **Iterate**: Refine search based on initial results

## Related Activities

- Drafting personalized outreach messages
- Building CRM-ready prospect databases
- Conducting detailed company research
- Analyzing competitor customer bases
- Identifying partnership opportunities
- Creating account-based marketing lists

## Best Practices

### For Research Quality
- Verify company information from multiple sources
- Check for recent news and updates
- Validate decision-maker roles on LinkedIn
- Look for timing signals in job postings

### For Outreach Success
- Personalize based on specific company context
- Reference recent company news or initiatives
- Focus on value, not features
- Suggest clear next steps

### For CRM Integration
- Include all relevant contact fields
- Add notes on fit rationale
- Tag by priority score
- Include source URLs for verification
