# Three-minute presentation script

**Slide 1 — Decision question (about 45 seconds)**

Today I am proposing a measurable pharmacy operations question: can a weekly medication-review queue help the team identify records that may benefit from review, and can we measure whether the workflow is timely and useful? This is a workflow proposal, not a clinical recommendation. The files in this package contain synthetic teaching data only because the task's supplied dataset links were not visible in the screenshot. No results here describe actual patients or pharmacy activity.

**Slide 2 — Evidence and guardrails (about 75 seconds)**

The demonstration brings together three aggregate views: age-band and risk-flag counts, pharmacy fills and refill gaps, and adverse-event report counts with serious-report proportions. In a real project, we would replace these examples with the assigned datasets, record extraction dates and definitions, verify field mappings, and reconcile duplicate records before joining. A dispensing record does not establish that a medicine was taken. A spontaneous adverse-event report is not verified and does not establish causality or incidence. The two signals can guide a question for review, but they cannot answer a clinical safety question by themselves.

**Slide 3 — Pilot and decision (about 60 seconds)**

I recommend first validating the data and workflow with pharmacy and privacy leads, then running a time-limited operational pilot only after approval. Success measures should include data completeness, the share of flagged records reviewed within seven days, the adjudicated actionable-review rate, refill-gap trends, and subgroup coverage. We should compare against a defined baseline and report uncertainty and missingness. The leadership decision today is whether to authorize a governed pilot and provide the actual approved datasets. Until then, this dashboard is a demonstration, not evidence for changing treatment or prioritizing real individuals.
