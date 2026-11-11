# ICP Framework — Define Your Ideal Customer Profile

A practical framework for defining, validating, and using your Ideal Customer Profile (ICP) in B2B outbound sales.

> Used by the [MachGTM](https://machgtm.com) platform to power AI-driven prospecting for B2B software teams.

---

## What Is an ICP?

Your Ideal Customer Profile (ICP) is a description of the type of company most likely to:
1. Buy your product
2. Achieve value from it
3. Stay and expand

It is **not** a buyer persona (that's the individual). It's the company-level profile.

A good ICP tells you: if you found 1,000 companies matching this description, the majority would be worth pursuing.

---

## The 5-Minute ICP Method

Start here. Answer these five questions.

### 1. Who are your 3 best customers?
Best = highest lifetime value, easiest to sell to, happiest with results.

| Customer | Industry | Employees | Revenue Stage | What problem did they have? |
|----------|----------|-----------|---------------|----------------------------|
| Customer A | | | | |
| Customer B | | | | |
| Customer C | | | | |

### 2. What do they have in common?
Look for patterns:
- Industry overlap
- Size range (employees, revenue)
- Tech stack (what tools do they use?)
- Geography
- Funding stage
- Hiring patterns

### 3. Who is the buyer?
- Title (e.g. VP Sales, CTO, Founder)
- Seniority
- Department
- What are they measured on?

### 4. What was the trigger that made them buy?
- Just received funding?
- Hiring salespeople?
- Lost a deal because of the problem you solve?
- Exec posted about the pain?

### 5. What are 3 negative ICP signals?
Who should you NOT pursue?
- Companies that churn most
- Deals that take too long
- Segments where your product doesn't deliver value

---

## Full ICP Template

```markdown
## Company Profile (Firmographics)
- Industry: [e.g. SaaS, IT Services, AI companies]
- Company size: [e.g. 10-200 employees]
- Revenue stage: [e.g. $2M-$20M ARR / Series A-B]
- Geography: [e.g. US-headquartered, selling to US buyers]
- Growth signal: [e.g. growing 2x YoY, hiring actively]

## Technology Profile (Technographics)
- Uses: [e.g. Salesforce or HubSpot]
- Likely uses: [e.g. Apollo, LinkedIn Sales Navigator]
- Platforms: [e.g. AWS, Azure]

## Buyer Persona
- Primary title: [e.g. VP Sales, Head of Sales, Founder]
- Secondary title: [e.g. CRO, SDR Manager]
- Measured on: [e.g. pipeline generated, new ARR]
- Fears: [e.g. missing quota, ramp time, cost-per-meeting]
- Reads: [e.g. Sales Hacker, Pavilion Slack, Outbound Squad]

## Pain Points
1. [Specific, concrete pain — not "needs to scale"]
2. [Another specific pain]
3. [Another specific pain]

## Buying Signals (Observable Triggers)
- [ ] Hiring SDRs or BDRs
- [ ] Posting on LinkedIn about [pain area]
- [ ] Recent funding (Series A/B)
- [ ] Using a specific tech stack (e.g. Salesforce)
- [ ] [Custom signal specific to your product]

## Proof Points (Match to Their Situation)
- For [segment A]: "[Customer] achieved [result] in [time]"
- For [segment B]: "[Customer] solved [problem] using [approach]"

## Negative ICP (Who to Avoid)
- Companies with fewer than [X] employees
- Industries where you haven't had success: [list]
- Tech stack signals: [tools they use that make them bad fit]
- Behavioral signals: [signs they won't buy or will churn]

## Value Proposition
"We help [ICP description] achieve [outcome] without [pain/effort/cost]."
```

---

## ICP Validation Checklist

Before committing to an ICP, validate it:

- [ ] At least 3 existing customers match it
- [ ] You can find 500+ companies that fit it (not too narrow)
- [ ] You can identify the decision-maker's title consistently
- [ ] You can find observable buying signals (not just "they might need this")
- [ ] Win rate is higher when you stick to it vs. outside it

---

## Using Your ICP in Outreach

### Signal-Based Prospecting
Don't just build a list of ICP companies — find ICP companies showing buying signals.

Example: Instead of "all Series B SaaS companies with 20-100 employees", find "Series B SaaS companies with 20-100 employees that are currently hiring SDRs."

Tools: LinkedIn Sales Navigator + Apollo for signal filtering. [MachGTM](https://machgtm.com) automates this signal detection across LinkedIn, job boards, and funding data.

### ICP-to-Message Connection
Every element of your ICP should map to a message element:
- Pain point → hook or problem statement
- Proof point → social proof
- Buying signal → personalised opener
- Negative ICP → pre-qualifying questions

### ICP Scoring
Score each lead against your ICP (0-100):
- Firmographic match: 0-40 points
- Technographic match: 0-20 points
- Buying signals: 0-30 points
- Decision-maker access: 0-10 points

This proposed weighting is a starting point for your own evaluation. The separate [Mach local helper](https://machgtm.com/blog/mcp-server-sales-prospecting) uses its own published formula and thresholds. Inspect that formula before interpreting a score.

---

## Check fit, intent and buying responsibility

Use the [fit and intent guide](https://machgtm.com/learn/fit-and-intent) to separate company fit from a current request. Build a [buying committee map](https://machgtm.com/resources/buying-committee-map.md) with evidence of each person's responsibility.

The [one-run buying-signal study](https://machgtm.com/blog/buying-signals-one-real-run) shows system grades and the limits of the available human review.

## ICP Evolution

Your ICP should change as you learn:

**Every quarter, review:**
1. Which closed deals matched the ICP? Which didn't?
2. Where's the fastest deal velocity?
3. Where's the highest retention?
4. What new signals correlate with closing?

Update the ICP. Kill the segments that aren't working. Double down on what is.

---

## Tools

| Tool | Use |
|------|-----|
| [MachGTM](https://machgtm.com) | AI builds your ICP from website + case studies, then finds signal-matched prospects |
| [build_icp local helper](https://github.com/verma6uc/mach-gtm-mcp) | Returns a largely fixed example profile with selected supplied inputs. Inspect the result before adapting it. |
| Apollo.io | Filter a lead list by ICP criteria |
| LinkedIn Sales Navigator | Find ICP accounts showing buying signals |
| Clay | Enrich accounts against ICP criteria |

---

## Example ICPs

### Example 1. Illustrative AI outbound platform profile
- Industry: SaaS, IT Services, AI companies
- Size: 10-200 employees
- Geography: US-focused (selling to US buyers)
- Buyer: Founder/CEO, VP Sales, Head of Sales
- Signals: Hiring SDRs, posted about pipeline challenges, Series A/B
- Negative: >500 employees, consumer products, non-English-speaking markets

### Example 2: Code Review Tool
- Industry: SaaS, FinTech, HealthTech
- Size: 20-200 engineers
- Geography: US/Europe
- Buyer: CTO, VP Engineering, Engineering Manager
- Signals: Scaling engineering team rapidly, SOC2 compliance in job posts
- Negative: Agencies (not product companies), <5 engineers

### Example 3: Revenue Intelligence Platform
- Industry: SaaS
- Size: 50-500 employees, $5M-$50M ARR
- Geography: US
- Buyer: VP Sales, CRO, Head of Revenue Operations
- Signals: Using Salesforce + Gong, hiring RevOps roles
- Negative: Transactional/e-commerce, SMB-only motion

---

## Contributing

Open a PR to add example ICPs, improve the framework, or correct anything.

---

*Maintained alongside [MachGTM](https://machgtm.com). The example profiles and weighting are proposed starting points.*
