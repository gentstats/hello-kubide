# Business Context Assessment (Step 1)
*Get clear on the why before diving into the how*

## Quick Start (5 Minutes)
If you're in a hurry, answer these 3 critical questions:

1. **What business problem are we solving?** _(one sentence)_
2. **How will we know if we succeed?** _(one measurable outcome)_
3. **What's our biggest constraint?** _(time, budget, skills, or compliance)_

**Based on your constraint, jump to:**
- Time pressure → [Rapid Delivery Track](#rapid-delivery-track)
- Budget constraints → [Cost-Conscious Track](#cost-conscious-track)
- Skills gap → [Team Development Track](#team-development-track)
- Compliance requirements → [Governance Track](#governance-track)

---

## Full Assessment (30 Minutes)

### Core Business Questions
**Complete this in one sitting with key stakeholders present**

#### The Business Case
```
Problem Statement:
[ ] What specific business pain are we addressing?
[ ] Who is experiencing this pain and how often?
[ ] What happens if we don't solve this?

Success Definition:
[ ] Primary success metric (revenue, cost, time, quality)
[ ] Target improvement percentage
[ ] Timeline for achieving results

Constraints:
[ ] Hard deadline (regulatory, competitive, contractual)
[ ] Budget ceiling (not just initial, but total cost of ownership)
[ ] Must-have vs nice-to-have features
```

#### Stakeholder Landscape
```
Decision Makers:
[ ] Who has budget authority?
[ ] Who can kill the project?
[ ] Who defines "done"?

Users:
[ ] Who will use this daily?
[ ] Who will be impacted by changes?
[ ] Who will provide feedback?

Supporters:
[ ] Who will champion this internally?
[ ] Who has relevant expertise?
[ ] Who controls related systems?
```

### Organizational Reality Check

#### Team Assessment
```
Current State:
[ ] Team size and composition
[ ] Skill levels (beginner/intermediate/expert per technology)
[ ] Availability (% time on this project)
[ ] Geographic distribution

Capability Gaps:
[ ] Skills we need but don't have
[ ] Training time required
[ ] External help needed
[ ] Knowledge transfer requirements
```

#### Technical Environment
```
Existing Systems:
[ ] What must we integrate with?
[ ] What can we replace?
[ ] What are the untouchable systems?
[ ] What's the data landscape?

Infrastructure:
[ ] Cloud, on-premise, or hybrid?
[ ] DevOps maturity level
[ ] Security and compliance requirements
[ ] Monitoring and observability tools
```

---

## Context-Based Recommendations

### Rapid Delivery Track
**For: Time-critical projects with clear requirements**

- **Approach**: Start with monolith, optimize later
- **Process**: Kanban with 1-week cycles
- **Quality**: Essential tests only, technical debt tracking
- **Tools**: Whatever the team knows best

### Cost-Conscious Track
**For: Budget-constrained projects**

- **Approach**: Open source first, cloud-native design
- **Process**: Lean methodologies, value stream mapping
- **Quality**: Automated testing to reduce manual QA costs
- **Tools**: Free/low-cost alternatives prioritized

### Team Development Track
**For: Projects that need to build team capabilities**

- **Approach**: Start simple, introduce complexity gradually
- **Process**: Scrum with extended learning time
- **Quality**: Code reviews as learning opportunities
- **Tools**: Industry-standard tools for skill building

### Governance Track
**For: Highly regulated or enterprise environments**

- **Approach**: Architecture-first, compliance by design
- **Process**: Hybrid agile-waterfall with gates
- **Quality**: Extensive documentation and audit trails
- **Tools**: Enterprise-grade with compliance features

---

## Red Flags and Escape Hatches

### When to Stop and Reassess
- Stakeholders can't agree on the problem statement
- Success metrics keep changing
- Key team members are unavailable >50% of time
- Technology constraints make the approach impossible

### Common Traps to Avoid
- **Scope Creep**: Lock down the minimum viable success criteria
- **Technology Resume Padding**: Choose boring technology that works
- **Process Perfectionism**: Good enough processes beat perfect processes never implemented
- **Analysis Paralysis**: Time-box all assessment activities

### Emergency Protocols
If the project becomes critical (customer escalation, regulatory deadline, etc.):
1. Simplify scope to absolute essentials
2. Increase team availability to 80%+
3. Switch to daily stakeholder check-ins
4. Defer all non-critical quality activities

---

## Output: Project Context Card

**Fill this out and keep it visible throughout the project:**

```
PROJECT: [Name]
BUSINESS GOAL: [One sentence]
SUCCESS METRIC: [Number we're trying to move]
PRIMARY CONSTRAINT: [Time/Budget/Skills/Compliance]
APPROACH: [Which track we're following]
TEAM: [Size and key skills]
DEADLINE: [Hard date if any]
BUDGET: [Total available]
```

**Next Steps:**
- Share this card with all team members
- Post it in your workspace/chat
- Reference it in every major decision
- Update it only if business context fundamentally changes

---

## Assessment Templates

### 15-Minute Stakeholder Interview
```
1. What does success look like for you personally?
2. What would failure look like?
3. What's your biggest worry about this project?
4. Who else should we talk to?
5. What decisions do you need to make vs. recommend?
```

### Risk Conversation Starter
```
"Let's assume this project fails spectacularly. Looking back from that failure, what are the most likely reasons it went wrong?"

Common answers and what they tell you:
- "Ran out of time" → Scope is unrealistic
- "Team couldn't deliver" → Skills or capacity issue
- "Requirements changed" → Stakeholder alignment problem
- "Too complex" → Architecture risk
- "Lost support" → Political/budget risk
```

### Technology Readiness Check
```
For each proposed technology:
- How many team members know it well? (0-5 scale)
- How critical is it to success? (0-5 scale)
- How risky is it? (0-5 scale)

High critical + Low knowledge + High risk = Find alternative
High critical + High knowledge + Low risk = Use it
Everything else = Evaluate case by case
```
