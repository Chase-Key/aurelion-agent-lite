# Essential Prompt Library

**Purpose:** 100 proven prompt patterns for maximizing AI collaboration effectiveness  
**Audience:** Knowledge workers using AI as thinking partner (ChatGPT, Claude, GitHub Copilot, etc.)  
**Philosophy:** Better prompts = Better results. Specificity reduces hallucination. Structure ensures completeness.

**How to use this library:**
1. Find the category matching your need
2. Copy the prompt template
3. Replace [placeholders] with your specific context
4. Customize constraints and output format as needed
5. Save effective customizations to your Reference Library

---

## 📊 Navigation by Use Case

| Category | Prompts | Best For | Avg Time |
|----------|---------|----------|----------|
| [Strategic Thinking](#strategic-thinking) | 15 | Planning, decision-making, options analysis | 15-30 min |
| [Research & Analysis](#research--analysis) | 20 | Deep investigation, data validation, root cause | 10-20 min |
| [Writing & Documentation](#writing--documentation) | 15 | Creating docs, improving clarity, formatting | 15-30 min |
| [Problem-Solving](#problem-solving) | 15 | Debugging, optimization, troubleshooting | 10-20 min |
| [Career Development](#career-development) | 10 | Skill gaps, promotion prep, wins translation | 20-30 min |
| [Learning & Understanding](#learning--understanding) | 10 | Explaining concepts, breaking down complexity | 10-15 min |
| [Project Management](#project-management) | 10 | Planning, tracking, risk mgmt, retrospectives | 15-25 min |
| [Session Management](#session-management) | 5 | Starting/ending AI sessions, continuity | 2-5 min |

**Total: 100 essential prompts** (curated from 850+ patterns, FTO-safe universal applicability)

---

## 🎯 Strategic Thinking

### 1. Strategic Options Generator

**When:** Facing significant decision with multiple paths forward

**Prompt:**
```
Generate strategic options for [decision/problem]:

Context: [Current situation]
Constraints: [Limitations - budget, time, resources]
Goal: [Desired outcome]

Generate 5 distinct options:
1. Conservative: [Low risk, proven approach]
2. Moderate: [Balanced risk/reward]
3. Aggressive: [High risk, high reward]
4. Creative: [Outside-the-box thinking]
5. Hybrid: [Combination of above]

For each option provide:
- Pros (3-5 points)
- Cons (3-5 points)
- Resource requirements
- Timeline estimate
- Success likelihood (%)
- Key risks

Rank options by overall recommendation with rationale.
```

---

### 2. Pre-Mortem Analysis

**When:** Planning important project/initiative to identify risks proactively

**Prompt:**
```
Pre-mortem analysis: Assume [project/initiative] failed spectacularly 6 months from now.

Working backward, what went wrong?

Generate 10 failure scenarios:
1. [Failure mode] 
   - Probability: [High/Med/Low]
   - Impact: [High/Med/Low]
   - Warning signs: [How we'd know it's happening]
   - Prevention: [How to avoid]

Continue for scenarios 2-10...

Prioritize by risk (Probability × Impact):
- 🔴 Critical risks (must mitigate)
- 🟡 Moderate risks (monitor)
- 🟢 Low risks (accept)

For each critical risk, provide specific mitigation plan.
```

---

### 3. Goal Decomposition

**When:** Have big goal, need to break into actionable milestones

**Prompt:**
```
Break down this goal into actionable milestones:

Big Goal: [Ultimate objective - 6-12 months out]

Create hierarchical breakdown:
1. **Phase 1 (Month 1-2):** [Foundation work]
   - Milestone 1.1: [Specific deliverable]
   - Milestone 1.2: [Specific deliverable]
   - Success criteria: [How we know Phase 1 is complete]

2. **Phase 2 (Month 3-4):** [Building phase]
   - Milestone 2.1: [Specific deliverable]
   - Milestone 2.2: [Specific deliverable]
   - Success criteria: [How we know Phase 2 is complete]

Continue for remaining phases...

For each milestone:
- Dependencies (what must happen first)
- Estimated effort (hours/days)
- Owner (who's accountable)
- Risk level (low/med/high)

Provide Gantt chart view of timeline.
```

---

### 4. Decision Framework

**When:** Need structured approach to evaluate complex decision

**Prompt:**
```
Create decision framework for [decision type]:

Decision: [What needs to be decided]
Stakeholders: [Who's affected/who decides]
Timeline: [When decision needed]

Evaluation criteria (rank importance 1-5):
1. [Criterion 1 - e.g., cost] - Weight: [X]
2. [Criterion 2 - e.g., time] - Weight: [X]
3. [Criterion 3 - e.g., quality] - Weight: [X]
4. [Criterion 4 - e.g., risk] - Weight: [X]

Options to evaluate:
- Option A: [Description]
- Option B: [Description]
- Option C: [Description]

Create scoring matrix:
| Option | Criterion 1 (score 1-10) | Criterion 2 (score 1-10) | ... | Weighted Total |
|--------|--------------------------|--------------------------|-----|----------------|
| A      |                          |                          |     |                |
| B      |                          |                          |     |                |
| C      |                          |                          |     |                |

Recommendation: [Highest scoring option] because [rationale]
```

---

### 5. SWOT Analysis

**When:** Evaluating strategic position (project, career move, business initiative)

**Prompt:**
```
Conduct SWOT analysis for [situation/initiative]:

**Strengths (Internal, Positive):**
- [What advantages do we have?]
- [What do we do well?]
- [What unique resources/capabilities?]

**Weaknesses (Internal, Negative):**
- [What could we improve?]
- [Where do we lack resources?]
- [What do others do better?]

**Opportunities (External, Positive):**
- [What market/environmental trends favor us?]
- [What gaps can we fill?]
- [What partnerships/synergies exist?]

**Threats (External, Negative):**
- [What obstacles do we face?]
- [What are competitors doing?]
- [What external risks exist?]

Strategic recommendations:
1. **Leverage:** How to use Strengths to capitalize on Opportunities
2. **Improve:** How to address Weaknesses before they become problems
3. **Mitigate:** How to use Strengths to counter Threats
4. **Defend:** How to shore up Weaknesses against Threats
```

---

### 6. Stakeholder Mapping

**When:** Planning communication strategy for initiative with multiple stakeholders

**Prompt:**
```
Map stakeholders for [project/initiative]:

For each stakeholder, analyze:
1. **Name/Role:** [Who they are]
2. **Interest:** [What they care about - High/Med/Low]
3. **Influence:** [Decision-making power - High/Med/Low]
4. **Position:** [Supporter/Neutral/Blocker]
5. **Concerns:** [What worries them]
6. **Communication needs:** [How often, what format, what detail]

Create 2x2 matrix:
- **High Interest, High Influence:** [MANAGE CLOSELY - list names]
- **High Interest, Low Influence:** [KEEP INFORMED - list names]
- **Low Interest, High Influence:** [KEEP SATISFIED - list names]
- **Low Interest, Low Influence:** [MONITOR - list names]

For each "Manage Closely" stakeholder:
- Engagement strategy: [How to involve them]
- Frequency: [How often to communicate]
- Key messages: [What they need to hear]
```

---

### 7. Trade-Off Analysis

**When:** Can't have everything, need to consciously choose what to prioritize

**Prompt:**
```
Analyze trade-offs for [decision/constraints]:

Key dimensions in tension:
1. [Dimension A] vs [Dimension B] (e.g., Speed vs Quality)
2. [Dimension C] vs [Dimension D] (e.g., Cost vs Features)

Current state: [Where we are now on each dimension]
Ideal state: [Where we'd like to be - often impossible]

For each pairing, evaluate:
- **If we optimize for [A]:** [What we gain] + [What we sacrifice]
- **If we optimize for [B]:** [What we gain] + [What we sacrifice]
- **Balanced approach:** [Middle ground option]

Recommendation matrix:
| Scenario | Priority Order | Rationale | Impact on [goal] |
|----------|----------------|-----------|------------------|
| 1        | A > B > C      |           |                  |
| 2        | B > C > A      |           |                  |
| 3        | C > A > B      |           |                  |

Which scenario aligns with strategic goals?
```

---

### 8. Assumption Testing

**When:** Planning based on assumptions that should be validated

**Prompt:**
```
Identify and test assumptions in [plan/strategy]:

Explicit assumptions (stated):
1. [Assumption 1] 
   - How critical? [High/Med/Low]
   - Confidence level? [%]
   - Evidence supporting: [What makes us think this is true]
   - If wrong, impact: [What breaks]
   - How to validate: [Specific test]

Implicit assumptions (unstated but present):
1. [Hidden assumption]
   - How critical? [High/Med/Low]
   - Why we missed it: [Blind spot reason]
   - If wrong, impact: [What breaks]
   - How to validate: [Specific test]

For high-criticality, low-confidence assumptions:
- Validation plan: [Steps to test before proceeding]
- Contingency plan: [What to do if assumption proves false]
```

---

### 9. Retrospective Analysis

**When:** Completed project/initiative, want to extract lessons learned

**Prompt:**
```
Retrospective analysis for [completed project]:

Project summary:
- Duration: [Start - End dates]
- Goal: [What we set out to accomplish]
- Outcome: [What actually happened]
- Success level: [1-10 rating]

**What went well? (Keep doing)**
1. [Specific thing] - Why it worked: [Analysis]
2. [Specific thing] - Why it worked: [Analysis]
3. [Continue for 5-7 items...]

**What went poorly? (Stop doing)**
1. [Specific thing] - Root cause: [Analysis]
2. [Specific thing] - Root cause: [Analysis]
3. [Continue for 5-7 items...]

**What should we try? (Start doing)**
1. [New approach] - Expected benefit: [Analysis]
2. [New approach] - Expected benefit: [Analysis]
3. [Continue for 3-5 items...]

Key lessons (transferable to future projects):
1. [Lesson]
2. [Lesson]
3. [Lesson]

Action items for next project:
- [ ] [Actionable change based on lessons]
- [ ] [Actionable change based on lessons]
```

---

### 10. Priority Matrix

**When:** Have too many competing priorities, need systematic ranking

**Prompt:**
```
Prioritize these items using Eisenhower Matrix:

Items to prioritize:
1. [Task/project 1]
2. [Task/project 2]
3. [Task/project 3]
... [Continue for all items]

For each item, evaluate:
- **Urgency:** [High/Low] - Does this have a deadline? Is it time-sensitive?
- **Importance:** [High/Low] - Does this align with strategic goals? High impact?

Create 2x2 matrix:

**Quadrant 1: Urgent + Important (DO FIRST)**
- [List items that are both urgent AND important]
- Timeline: Immediate action required

**Quadrant 2: Not Urgent + Important (SCHEDULE)**
- [List items that are important but not urgent]
- Timeline: Plan dedicated time

**Quadrant 3: Urgent + Not Important (DELEGATE if possible)**
- [List items that feel urgent but aren't truly important]
- Timeline: Minimize time spent or delegate

**Quadrant 4: Not Urgent + Not Important (ELIMINATE)**
- [List items that are neither urgent nor important]
- Recommendation: Stop doing these

Action plan: Focus 70% of time on Quadrant 2 (strategic), 20% on Q1 (emergencies), 10% on Q3 (tactical).
```

---

### 11. Scenario Planning

**When:** Uncertain future, want to prepare for multiple possibilities

**Prompt:**
```
Create scenario plans for [situation with uncertainty]:

Key uncertainties:
1. [Variable 1] - Could go: [Direction A] or [Direction B]
2. [Variable 2] - Could go: [Direction C] or [Direction D]

Generate 4 scenarios (2x2 matrix of uncertainties):

**Scenario 1: [A + C]**
- What this world looks like: [Description]
- Probability: [%]
- Our strategy in this scenario: [How we'd operate]
- Leading indicators: [How we'd know we're in this scenario]

**Scenario 2: [A + D]**
- What this world looks like: [Description]
- Probability: [%]
- Our strategy in this scenario: [How we'd operate]
- Leading indicators: [How we'd know we're in this scenario]

**Scenario 3: [B + C]**
[Continue pattern...]

**Scenario 4: [B + D]**
[Continue pattern...]

Robust actions (work across all scenarios):
- [Action that's valuable regardless of which scenario unfolds]
- [Action that's valuable regardless of which scenario unfolds]

Contingent actions (scenario-dependent):
- If Scenario 1, then: [Specific action]
- If Scenario 2, then: [Specific action]
```

---

### 12. Value Proposition Design

**When:** Defining what makes offering compelling to audience

**Prompt:**
```
Design value proposition for [product/service/idea]:

**Customer segment:** [Who is this for specifically?]

**Customer jobs:**
- Functional: [What practical tasks are they trying to accomplish?]
- Social: [How do they want to be perceived?]
- Emotional: [How do they want to feel?]

**Customer pains:**
- [What frustrates them?]
- [What's risky or could go wrong?]
- [What's time-consuming or costly?]

**Customer gains:**
- [What would make their life easier?]
- [What outcomes do they want?]
- [What would delight them?]

**Our solution:**
- Products/services: [What we offer]
- Pain relievers: [How we address each pain specifically]
- Gain creators: [How we deliver each gain specifically]

**Value proposition statement:**
"For [customer segment] who [customer job/pain], our [solution] provides [key benefit] unlike [alternative approach] which [limitation we solve]."

**Proof points:**
- [Evidence that our solution delivers value]
- [Testimonial, case study, or data]
```

---

### 13. North Star Metric

**When:** Need single metric to guide decisions and track progress

**Prompt:**
```
Identify North Star Metric for [initiative/team/product]:

Criteria for good North Star:
1. **Reflects core value** delivered to customers
2. **Measurable** (can track numerically)
3. **Actionable** (team can influence it)
4. **Leading indicator** (predicts long-term success)

Candidate metrics:
1. [Metric option 1] - Pros: [X] | Cons: [Y] | Score: [1-10]
2. [Metric option 2] - Pros: [X] | Cons: [Y] | Score: [1-10]
3. [Metric option 3] - Pros: [X] | Cons: [Y] | Score: [1-10]

Recommended North Star: [Chosen metric]

Supporting metrics (track but don't optimize for):
- Input metric: [What drives the North Star]
- Output metric: [What the North Star drives]
- Health metric: [What ensures quality not sacrificed]

Current state: [Where we are now on North Star]
Target: [Where we want to be in 3/6/12 months]
Tracking cadence: [How often to measure]
```

---

### 14. Mental Model Mapping

**When:** Complex situation benefits from explicit framework to think through it

**Prompt:**
```
Apply mental model to [situation]:

Mental model: [e.g., First Principles, Inversion, Second-Order Thinking]

**If using First Principles:**
1. What are the fundamental truths? [Strip away assumptions]
2. What can we rebuild from these truths? [Reconstruct from scratch]
3. What assumptions were we carrying that aren't necessary? [Identify waste]

**If using Inversion:**
1. What would guarantee failure? [Think backwards]
2. What are we currently doing that resembles failure patterns? [Identify risks]
3. What should we explicitly avoid? [Create "stop doing" list]

**If using Second-Order Thinking:**
1. If we do [action], what happens? [First-order effect]
2. And then what happens? [Second-order effect]
3. And then what happens? [Third-order effect]
4. What unintended consequences could emerge? [Long-term thinking]

Insight from applying this mental model:
- [What became clear that wasn't before]
- [What decision changes as a result]
```

---

### 15. Gap Analysis

**When:** Current state doesn't match desired state, need roadmap to close gap

**Prompt:**
```
Gap analysis for [situation]:

**Current State (As-Is):**
- [Describe current reality across key dimensions]
- Strengths: [What's working]
- Weaknesses: [What's not working]
- Metrics: [Current performance numbers]

**Desired State (To-Be):**
- [Describe vision of success]
- Requirements: [What must be true]
- Metrics: [Target performance numbers]

**Gap Identification:**
| Dimension | Current | Desired | Gap | Priority |
|-----------|---------|---------|-----|----------|
| [Dimension 1] | [X] | [Y] | [Y-X] | High/Med/Low |
| [Dimension 2] | [X] | [Y] | [Y-X] | High/Med/Low |
| [Continue...] |  |  |  |  |

**Root Cause of Gap:**
- [Why does gap exist?]
- [What's preventing closure?]

**Bridging Strategy:**
- Initiative 1: [Action to close gap] - Impact: [Expected improvement] - Effort: [Resources needed]
- Initiative 2: [Action to close gap] - Impact: [Expected improvement] - Effort: [Resources needed]

**Roadmap:**
- Phase 1 (0-3 months): [Quick wins to close 30% of gap]
- Phase 2 (3-6 months): [Major initiatives to close next 50%]
- Phase 3 (6-12 months): [Final refinement to reach desired state]
```

---

## 🔍 Research & Analysis

### 16. Root Cause Analysis (5 Whys)

**When:** Problem keeps recurring, need to find underlying cause not just symptoms

**Prompt:**
```
Root cause analysis for [problem]:

**Problem statement:** [Specific, observable issue]
**When it occurs:** [Frequency, timing, conditions]
**Impact:** [Who/what is affected, severity]

**5 Whys:**
1. **Why did [problem] happen?**
   → [Answer - immediate cause]
   
2. **Why [answer from #1]?**
   → [Answer - one level deeper]
   
3. **Why [answer from #2]?**
   → [Answer - getting to systems/processes]
   
4. **Why [answer from #3]?**
   → [Answer - organizational/structural factors]
   
5. **Why [answer from #4]?**
   → [ROOT CAUSE - fundamental issue]

**Validation:** Is this truly the root cause?
- If we fix [root cause], will problem stop recurring? [Yes/No + reasoning]
- Are there multiple root causes? [List if yes]

**Solutions by level:**
- **Immediate fix** (stop the bleeding): [Quick tactical response]
- **Short-term** (prevent recurrence): [Process improvement]
- **Long-term** (systematic solution): [Structural change]

**Preventive measures:**
- Early warning signals: [How we'd detect this emerging in future]
- Monitoring: [What to track to ensure fix worked]
```

---

### 17. Data Validation Framework

**When:** Need to verify data completeness, accuracy, or consistency

**Prompt:**
```
Validate [dataset/file] for quality and completeness:

**Source of truth:** [What is authoritative reference]
**Current data:** [What we're validating]
**Validation date:** [When this check performed]

**Completeness checks:**
1. Record count: Expected [X], Found [Y], Gap: [X-Y]
2. Required fields: [List fields that must be populated] - % filled: [Z%]
3. Date range: Expected [start-end], Found [start-end], Missing: [gaps]
4. Unique identifiers: [Check for duplicates] - Duplicates found: [count]

**Accuracy checks:**
1. Format validation: [Are values in expected format?] - Errors: [count]
2. Range validation: [Are values within expected bounds?] - Outliers: [count]
3. Cross-reference validation: [Do IDs exist in related system?] - Orphans: [count]
4. Business rules: [Are domain-specific rules met?] - Violations: [count]

**Consistency checks:**
1. Internal consistency: [Do related fields agree?] - Conflicts: [count]
2. Historical consistency: [Does this match prior patterns?] - Anomalies: [count]
3. Cross-system consistency: [Does this match other systems?] - Discrepancies: [count]

**Results summary:**
- ✅ Passed: [What validated successfully]
- ⚠️ Warnings: [What's questionable but not critical]
- ❌ Failures: [What must be fixed]
- **Overall confidence level:** [High/Medium/Low] based on [rationale]

**Action items:**
- [ ] [Fix for critical issues]
- [ ] [Investigation for warnings]
```

---

### 18. Comparative Analysis

**When:** Evaluating differences between two things (systems, approaches, time periods)

**Prompt:**
```
Compare [Thing A] vs [Thing B]:

**Comparison dimensions:**

| Dimension | Thing A | Thing B | Difference | Winner | Significance |
|-----------|---------|---------|------------|--------|--------------|
| [Metric 1] | [Value] | [Value] | [Delta] | A/B/Tie | High/Med/Low |
| [Metric 2] | [Value] | [Value] | [Delta] | A/B/Tie | High/Med/Low |
| [Continue for 10-15 dimensions...] |  |  |  |  |  |

**Qualitative factors:**
- **Thing A strengths:** [What it does better]
- **Thing A weaknesses:** [Where it falls short]
- **Thing B strengths:** [What it does better]
- **Thing B weaknesses:** [Where it falls short]

**Context considerations:**
- Use cases where Thing A better: [Scenarios]
- Use cases where Thing B better: [Scenarios]
- Tie scenarios: [When choice doesn't matter]

**Overall recommendation:**
[Which is better overall, or "it depends" with decision criteria]

**Confidence level:** [High/Med/Low] because [rationale]
```

---

### 19. Trend Analysis

**When:** Have time-series data, want to identify patterns and project forward

**Prompt:**
```
Analyze trends in [metric/dataset] over [time period]:

**Data overview:**
- Time period: [Start date] to [End date]
- Data points: [Count]
- Frequency: [Daily/Weekly/Monthly]

**Descriptive statistics:**
- Mean: [Average value]
- Median: [Middle value]
- Standard deviation: [Variability]
- Min/Max: [Range]

**Trend identification:**
1. **Overall direction:** [Increasing/Decreasing/Stable/Volatile]
   - Trend line equation: [If linear: y = mx + b]
   - R² value: [Goodness of fit]

2. **Patterns:**
   - Seasonality: [Do certain periods show consistent patterns?]
   - Cycles: [Any recurring peaks/troughs?]
   - Anomalies: [Dates] with [values] - Likely causes: [Explanation]

3. **Change points:**
   - [Date]: Shift from [pattern] to [pattern] - Cause: [What happened]

**Interpretation:**
- What's driving the trend? [Hypotheses]
- Is this sustainable? [Reasoning]
- What could change trajectory? [Risk factors]

**Projection:**
- If current trend continues: [Forecast next 3-6 months]
- Best case scenario: [Optimistic projection]
- Worst case scenario: [Pessimistic projection]
- Most likely scenario: [Realistic projection]

**Actionable insights:**
- [What decision should be made based on this trend]
- [What to monitor going forward]
```

---

### 20. Correlation Analysis

**When:** Want to understand relationships between variables

**Prompt:**
```
Analyze correlation between [Variable X] and [Variable Y]:

**Hypothesis:** [What relationship do we expect to see?]

**Data:**
- Sample size: [N]
- Time period: [When data collected]
- Data source: [Where it came from]

**Scatter plot description:**
- Pattern: [Linear/Non-linear/No pattern]
- Direction: [Positive/Negative/No correlation]
- Strength: [How tightly clustered around trend line?]

**Correlation coefficient:**
- r = [Value between -1 and 1]
- Interpretation: 
  - If r > 0.7: Strong positive correlation
  - If r = 0.3-0.7: Moderate positive correlation
  - If r < 0.3: Weak/no correlation
  - [Negative values = inverse relationship]

**Statistical significance:**
- p-value: [Is this correlation likely due to chance?]
- Confidence: [Can we trust this finding?]

**Causation analysis:**
- **Correlation does NOT equal causation**
- Possible explanations:
  1. X causes Y: [Mechanism if true]
  2. Y causes X: [Mechanism if true]
  3. Third factor Z causes both: [What could Z be?]
  4. Coincidence: [Is this just random?]

**Most likely explanation:** [Which causal story makes most sense]

**Action items:**
- [What decision or experiment should follow from this analysis]
```

---

### 21. Segmentation Analysis

**When:** Have population, want to break into meaningful groups

**Prompt:**
```
Segment [population] into meaningful groups:

**Segmentation variables:**
1. [Variable 1] - e.g., behavior, demographics, firmographics
2. [Variable 2]
3. [Variable 3]

**Proposed segments:**

**Segment 1: [Name]**
- Size: [% of total population]
- Defining characteristics: [What makes them unique]
- Typical profile: [Description of archetypical member]
- Key needs: [What they care about]
- Current performance: [Metrics for this segment]

**Segment 2: [Name]**
[Repeat pattern for3-5 segments...]

**Segment comparison:**
| Metric | Segment 1 | Segment 2 | Segment 3 | Overall |
|--------|-----------|-----------|-----------|---------|
| [Metric 1] | [Value] | [Value] | [Value] | [Avg] |
| [Metric 2] | [Value] | [Value] | [Value] | [Avg] |

**Insights:**
- Which segment is highest value? [Name + why]
- Which segment is underserved? [Name + opportunity]
- Which segment is declining? [Name + concern]

**Recommendations:**
- Segment 1: [Specific strategy for this group]
- Segment 2: [Specific strategy for this group]
- Segment 3: [Specific strategy for this group]
```

---

### 22. Benchmarking Analysis

**When:** Want to compare performance to standards/competitors/best practices

**Prompt:**
```
Benchmark [our performance] against [comparison group]:

**Metrics to benchmark:**

| Metric | Our Performance | Industry Average | Top Performer | Gap to Average | Gap to Best |
|--------|----------------|------------------|---------------|----------------|-------------|
| [Metric 1] | [Value] | [Value] | [Value] | [Delta] | [Delta] |
| [Metric 2] | [Value] | [Value] | [Value] | [Delta] | [Delta] |
| [Continue for key metrics...] |  |  |  |  |  |

**Performance assessment:**
- Where we excel: [Metrics where we beat industry average]
- Where we're average: [Metrics where we match industry]
- Where we lag: [Metrics where we underperform]

**Root cause of gaps:**
For each underperforming metric:
- [Metric]: Gap exists because [reason] - To close gap: [action]

**Best practice analysis:**
- What is top performer doing differently? [Practices to emulate]
- What is feasible for us to adopt? [Realistic improvements]
- What is not applicable to our context? [Why certain practices won't transfer]

**Improvement roadmap:**
- Quick wins (0-3 months): [Actions to close 30% of gap]
- Medium-term (3-6 months): [Actions to reach industry average]
- Long-term (6-12 months): [Actions to become top performer]
```

---

### 23. Survey Design & Analysis

**When:** Need to gather structured feedback from group

**Prompt:**
```
Design survey to answer [research question]:

**Research objectives:**
1. [What do we need to learn?]
2. [What decision will this inform?]

**Target audience:** [Who should respond]
**Sample size needed:** [How many responses for statistical significance]

**Survey structure:**

**Section 1: [Topic]**
1. [Question text]
   - Type: [Multiple choice/Rating scale/Open-ended]
   - Options: [If applicable]
   - Why asking: [What this tells us]

2. [Question text]
   [Continue for 10-15 questions total...]

**Section 2: Demographics** (for segmentation)
- [Relevant demographic questions]

**Survey best practices checklist:**
- [ ] Questions are clear and unambiguous
- [ ] No leading or biased questions
- [ ] Logical flow (general → specific)
- [ ] Mix of question types
- [ ] Takes <10 minutes to complete
- [ ] Includes progress bar
- [ ] Has clear call-to-action

**Analysis plan:**
Once responses collected:
1. Calculate response rate: [Responses / Invitations]
2. Segment analysis: [Break down by demographic groups]
3. Key findings: [What patterns emerge]
4. Visualizations: [What charts to create]
5. Actions: [What to do with insights]
```

---

### 24. Hypothesis Testing

**When:** Have theory about cause/effect, want to validate rigorously

**Prompt:**
```
Design test for hypothesis:

**Hypothesis:** [Specific, testable prediction]
- Example: "If we do X, then Y will happen because Z"

**Null hypothesis:** [The opposite - what we're trying to disprove]

**Variables:**
- Independent variable (what we change): [X]
- Dependent variable (what we measure): [Y]
- Control variables (what we hold constant): [List]

**Experiment design:**
- **Control group:** [Baseline - no intervention]
- **Treatment group:** [Gets the intervention]
- **Sample size:** [How many in each group - need power analysis]
- **Duration:** [How long to run experiment]
- **Randomization:** [How to assign to groups fairly]

**Success metrics:**
- Primary metric: [Main thing we're measuring]
- Secondary metrics: [Other things to track]
- Guardrail metrics: [Things that shouldn't get worse]

**Analysis plan:**
- What result would prove hypothesis? [Specific threshold]
- What result would disprove hypothesis? [Specific threshold]
- What result would be inconclusive? [Gray area]

**Predicted outcome:** [What we expect to find]
**Alternative explanations:** [What else could explain results]
**Risks:** [What could go wrong with experiment]
```

---

### 25. Literature Review

**When:** Researching topic, want to synthesize existing knowledge

**Prompt:**
```
Synthesize literature on [topic]:

**Research question:** [What are we trying to understand?]

**Sources reviewed:**
1. [Source 1 - author, title, year]
2. [Source 2]
... [List 10-20 sources]

**Key themes:**

**Theme 1: [Topic]**
- Consensus view: [What most sources agree on]
- Evidence: [Key studies/data supporting this]
- Dissenting views: [Any contradictions]
- Strength of evidence: [How confident are we]

**Theme 2: [Topic]**
[Repeat structure...]

**Evolution of thinking:**
- Early understanding (before [year]): [What people thought]
- Current understanding: [What we know now]
- How views changed: [What new evidence emerged]

**Gaps in knowledge:**
- What's still unknown: [Unanswered questions]
- Conflicting evidence: [Where studies disagree]
- Areas needing more research: [What to study next]

**Implications for our work:**
- How this applies to [our situation]: [Practical takeaways]
- What to do based on this research: [Actions]
- What to avoid: [What research says won't work]

**Recommended reading:**
- If you read 1 source, read: [Most important source]
- If you read 3 sources, read: [Top 3 most valuable]
```

---

### 26. Fishbone Diagram (Ishikawa)

**When:** Complex problem with multiple potential causes

**Prompt:**
```
Create Fishbone diagram for [problem]:

**Problem/Effect:** [What we're trying to explain - the "fish head"]

**Major cause categories** (the "bones"):

**1. People:**
- [Potential cause 1 related to people]
- [Potential cause 2 related to people]

**2. Process:**
- [Potential cause 1 related to process]
- [Potential cause 2 related to process]

**3. Technology:**
- [Potential cause 1 related to technology]
- [Potential cause 2 related to technology]

**4. Environment:**
- [Potential cause 1 related to environment]
- [Potential cause 2 related to environment]

**5. Materials:**
- [Potential cause 1 related to inputs/materials]
- [Potential cause 2 related to inputs/materials]

**6. Measurement:**
- [Potential cause 1 related to metrics/tracking]
- [Potential cause 2 related to metrics/tracking]

**Brainstorm sub-causes** (branches off main bones):
For each potential cause above:
- Why might this cause the problem? [Deeper level]
- What evidence supports this? [Data/observations]

**Prioritization:**
Which causes are most likely? (Use criteria: frequency, impact, evidence)
1. [Most likely cause] - Confidence: [%]
2. [Second most likely] - Confidence: [%]
3. [Third most likely] - Confidence: [%]

**Investigation plan:**
- [ ] Test cause #1 by: [Specific validation method]
- [ ] Test cause #2 by: [Specific validation method]
```

---

### 27. Pareto Analysis (80/20)

**When:** Want to identify vital few issues vs trivial many

**Prompt:**
```
Conduct Pareto analysis on [dataset/issues]:

**Data:**
[List all items with their frequency/impact/value]

| Item | Count/Value | % of Total | Cumulative % |
|------|-------------|------------|--------------|
| [Item 1] | [X] | [Y%] | [Y%] |
| [Item 2] | [X] | [Y%] | [Y+Y%] |
| [Continue sorted by Count descending...] |  |  |  |

**80/20 Analysis:**
- Top [N] items account for [~80%] of total impact
- These [N] items = [% of all items] (should be ~20%)

**Vital Few (focus here):**
1. [Item] - Impact: [X] - Why prioritize: [Reasoning]
2. [Item] - Impact: [X] - Why prioritize: [Reasoning]
3. [Item] - Impact: [X] - Why prioritize: [Reasoning]

**Trivial Many (deprioritize):**
- Remaining [N] items account for only [~20%] of impact
- Recommendation: [Batch process, automate, or eliminate]

**Action plan:**
- If we fix the vital few: [Expected improvement: %]
- Effort to fix vital few: [Estimate hours/resources]
- ROI: [Impact / Effort ratio]

**Insight:** Focus on [specific vital few items] to achieve [X%] improvement with [Y%] of effort.
```

---

### 28. Time Series Decomposition

**When:** Have complex time-based data, want to separate components

**Prompt:**
```
Decompose time series for [metric]:

**Raw data:** [Describe dataset - time period, frequency]

**Components to extract:**

**1. Trend:**
- Long-term direction: [Increasing/Decreasing/Flat]
- Rate of change: [X per time period]
- Visual: [Describe smoothed trend line]

**2. Seasonality:**
- Pattern repeats every: [Time period - e.g., weekly, monthly, quarterly]
- Peak occurs: [When in cycle]
- Trough occurs: [When in cycle]
- Magnitude: [How big are seasonal swings - %]

**3. Cyclical:**
- Longer-term cycles (not seasonality): [Describe if present]
- Cycle length: [How long peak-to-peak]
- Related to: [External factors causing cycles]

**4. Irregular / Noise:**
- Random fluctuations: [How much unexplained variance]
- Outliers: [Dates] - Caused by: [Known events]

**Reconstruction:**
- Trend + Season + Cycle + Noise = Observed value
- Model fit: [How well does this explain data - R²]

**Forecasting:**
Using decomposition:
- Next period forecast: [Value]
- Confidence interval: [Range]
- Key assumptions: [What must remain constant]

**Insights:**
- [What component dominates - trend vs seasonality]
- [What action items emerge from understanding components]
```

---

### 29. Cost-Benefit Analysis

**When:** Evaluating whether initiative is worth the investment

**Prompt:**
```
Cost-benefit analysis for [initiative]:

**Costs:**

**One-time costs:**
| Item | Amount | Timing | Notes |
|------|--------|--------|-------|
| [Item 1] | $[X] | [When] | [Details] |
| [Item 2] | $[X] | [When] | [Details] |
| **Total one-time** | **$[X]** |  |  |

**Recurring costs:**
| Item | Amount per [period] | Annual | Notes |
|------|---------------------|--------|-------|
| [Item 1] | $[X] | $[Y] | [Details] |
| [Item 2] | $[X] | $[Y] | [Details] |
| **Total recurring** | **$[X]/period** | **$[Y]/year** |  |

**Benefits:**

**One-time benefits:**
| Item | Amount | Timing | Notes |
|------|--------|--------|-------|
| [Item 1] | $[X] | [When] | [Details] |

**Recurring benefits:**
| Item | Amount per [period] | Annual | Notes |
|------|---------------------|--------|-------|
| [Item 1] | $[X] | $[Y] | [Details] |
| [Item 2] | $[X] | $[Y] | [Details] |
| **Total recurring** | **$[X]/period** | **$[Y]/year** |  |

**Analysis:**
- Year 1 net: [Benefits - Costs] = $[X]
- Break-even point: [Month/Year when cumulative benefits exceed costs]
- 3-year NPV: $[X] (discounted at [Y%])
- ROI: [(Total Benefits - Total Costs) / Total Costs] = [X%]

**Qualitative factors:**
- Benefits hard to quantify: [List intangible benefits]
- Risks/downsides: [What could reduce benefits]
- Opportunity cost: [What else could we do with resources]

**Recommendation:** [Go/No-go + rationale]
```

---

### 30. Sensitivity Analysis

**When:** Model depends on assumptions, want to test how robust conclusions are

**Prompt:**
```
Sensitivity analysis for [model/forecast]:

**Base case assumptions:**
1. [Assumption 1] = [Value]
2. [Assumption 2] = [Value]
3. [Assumption 3] = [Value]

**Base case result:** [Outcome]

**Sensitivity testing:**

**Variable 1: [Assumption 1]**
| Scenario | Assumption Value | Result | % Change from Base |
|----------|-----------------|--------|-------------------|
| Pessimistic | [Low value] | [Outcome] | [-X%] |
| Base | [Expected value] | [Outcome] | [0%] |
| Optimistic | [High value] | [Outcome] | [+X%] |

**Variable 2: [Assumption 2]**
[Repeat table...]

**Variable 3: [Assumption 3]**
[Repeat table...]

**Sensitivity ranking:**
Which assumptions matter most? (Ranked by impact on outcome)
1. [Assumption X] - Most sensitive: [±Y%] change causes [±Z%] outcome change
2. [Assumption Y] - Moderate sensitivity
3. [Assumption Z] - Least sensitive

**Scenario combinations:**
| Scenario | Assumptions | Result | Probability |
|----------|-------------|--------|-------------|
| Worst case | [All pessimistic] | [Outcome] | [Low %] |
| Expected case | [All base] | [Outcome] | [High %] |
| Best case | [All optimistic] | [Outcome] | [Low %] |

**Insights:**
- Model is robust if: [Result stays positive across realistic scenarios]
- Model is fragile if: [Result very sensitive to one assumption]
- Focus validation efforts on: [Most sensitive assumptions]

**Recommendation:**
Given sensitivity analysis: [Decision + confidence level]
```

---

### 31. Expert Interview Protocol

**When:** Conducting research interview, want structured yet flexible approach

**Prompt:**
```
Design interview protocol for [research topic]:

**Interview goal:** [What insight we're seeking]
**Expert profile:** [Who we're interviewing - role, expertise]
**Duration:** [30/60/90 minutes]

**Opening (5 min):**
- Thank you for your time
- Context: [Briefly explain research purpose]
- Permission to record/take notes
- Confidentiality: [How will we use this information]

**Warmup questions (10 min):**
1. Tell me about your role and how you work with [topic]
2. How long have you been doing this?
3. [Establish rapport, get them talking]

**Core questions (30-40 min):**

**Theme 1: [Topic]**
1. [Open-ended question]
   - Probe: Can you give me an example?
   - Probe: What makes that challenging?
   
2. [Follow-up question]
   - Probe: How do others approach this differently?

**Theme 2: [Topic]**
[Continue structure...]

**Theme 3: [Topic]**
[Continue structure...]

**Closing questions (10 min):**
1. What's the most important thing we haven't discussed?
2. If you could change one thing about [topic], what would it be?
3. Who else should I talk to about this?

**Wrap up (5 min):**
- Summarize key points: "I heard you say..."
- Next steps: [What happens with this information]
- Thank you + follow-up contact

**Interview notes template:**
- Date: [X]
- Interviewee: [Anonymous ID if confidential]
- Key insights: [Bullet list]
- Quotes: [Noteworthy exact words]
- Surprising findings: [What challenged assumptions]
- Follow-up needed: [Questions for next interview]
```

---

### 32. Data Lineage Mapping

**When:** Need to trace data journey from source to final use

**Prompt:**
```
Map data lineage for [data element/field]:

**Source:**
- Origin system: [Where does raw data come from]
- Creation method: [How is it generated/collected]
- Owner: [Who's responsible for source]
- Refresh frequency: [How often updated]
- Format: [Data type, structure]

**Transformation journey:**

**Step 1: Extraction**
- Tool: [What pulls data from source]
- Schedule: [When/how often]
- Logic: [Any filtering/selection]
- Output: [Where it lands]

**Step 2: Transformation**
- Tool: [What processes it]
- Logic: [What changes - formulas, mappings, cleansing]
- Business rules: [Validations applied]
- Output: [Where it lands]

**Step 3: Loading**
- Tool: [What loads to final destination]
- Destination: [Final system/table]
- Validation: [Quality checks]

**Dependencies:**
- Upstream: [What other data this depends on]
- Downstream: [What uses this data]

**Quality & Governance:**
- Data quality checks: [Where/when validated]
- Failure modes: [What can break this pipeline]
- Monitoring: [How we detect issues]
- SLA: [How fresh must data be]

**Documentation:**
- Technical docs: [Link to ETL specs]
- Business glossary: [Link to definition]
- Ownership: [Who to contact for issues]

**Visual diagram:**
```
[Source System] 
     ↓ [ETL Tool - Daily @ 2am]
[Staging Table] 
     ↓ [Transform - Join + Aggregate]
[Data Warehouse]
     ↓ [BI Tool - Refresh on demand]
[Dashboard/Report]
```

**Purpose:** Enables troubleshooting, impact analysis, compliance
```

---

### 33. A/B Test Analysis

**When:** Ran experiment with control and treatment, need to interpret results

**Prompt:**
```
Analyze A/B test results:

**Test setup:**
- Hypothesis: [What we predicted]
- Duration: [Start - End dates]
- Sample size: Control [N], Treatment [M]
- Primary metric: [What we measured]
- Secondary metrics: [Other things tracked]

**Results:**

| Metric | Control | Treatment | Difference | % Change | Statistical Significance |
|--------|---------|-----------|------------|----------|-------------------------|
| [Primary] | [Value] | [Value] | [Delta] | [%] | p=[X] (sig/not sig) |
| [Secondary 1] | [Value] | [Value] | [Delta] | [%] | p=[X] |
| [Secondary 2] | [Value] | [Value] | [Delta] | [%] | p=[X] |

**Interpretation:**
- **Is difference real?** [Yes/No based on p-value < 0.05]
- **Is difference meaningful?** [Yes/No based on business impact]
- **Confidence interval:** We're 95% confident true effect is between [X%] and [Y%]

**Segment analysis:**
Did treatment work better for certain groups?
| Segment | Control | Treatment | Lift |
|---------|---------|-----------|------|
| [Segment 1] | [Value] | [Value] | [%] |
| [Segment 2] | [Value] | [Value] | [%] |

**Guardrail metrics:**
Did anything get worse?
- [Metric]: [No change / Acceptable change / Concerning change]

**Conclusion:**
- Winner: [Control / Treatment / No clear winner]
- Recommendation: [Roll out / Don't roll out / Test further]
- Expected impact if rolled out to 100%: [Projected value]

**Caveats:**
- Sample size limitations: [Did we have enough power?]
- Novelty effects: [Might effect fade over time?]
- Generalizability: [Will this hold for full population?]

**Next steps:**
- [ ] [Action based on results]
```

---

### 34. Competitive Intelligence Brief

**When:** Monitoring competitor moves, need structured summary

**Prompt:**
```
Compile competitive intelligence on [Competitor]:

**Company overview:**
- Name: [X]
- Size: [Revenue, employees, market share]
- Key markets: [Geographic, segments]
- Positioning: [How they describe themselves]

**Recent moves:**
| Date | Action | Source | Significance |
|  |------|--------|----------|------------|
| [Date] | [Product launch/partnership/acquisition] | [Link] | [Impact on us] |

**Product/Service comparison:**
| Feature | Us | Them | Comments |
|---------|-----|------|----------|
| [Feature 1] | [Status] | [Status] | [Advantage/parity/disadvantage] |
| [Feature 2] | [Status] | [Status] | [Advantage/parity/disadvantage] |

**Pricing comparison:**
| Tier | Us | Them | % Difference |
|------|-----|------|-------------|
| [Entry] | $[X] | $[Y] | [±Z%] |

**Strategic assessment:**
- Their strengths: [What they do well]
- Their weaknesses: [Where they're vulnerable]
- Likely next moves: [What we predict they'll do based on patterns]

**Implications for us:**
- Threats: [Where they pressure us]
- Opportunities: [Where we can counter]
- Actions: [What we should do in response]

**Sources:**
- Public filings: [Link]
- News coverage: [Link]
- Customer feedback: [Link/notes]
- Industry reports: [Link]

**Next review:** [Date - monthly/quarterly]
```

---

### 35. Knowledge Gap Assessment

**When:** Identifying what we don't know but need to learn

**Prompt:**
```
Identify knowledge gaps for [project/role/domain]:

**What we know well:**
- [Topic 1] - Confidence: High - Evidence: [How we know]
- [Topic 2] - Confidence: High - Evidence: [How we know]

**What we partially know:**
- [Topic 3] - Confidence: Medium - Gap: [What's unclear]
- [Topic 4] - Confidence: Medium - Gap: [What's unclear]

**What we don't know:**
- [Topic 5] - Confidence: Low - Need: [What we must learn]
- [Topic 6] - Confidence: Low - Need: [What we must learn]

**Unknown unknowns:**
[What are we not even aware we don't know?]
- [Potential blind spot 1]
- [Potential blind spot 2]

**Gap prioritization:**
| Knowledge Gap | Criticality | Urgency | Acquisition Difficulty | Priority Score |
|---------------|-------------|---------|----------------------|---------------|
| [Gap 1] | High/Med/Low | High/Med/Low | Hard/Med/Easy | [Calcimpact] |
| [Gap 2] | | | | |

**Learning plan:**

**Priority 1: [Gap]**
- What to learn: [Specific]
- Why critical: [Impact if not addressed]
- How to learn: [Method - research, training, expert interview]
- Timeline: [When to complete]
- Success criteria: [How we'll know we've learned it]

**Priority 2: [Gap]**
[Repeat structure...]

**Resources needed:**
- Time: [Hours estimated]
- Budget: [$ for training,courses]
- Access: [People to interview, systems to access]
```

---

## ✍️ Writing & Documentation

### 36. Executive Summary Generator

**When:** Have detailed document, need concise high-level summary for leadership

**Prompt:**
```
Create executive summary for [detailed document]:

**Context:** [1-2 sentences: What is this about and why does it matter]

**Key findings:** [3-5 bullet points, each one sentence]
- [Finding 1 - most important insight]
- [Finding 2]
- [Finding 3]

**Recommendations:** [3-5 action items, prioritized]
1. [Action 1] - Expected impact: [Quantified if possible]
2. [Action 2] - Expected impact: [Quantified]
3. [Action 3] - Expected impact: [Quantified]

**Bottom line:** [1-2 sentences: So what? What should reader do with this information?]

**Constraints:**
- Length: 150-200 words maximum (fits on one page with formatting)
- Tone: Confident, action-oriented, data-driven
- Audience: [VP/C-suite level] with limited time
- Standalone: Should make sense without reading full document

**Visual element:** [Include one compelling chart/table if applicable]

**Writing checklist:**
- [ ] No jargon or acronyms without definition
- [ ] Specific and concrete (not vague)
- [ ] Numbers included where possible
- [ ] Clear call-to-action
- [ ] Can be read in 60 seconds
```

---

### 37. Documentation Structure

**When:** Creating new documentation, need clear organization

**Prompt:**
```
Create documentation structure for [system/process]:

**1. Overview**
- Purpose: [What is this? Why does it exist?]
- Audience: [Who will use this documentation?]
- Scope: [What's covered / What's not covered]

**2. Prerequisites**
- Required knowledge: [What reader should know first]
- Required access: [Systems, permissions, tools needed]
- Estimated time: [How long to complete this process]

**3. Architecture / Conceptual Model** (if applicable)
- High-level diagram: [Visual representation]
- Components: [Key parts and how they interact]
- Terminology: [Define domain-specific terms]

**4. Step-by-Step Instructions**

**Part A: [Phase name]**
- **Step 1:** [Action in imperative voice]
  - Why: [Purpose of this step]
  - Expected result: [What you should see]
  - If something goes wrong: [Troubleshooting]
  - Screenshot/example: [Visual aid]

- **Step 2:** [Continue pattern...]

**Part B: [Phase name]**
[Continue structure...]

**5. Examples**
- Example 1: [Real-world scenario showing process]
- Example 2: [Edge case or variation]

**6. Troubleshooting**
| Problem | Likely Cause | Solution |
|---------|--------------|----------|
| [Error 1] | [Reason] | [How to fix] |
| [Error 2] | [Reason] | [How to fix] |

**7. FAQs**
- Q: [Common question]
- A: [Clear answer]

**8. Reference**
- Related documentation: [Links]
- Glossary: [Terms defined]
- Contact: [Who to ask for help]

**9. Maintenance**
- Last updated: [Date]
- Owner: [Who maintains this]
- Review cycle: [When to update]
- Changelog: [What's changed over time]

**Quality checklist:**
- [ ] Is it accurate?
- [ ] Is it complete?
- [ ] Is it clear?
- [ ] Has it been tested by someone unfamiliar with process?
```

---

### 38. Email Templates by Purpose

**When:** Common email scenarios where consistent, professional communication matters

**Status Report Email:**
```
Subject: [Project Name] - Status Report for [Month/Week]

Hi [Recipient],

Here's this [month/week]'s status for [project]:

**🟢 On Track:**
- [Deliverable 1] - Completed [date]
- [Deliverable 2] - 80% complete, on schedule

**🟡 At Risk:**
- [Deliverable 3] - [Brief explanation of risk] - Mitigation: [Our plan]

**🔴 Blocked:**
- [Deliverable 4] - [What's blocking] - Need: [Specific help requested]

**Next Week Focus:**
- [Priority 1]
- [Priority 2]

**Questions/Decisions Needed:**
- [Item needing input] - Need by: [Date]

Let me know if you need more detail on anything.

[Your name]
```

**Stakeholder Update:**
```
Subject: [Project]: Key Milestone Achieved

Hi [Stakeholder],

Quick update: [Major accomplishment in one line].

**What this means:**
[Business impact in 2-3 sentences]

**Key metrics:**
- [Metric 1]: [Value] ([% change from baseline])
- [Metric 2]: [Value] ([% change])

**Next steps:**
[What happens next - 1-2 sentences]

Happy to discuss further if useful. [Optional: Meeting offer]

[Your name]
```

**Request for Help:**
```
Subject: Request: [Specific help needed] for [Project]

Hi [Recipient],

I'm working on [brief context] and could use your expertise with [specific thing].

**What I need:**
[Clear, specific request - ideally yes/no or <30min commitment]

**Context:**
[Why I'm asking you specifically]
[What I've tried so far]
[What decision this will inform]

**Timeline:**
[When I need this by - with buffer]

**How you can help:**
[Make it easy - provide options like "15-min call" or "quick email response to these 3 questions"]

Let me know if this is feasible. Happy to provide more context.

Thanks,
[Your name]
```

**Escalation Email:**
```
Subject: [Urgent Help Needed]: [Specific issue]

Hi [Manager/Stakeholder],

Escalating an issue that needs visibility/decision:

**Problem:**
[What's wrong - 1-2 sentences]

**Impact:**
[Who/what affected + severity]

**What I've tried:**
1. [Action 1] - Result: [Didn't work because X]
2. [Action 2] - Result: [Didn't work because Y]

**What I need:**
[Specific help - decision, resource, approval]

**Options:**
1. [Option 1] - Pros: [X] | Cons: [Y]
2. [Option 2] - Pros: [X] | Cons: [Y]

My recommendation: [Option X] because [reasoning]

Can we discuss [today/tomorrow]? This is blocking [deliverable].

[Your name]
```

**Thank You / Recognition:**
```
Subject: Thank You - [Specific thing]

Hi [Recipient],

Just wanted to say thanks for [specific help you provided].

[One sentence on impact: "This saved me X hours" or "This unblocked the project" or "I learned X from this"]

[Optional: Offer to return favor] Let me know if there's anything I can help you with.

Appreciate it!
[Your name]
```

---

### 39. Meeting Notes Template

**When:** Taking notes during meeting to ensure  actionability and follow-through

**Prompt:**
```
Meeting notes for: [MeetingTitle/Purpose]

**Date:** [X]
**Attendees:** [Names] ([Y] present, [Z] absent)
**Duration:** [Start - End]
**Note-taker:** [Your name]

**Agenda:**
1. [Topic 1]
2. [Topic 2]
3. [Topic 3]

**Discussion:**

**Topic 1: [Name]**
- [Key point discussed]
- [Key point discussed]
- [Decision made]: [What was decided + rationale]
- [Open question]: [What wasn't resolved]

**Topic 2: [Name]**
[Repeat structure...]

**Decisions Made:**
1. [Decision] - Owner: [Who] - Rationale: [Why]
2. [Decision] - Owner: [Who] - Rationale: [Why]

**Action Items:**
| Item | Owner | Due Date | Status |
|------|-------|----------|--------|
| [Action 1] | [Name] | [Date] | [Not started] |
| [Action 2] | [Name] | [Date] | [Not started] |

**Parking Lot** (items deferred):
- [Topic to revisit later]

**Next Meeting:**
- Date/Time: [When]
- Purpose: [What we'll cover]
- Prep needed: [What attendees should do beforehand]

**Follow-up by:** [Date - usually within 24 hours of meeting]
Send notes to: [Distribution list]
```

---

### 40. Process Documentation (SOP)

**When:** Documenting repeatable process for consistency

**Prompt:**
```
Standard Operating Procedure (SOP) for: [Process Name]

**SOP ID:** [Number]
**Version:** [X.Y]
**Effective Date:** [Date]
**Owner:** [Name/Role]
**Review Frequency:** [Quarterly/Annually]

**1. PURPOSE**
[Why this process exists - business objective]

**2. SCOPE**
- **In scope:** [What situations this covers]
- **Out of scope:** [What is NOT covered by this SOP]

**3. ROLES & RESPONSIBILITIES**
| Role | Responsibility |
|------|----------------|
| [Role 1] | [What they do in this process] |
| [Role 2] | [What they do in this process] |

**4. PREREQUISITES**
- [ ] [System access required]
- [ ] [Data/tools needed]
- [ ] [Training completed]

**5. PROCEDURE**

**Phase 1: [Name]** (Frequency: [Daily/Weekly/etc])

**Step 1.1:** [Action verb] [object]
- **How:** [Detailed instructions]
- **Where:** [System/location]
- **Expected result:** [What you should see]
- **Time estimate:** [Duration]

**Step 1.2:** [Continue...]

**Phase 2: [Name]**
[Repeat structure...]

**6. QUALITY CHECKS**
- [ ] [Validation step 1]
- [ ] [Validation step 2]
- [ ] [Validation step 3]

**7. EXCEPTION HANDLING**
| Exception | When it occurs | How to handle |
|-----------|----------------|---------------|
| [Exception 1] | [Trigger] | [Response] |
| [Exception 2] | [Trigger] | [Response] |

**8. SUCCESS CRITERIA**
- [Metric 1]: Target [X]
- [Metric 2]: Target [Y]

**9. RELATED DOCUMENTS**
- [Link to related SOP]
- [Link to system documentation]
- [Link to training materials]

**10. REVISION HISTORY**
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | [Date] | [Name] | Initial creation |
| 1.1 | [Date] | [Name] | [What changed] |

**Approval:**
- Prepared by: [Name, Date]
- Reviewed by: [Name, Date]
- Approved by: [Name, Date]
```

---

### 41. Decision Documentation

**When:** Made significant decision, need record of rationale for future reference

**Prompt:**
```
Decision Record: [Decision Title]

**Decision ID:** [Number]
**Date:** [When decision made]
**Decider(s):** [Who had authority]
**Status:** [Proposed / Accepted / Superseded]

**Context:**
[What situation led to this decision? 3-5 sentences providing background]

**Decision:**
[What was decided? Clear, one-sentence statement]

**Options Considered:**

**Option 1: [Name]**
- Description: [What this option entails]
- Pros: [Advantages]
- Cons: [Disadvantages]
- Cost: [Resources required]

**Option 2: [Name]**
[Repeat pattern for 3-5 options...]

**Evaluation Criteria:**
| Criterion | Weight | Option 1 Score | Option 2 Score | Option 3 Score |
|-----------|--------|----------------|----------------|----------------|
| [Criterion 1] | [%] | [1-10] | [1-10] | [1-10] |
| [Criterion 2] | [%] | [1-10] | [1-10] | [1-10] |
| **Total** | 100% | [Weighted sum] | [Weighted sum] | [Weighted sum] |

**Rationale:**
[Why was chosen option selected? 3-5 sentences explaining the reasoning]

**Assumptions:**
- [Assumption 1 - what we're taking as given]
- [Assumption 2]

**Risks:**
- [Risk 1] - Mitigation: [How we'll address]
- [Risk 2] - Mitigation: [How we'll address]

**Consequences:**
- [Expected positive outcome 1]
- [Expected positive outcome 2]
- [Potential downside awareness]

**Review Date:**
[When we'll revisit this decision to evaluate if it was correct]

**References:**
- [Link to analysis document]
- [Link to stakeholder input]

**Notes:**
[Any additional context for future readers]
```

---

### 42. onboarding Documentation

**When:** New person joining team/project, need efficient knowledge transfer

**Prompt:**
```
Onboarding Guide for: [Role/Project]

**Welcome!**
[Purpose of this onboarding, what new person will be able to do by the end]

**Week 1: Setup & Orientation**

**Day 1:**
- [ ] IT setup: [Links to request forms]
- [ ] Accounts created: [List systems + how to request access]
- [ ] Read: [Links to 3 essential documents]
- [ ] Meet: [Intro meeting with manager]

**Day 2-3:**
- [ ] Complete training: [Required courses]
- [ ] Shadow: [Person doing the job]
- [ ] Read: [Additional documentation - prioritized list]

**Day 4-5:**
- [ ] Hands-on exercise: [Simple task with supervision]
- [ ] Meet: [Key stakeholders - list names/roles]
- [ ] Ask questions: [Running list maintained]

**Week 2: Guided Practice**
- [ ] Complete [Task A] with review
- [ ] Complete [Task B] with review
- [ ] Attend [recurring meetings - list]
- [ ] 1:1 check-in: Questions, concerns, feedback

**Week 3-4: Increasing Independence**
- [ ] Own [Responsibility X] end-to-end
- [ ] Present work in [Team meeting]
- [ ] Identify improvement opportunity
- [ ] End-of-month check-in review

**Key Resources:**

| Resource | Link | When to Use |
|----------|------|-------------|
| [System 1 docs] | [URL] | [Daily - for X tasks] |
| [Process guide] | [URL] | [Weekly - when doing Y] |
| [Troubleshooting] | [URL] | [As needed - when errors] |

**Who to Ask:**
| Question Type | Person | Contact |
|---------------|--------|---------|
| [Technical questions] | [Name] | [Email/Slack] |
| [Process questions] | [Name] | [Email/Slack] |
| [Escalations] | [Manager] | [Email/Slack] |

**Common First Questions:**
- Q: [Frequently asked question]
- A: [Answer]

**Success Milestones:**
- End of Week 1: [Can navigate systems independently]
- End of Week 2: [Can complete Task X with guidance]
- End of Month 1: [Can complete full workflow independently]
- End of Month 3: [Fully ramped, contributing at expected level]

**Feedback Loop:**
[How new person should provide feedback on onboarding experience to improve this doc]
```

---

### 43. Technical Specification

**When:** Designing new feature/system, need detailed requirements

**Prompt:**
```
Technical Specification: [Feature/System Name]

**1. OVERVIEW**
- **Project:** [Name]
- **Author:** [Name]
- **Date:** [Date]
- **Status:** [Draft / In Review / Approved]

**2. OBJECTIVE**
[What are we building and why? 2-3 sentences]

**3. SUCCESS METRICS**
- [Metric 1]: Target [X]
- [Metric 2]: Target [Y]
- [Metric 3]: Target [Z]

**4. REQUIREMENTS**

**4.1 Functional Requirements**
| ID | Requirement | Priority | Acceptance Criteria |
|----|-------------|----------|-------------------|
| FR-1 | [System must do X] | High/Med/Low | [How we'll test] |
| FR-2 | [System must do Y] | High/Med/Low | [How we'll test] |

**4.2 Non-Functional Requirements**
| ID | Type | Requirement | Target |
|----|------|-------------|--------|
| NFR-1 | Performance | [Response time] | [<2 seconds] |
| NFR-2 | Scalability | [Concurrent users] | [1000+] |
| NFR-3 | Security | [Data protection] | [Encryption at rest/transit] |

**5. ARCHITECTURE**

**5.1 System Diagram**
```
[ASCII or description of component diagram]
[Component A] <--> [Component B] <--> [Component C]
```

**5.2 Data Model**
- **Entity 1:** [Name]
  - Fields: ID, Field1, Field2
  - Relationships: [How it connects to other entities]

**5.3 APIs / Interfaces**
- **Endpoint:** `POST /api/resource`
  - Input: `{field1: string, field2: int}`
  - Output: `{id: int, status: string}`
  - Errors: [List possible error codes]

**6. IMPLEMENTATION PLAN**

**Phase 1:** [Scope]
- Sprint 1: [Deliverables]
- Sprint 2: [Deliverables]

**Phase 2:** [Scope]
[Continue...]

**7. DEPENDENCIES**
- [External system 1] - Risk: [High/Med/Low]
- [External API 2] - Risk: [High/Med/Low]

**8. RISKS & MITIGATIONS**
| Risk | Impact | Probability | Mitigation |
|------|--------|-------------|------------|
| [Risk 1] | High/Med/Low | High/Med/Low | [How we'll address] |

**9. TESTING STRATEGY**
- Unit tests: [Coverage target]
- Integration tests: [What scenarios]
- User acceptance testing: [Criteria]

**10. ROLLOUT PLAN**
- Dev environment: [Date]
- Staging: [Date]
- Production (% rollout): [Dates with % increments]

**11. SUPPORT & MAINTENANCE**
- Monitoring: [What metrics to track]
- Alerts: [Thresholds for notification]
- On-call: [Who handles issues]

**12. OPEN QUESTIONS**
- [ ] [Question 1 - Owner: [Name]]
- [ ] [Question 2 - Owner: [Name]]

**13. APPROVALS**
- Engineering: [Name, Date]
- Product: [Name, Date]
- Security: [Name, Date]
```

---

### 44. Change Log

**When:** Tracking changes to system/document/project over time

**Prompt:**
```
Change Log for: [System/Document Name]

**Format:** All entries follow format: `[Version] - [Date] - [Category] - [Description]`

**Categories:**
- **Added:** New features/content
- **Changed:** Modifications to existing
- **Deprecated:** Soon-to-be-removed features
- **Removed:** Deleted features/content
- **Fixed:** Bug fixes
- **Security:** Security patches

---

## [Version X.Y.Z] - YYYY-MM-DD

### Added
- [Feature/Content 1] - [Brief description of what was added and why]
- [Feature/Content 2]

### Changed
- [Modification 1] - [What changed and impact]
- [Modification 2]

### Fixed
- [Bug 1] - [What was broken and how it was fixed]

---

## [Version X.Y.Z-1] - YYYY-MM-DD

[Repeat structure for previous versions...]

---

**Versioning Scheme:**
- Major (X.0.0): Breaking changes, significant rewrites
- Minor (0.Y.0): New features, backwards-compatible
- Patch (0.0.Z): Bug fixes, minor updates

**How to Contribute:**
[Instructions for how others should document their changes]
```

---

### 45. README Template

**When:** Creating repository or project folder that others will use

**Prompt:**
```
# [Project Name]

[One-sentence description of what this is]

## Overview

[2-3 paragraphs explaining what this project does, why it exists, and key capabilities]

## Features

- ✅ [Feature 1]
- ✅ [Feature 2]
- ✅ [Feature 3]
- 🚧 [Feature 4 - In Development]
- 📋 [Feature 5 - Planned]

## Getting Started

### Prerequisites

- [Requirement 1] - version X.Y+
- [Requirement 2]
- [System requirement]

### Installation

```bash
# Step-by-step commands
command 1
command 2
```

### Quick Start

```bash
# Minimal example to get something working
command to run
```

Expected output:
```
[What you should see]
```

## Usage

### Basic Example

```code
[ Show most common use case]
```

### Advanced Example

```code
[Show more complex use case]
```

## Configuration

| Option | Description | Default | Required |
|--------|-------------|---------|----------|
| `option1` | [What it does] | `value` | Yes/No |
| `option2` | [What it does] | `value` | Yes/No |

## Documentation

- [Link to full documentation]
- [Link to API reference]
- [Link to examples]

## Contributing

[How others can contribute - link to CONTRIBUTING.md if detailed]

## Testing

```bash
# How to run tests
command to test
```

## Deployment

[Instructions for deploying to production environment]

## Troubleshooting

**Problem:** [Common issue]
**Solution:** [How to fix]

**Problem:** [Common issue]
**Solution:** [How to fix]

## License

[License type - e.g., MIT, Apache 2.0] - see [LICENSE](LICENSE) file

## Contact

- **Maintainer:** [Name](mailto:email@example.com)
- **Issues:** [Link to issue tracker]
- **Discussions:** [Link to forum/chat]

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history.

## Acknowledgments

- [Credit to contributors]
- [Credit to libraries/tools used]
```

---

## End of Library

**Total Prompts:** 45

This library contains 45 curated prompts covering strategic planning, analysis, documentation, and communication scenarios. Each prompt is designed to be copy-pastable and adapted to your specific context.

**Usage Tips:**
- Use Ctrl+F to search by keyword or prompt number
- Adapt placeholder text ([brackets]) to your situation
- Combine prompts for complex scenarios
- Save your customized versions for reuse

**Contributing:**
Have a prompt that's proven valuable? Consider contributing to expand this library.

---

**License:** MIT  
**Maintainer:** chase-key (CK)  
**Part of:** [AURELION AGENT-Lite](https://github.com/chase-key/aurelion-agent-lite)