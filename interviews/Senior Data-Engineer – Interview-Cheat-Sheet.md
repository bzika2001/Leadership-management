⭐ Senior Data Engineer – Interview Cheat Sheet

1. Pipeline They’re Proud Of (Easy)
Primary question:
“Tell me about a data pipeline you built that you’re proud of. What problem did it solve?”
Follow‑ups:

“What made it challenging?”
“How did you know it was working correctly?”
“What would you improve next time?”

✔ Green Flags

Clear, confident explanation
Talks about business impact
Mentions reliability, performance, or quality improvements
Shows ownership and learning

❌ Red Flags

Too vague (“I just built pipelines”)
No measurable impact
Blames others, lack of ownership


2. Handling Changing Data (Medium)
Primary question:
“When data changes in the source system, how do your pipelines pick up only what’s changed?”
Follow‑ups:

“How do you handle late or duplicate data?”
“What if CDC breaks?”

✔ Green Flags

Knows terms like: incremental loads, CDC, watermarks, merge/upsert
Can explain simply how changes flow through
Shows real experience with broken pipelines and fixes

❌ Red Flags

Suggests full reloads as the norm
No awareness of data drift, late data, duplicates
Never handled schema changes


3. Ensuring Data Quality (Medium)
Primary question:
“How do you make sure the data is trustworthy before analysts use it?”
Follow‑ups:

“Which checks matter most?”
“How do you alert your team when data is wrong?”

✔ Green Flags

Mentions checks: freshness, duplicates, completeness, business rules
Has alerting/monitoring in place
Talks about preventing problems, not just fixing them

❌ Red Flags

“We just check visually”
No monitoring or alerting
No examples of solving quality issues


4. Building a Golden Employee Record (Medium)
Primary question:
“How would you combine multiple systems to create one accurate employee record?”
Follow‑ups:

“How do you avoid double-counting people?”
“Who decides which system is the ‘truth’?”

✔ Green Flags

Explains matching employees across systems
Talks about master data/keys
Understands handling historical changes
Mentions governance and definitions (“what counts as active?”)

❌ Red Flags

Says it’s just a join
Doesn’t talk about conflicts or mismatches
Ignores business rules or data ownership


5. Designing a Platform (Difficult)
Primary question:
“If you were designing our platform from scratch, what top 3 things would you prioritise, and why?”
Follow‑ups:

“How do you keep costs predictable?”
“What decisions are hardest to reverse later?”

✔ Green Flags

Priorities like:

reliable ingestion
data quality
standards (naming, logging, security)
cost/perf basics


Practical, balanced thinking
Not over‑engineering

❌ Red Flags

Overly theoretical
Only talks tools, not principles
Wants to build everything “perfect” before delivering value


🟩 Simple Scorecard (25 points total)
Rate each area:

Pipelines & CDC → /5
Data Quality → /5
Modeling / Golden Record → /5
Architecture Thinking → /5
Communication & Ownership → /5

Scoring guide:

22–25 → Strong hire
18–21 → Good hire
15–17 → Borderline (look at culture fit & growth)
<15 → Not ready for senior role
