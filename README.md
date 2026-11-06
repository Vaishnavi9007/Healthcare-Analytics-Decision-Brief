# Healthcare Analytics Decision Brief

This package is a privacy-aware demonstration of a leadership briefing built around a weekly medication-review workflow. **All included patient, pharmacy, and safety figures are synthetic teaching data. They are not supplied operational datasets and must not be represented as real findings.** The task screenshot indicates a supplied-materials area, but its dataset links were below the captured screen. Replace the demo CSVs with the assigned files before submitting any data-specific conclusions.

## Files

- healthcare_analytics_brief.pdf — executive brief
- dashboard.html — interactive, local dashboard
- presentation.html — three-slide presentation (arrow keys to navigate)
- speaker_script.md — approximately three-minute narration
- data/*_demo.csv — transparent synthetic aggregate input files
- report.html — source for the PDF brief

## Reproducible workflow

Open dashboard.html in a browser. It reads no remote resources and embeds the demonstration summaries so it works offline. For a real analysis, replace all three demo datasets with approved, de-identified sources; document source, extract date, field mapping, cohort inclusion rules, and suppressed small cells. Recompute all values and rerun privacy and bias review before presenting.

## Decision question

Can a weekly medication-review queue help pharmacy operations identify patients who may need a review, while tracking workflow measures and avoiding claims that spontaneous reports prove causation? Proposed queue prioritization is a workflow hypothesis only; validate it with authorized source data and clinical governance.

## Data and definitions

The demo shows aggregated age bands and risk flags, dispensing fills/refill gaps, and adverse-event report counts/seriousness. FAERS-style report counts are presented only to demonstrate a data-joining pattern. They do not measure incidence, relative risk, or causation. The actual assigned datasets and their documentation should replace these examples.

## Suggested success measures

1. Percentage of eligible records with complete medication and age fields.
2. Percentage of flagged records reviewed within seven days.
3. Actionable review rate, defined and adjudicated by the clinical team.
4. Refill-gap rate before and after workflow launch, with a pre-specified comparison design.
5. Privacy, subgroup coverage, and data-quality checks reported alongside each metric.

## Privacy and limitations

The demo uses aggregates and contains no patient identifiers. Real work should use approved minimum-necessary data, limit access, suppress small cells per organizational policy, and assess missingness and subgroup representation. A pharmacy claim is not proof of ingestion; a spontaneous safety report is not proof of drug causation. No clinical action should be based on this demonstration.
