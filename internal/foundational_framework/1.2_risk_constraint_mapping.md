# Risk & Constraint Mapping (Step 2)
*Identify project killers before they kill your project*

## The Reality of Project Constraints
Most projects fail not because of poor execution, but because teams didn't identify and plan for constraints that were hiding in plain sight. This step surfaces those constraints early when you can still do something about them.

---

## Quick Risk Assessment (15 Minutes)

### The 5 Project Killers
Answer these questions honestly - if any answer is "yes," that's your biggest risk:

1. **Timeline Trap**: Is your deadline set by external forces beyond your control? (regulation, competitor, contract)
2. **Skills Gap**: Do you need capabilities your team doesn't have and can't quickly learn?
3. **Integration Hell**: Must you integrate with systems you don't control or understand?
4. **Budget Reality**: Is your budget based on estimates rather than similar project data?
5. **Stakeholder Chaos**: Do key stakeholders disagree on priorities or requirements?

### Immediate Actions by Risk Type

**Timeline Trap → Scope Management**
- Lock down minimum viable scope immediately
- Identify what can be delivered post-deadline
- Plan phased delivery approach

**Skills Gap → Learning Strategy**
- List exact skills needed vs. current team capabilities
- Estimate learning time required
- Consider external help or training

**Integration Hell → Technical Risk Management**
- Map all integration points and their owners
- Test integration assumptions early
- Build anti-corruption layers and fallback plans

**Budget Reality → Cost Control**
- Get detailed estimates from team leads
- Add 25-50% contingency for unknowns
- Plan regular budget reviews and scope adjustments

**Stakeholder Chaos → Alignment Protocol**
- Identify single decision-maker
- Document all requirements in writing
- Establish change control process

---

## Comprehensive Risk & Constraint Analysis

### Technical Constraints Audit

#### Technology Landscape
```
Current Systems (Must Integrate With):
[ ] System name, owner, documentation quality
[ ] API availability and reliability
[ ] Data formats and protocols
[ ] Performance characteristics
[ ] Maintenance windows and downtime

Legacy Dependencies:
[ ] Outdated technologies that can't be changed
[ ] Vendor lock-ins and licensing constraints
[ ] Data migration requirements
[ ] Compatibility requirements

Infrastructure Limitations:
[ ] Hosting environment constraints
[ ] Network and security policies
[ ] Deployment process restrictions
[ ] Monitoring and logging capabilities
```

#### Technical Debt Assessment
```
Code Quality Issues:
[ ] Technical debt hotspots
[ ] Performance bottlenecks
[ ] Security vulnerabilities
[ ] Documentation gaps

Architecture Constraints:
[ ] Monolithic vs. distributed system trade-offs
[ ] Scalability limitations
[ ] Integration pattern restrictions
[ ] Data consistency requirements
```

### Organizational Constraints

#### Team Capacity Reality Check
```
Team Availability:
[ ] Actual hours per week available for project
[ ] Competing priorities and other commitments
[ ] Vacation and holiday schedules
[ ] Key person dependencies

Skill Distribution:
[ ] Senior vs. junior developer ratio
[ ] Domain expertise availability
[ ] Cross-training needs
[ ] External expertise requirements

Communication Challenges:
[ ] Geographic distribution
[ ] Time zone differences
[ ] Language and cultural considerations
[ ] Remote work effectiveness
```

#### Political and Cultural Factors
```
Organizational Dynamics:
[ ] Change resistance points
[ ] Competing project priorities
[ ] Resource allocation politics
[ ] Success definition conflicts

Cultural Readiness:
[ ] Agile/iterative methodology experience
[ ] Risk tolerance levels
[ ] Decision-making speed
[ ] Collaboration effectiveness
```

### External Constraints

#### Regulatory and Compliance
```
Compliance Requirements:
[ ] Industry regulations (GDPR, HIPAA, SOX, etc.)
[ ] Internal policy requirements
[ ] Audit and documentation needs
[ ] Certification requirements

External Dependencies:
[ ] Vendor software updates
[ ] Third-party service availability
[ ] Customer approval processes
[ ] Partner integration requirements
```

#### Market and Business Environment
```
Competitive Pressure:
[ ] Time-to-market requirements
[ ] Feature parity needs
[ ] Cost pressure points
[ ] Quality expectations

Business Stability:
[ ] Budget availability throughout project
[ ] Organizational changes (mergers, layoffs)
[ ] Strategic priority shifts
[ ] Customer demand changes
```

---

## Risk Impact and Probability Matrix

### Risk Categorization Framework
```
High Impact + High Probability = SHOW STOPPER
- Immediate mitigation required
- Consider alternative approaches
- Get executive sponsorship

High Impact + Low Probability = CONTINGENCY PLAN
- Monitor closely
- Prepare backup plans
- Regular reassessment

Low Impact + High Probability = PROCESS IMPROVEMENT
- Build into standard workflow
- Accept and manage
- Document lessons learned

Low Impact + Low Probability = MONITOR ONLY
- Acknowledge but don't overplan
- Periodic check-ins
- Document for future reference
```

### Risk Assessment Template
```
RISK: [Description]
IMPACT: [High/Medium/Low] - [Specific consequences]
PROBABILITY: [High/Medium/Low] - [Why this might happen]
MITIGATION: [Specific actions to reduce probability]
CONTINGENCY: [What to do if it happens anyway]
OWNER: [Who monitors and responds]
REVIEW DATE: [When to reassess]
```

---

## Constraint-Based Planning Strategies

### Timeline Constraints
**When deadline is fixed (regulatory, competitive, contractual):**

Strategy: Scope Management
- Define absolute minimum viable scope
- Plan incremental delivery post-deadline
- Use feature flags for optional functionality
- Prepare communication plan for stakeholders

Tactics:
- Daily progress tracking
- Weekly scope review meetings
- Automated deployment pipeline
- Parallel development tracks

### Budget Constraints
**When budget is fixed but scope can flex:**

Strategy: Value Maximization
- Prioritize features by business value
- Implement cost-per-feature tracking
- Plan regular scope reassessment
- Focus on sustainable development pace

Tactics:
- Bi-weekly budget burn rate review
- Feature-based cost estimation
- Scope adjustment protocols
- Vendor cost optimization

### Quality Constraints
**When quality requirements are non-negotiable:**

Strategy: Quality-First Development
- Define quality gates upfront
- Implement comprehensive testing strategy
- Plan additional time for quality activities
- Use quality metrics to drive decisions

Tactics:
- Test-driven development practices
- Automated quality checks
- Regular code reviews
- Performance monitoring

### Team Constraints
**When team capabilities are the limiting factor:**

Strategy: Capability Building
- Map skills to requirements
- Plan learning and training time
- Consider external expertise
- Implement knowledge sharing practices

Tactics:
- Pair programming for skill transfer
- Regular technical spike investigations
- External consultant engagement
- Documentation and knowledge base building

---

## Mitigation Strategies Toolkit

### Technical Risk Mitigation

#### Integration Risks
```
Spike Investigations:
- Build minimal integration prototypes
- Test integration assumptions early
- Validate data formats and protocols
- Measure integration performance

Anti-Corruption Patterns:
- Build adapter layers for external systems
- Use circuit breakers for unreliable services
- Implement data validation and cleansing
- Plan for service degradation scenarios
```

#### Performance Risks
```
Early Performance Testing:
- Set performance budgets upfront
- Test with realistic data volumes
- Monitor performance trends continuously
- Plan for capacity scaling

Optimization Strategies:
- Identify performance-critical paths
- Implement caching strategies
- Optimize database queries
- Plan for content delivery optimization
```

### Organizational Risk Mitigation

#### Communication Risks
```
Alignment Protocols:
- Regular stakeholder check-ins
- Written requirement confirmations
- Change control processes
- Escalation procedures

Documentation Strategies:
- Decision logs and rationale
- Meeting notes and action items
- Requirement traceability
- Progress dashboards
```

#### Resource Risks
```
Capacity Management:
- Buffer time in all estimates
- Cross-training for key skills
- Backup resource identification
- Workload balancing strategies

Skill Development:
- Just-in-time learning plans
- Mentoring and pairing programs
- External training investments
- Knowledge sharing sessions
```

---

## Risk Monitoring and Response

### Early Warning Systems
```
Technical Indicators:
- Build failure rates increasing
- Test coverage decreasing
- Performance degrading
- Integration points failing

Process Indicators:
- Sprint velocity declining
- Story completion rates dropping
- Blocked work increasing
- Team satisfaction scores falling

Business Indicators:
- Stakeholder satisfaction declining
- Requirement changes increasing
- Budget burn rate exceeding plan
- Timeline confidence decreasing
```

### Response Protocols
```
Yellow Alert (Minor Risk Increase):
- Increase monitoring frequency
- Implement focused mitigation actions
- Communicate to stakeholders
- Document lessons learned

Red Alert (Major Risk Materialized):
- Activate contingency plans
- Reassess project approach
- Escalate to project sponsors
- Consider scope or timeline adjustments

Crisis Mode (Project Viability Threatened):
- Emergency stakeholder meeting
- Fundamental approach reassessment
- Resource reallocation consideration
- Project continuation decision
```

### Risk Review Cadence
```
Daily (Development Team):
- Technical blocker identification
- Integration issue reporting
- Quality metric review
- Team capacity assessment

Weekly (Project Team):
- Risk register updates
- Mitigation strategy effectiveness
- New risk identification
- Stakeholder communication

Monthly (Stakeholders):
- Overall risk profile assessment
- Business impact evaluation
- Resource allocation review
- Strategic alignment confirmation
```

---

## Templates and Checklists

### Project Risk Register Template
```
PROJECT: [Name]
ASSESSMENT DATE: [Date]
NEXT REVIEW: [Date]

HIGH-IMPACT RISKS:
1. [Risk] - [Mitigation] - [Owner] - [Due Date]
2. [Risk] - [Mitigation] - [Owner] - [Due Date]
3. [Risk] - [Mitigation] - [Owner] - [Due Date]

CONSTRAINTS:
- Timeline: [Fixed/Flexible] - [Details]
- Budget: [Fixed/Flexible] - [Details]
- Scope: [Fixed/Flexible] - [Details]
- Quality: [Non-negotiable requirements]
- Team: [Capacity and skill limitations]

ASSUMPTIONS:
- [Assumption] - [Validation Plan] - [Risk if Wrong]
- [Assumption] - [Validation Plan] - [Risk if Wrong]

DEPENDENCIES:
- [Dependency] - [Owner] - [Required Date] - [Backup Plan]
- [Dependency] - [Owner] - [Required Date] - [Backup Plan]
```

### Risk Assessment Workshop Agenda
```
AGENDA (90 minutes):

Opening (10 minutes):
- Review project context and goals
- Explain risk assessment process
- Set ground rules for discussion

Risk Identification (30 minutes):
- Brainstorm potential risks
- Use constraint categories as prompts
- No evaluation during this phase

Risk Analysis (30 minutes):
- Assess impact and probability
- Identify dependencies between risks
- Categorize using impact/probability matrix

Mitigation Planning (15 minutes):
- Identify mitigation actions for high-impact risks
- Assign owners and due dates
- Plan monitoring approach

Wrap-up (5 minutes):
- Schedule follow-up reviews
- Confirm next steps
- Document and distribute results
```

### Constraint Validation Checklist
```
TECHNICAL CONSTRAINTS:
□ Integration requirements validated with system owners
□ Performance requirements tested with realistic data
□ Security requirements confirmed with security team
□ Infrastructure constraints verified with ops team

ORGANIZATIONAL CONSTRAINTS:
□ Team availability confirmed with resource managers
□ Skill requirements validated with technical leads
□ Budget availability confirmed with finance
□ Timeline feasibility validated with delivery team

EXTERNAL CONSTRAINTS:
□ Regulatory requirements confirmed with compliance team
□ Vendor dependencies validated with vendors
□ Customer requirements confirmed with customer success
□ Market timing validated with business stakeholders
```

---

## Integration with Other Steps

### How Step 2 Connects
```
Step 1 (Business Context) → Identifies constraints
Step 2 (Risk Mapping) → Plans for constraints  
Step 3 (Success Criteria) → Accounts for constraint impact

Risk Assessment → Informs → Approach Selection
Constraint Analysis → Drives → Resource Planning
Mitigation Strategies → Enable → Successful Delivery
```

### Constraint-Driven Decisions
- **High integration risk** → Choose modular architecture with anti-corruption layers
- **Tight timeline** → Prioritize scope flexibility and automated deployment
- **Skills gap** → Plan learning time or external expertise
- **Budget constraints** → Focus on open-source solutions and cloud-native design
- **Quality requirements** → Invest in testing automation and quality gates

---

## Red Flags and Escape Hatches

### When to Stop and Reassess
- Risk register has more than 10 high-impact items
- Mitigation plans require resources not available
- Key constraints conflict (can't optimize for both speed and quality)
- Team confidence in delivery drops below 70%

### Emergency Risk Response
```
If Major Risk Materializes:
1. Stop current work immediately
2. Assess actual impact vs. feared impact
3. Implement emergency mitigation
4. Communicate transparently to stakeholders
5. Revise plans based on new reality
```

### Project Viability Questions
- Are we trying to solve the right problem?
- Do we have the right team for this challenge?
- Is the timeline realistic given constraints?
- Can we deliver meaningful value within constraints?
- Should we pivot approach or pause project?
