# Chemistry — 865 draft question records

Target **1,000**; current draft **865**; shortfall **135**. This is an incomplete extraction draft, not a validated teaching dataset. All correct-answer and explanation fields are blank and approved_for_bot is false.

## Files

- [CSV](chemistry_candidates.csv)
- [JSON](chemistry_candidates.json)
- [Raw source contexts](source_contexts.json)
- [Quality report and similar question pairs](quality_report.json)
- [Source PDF](https://www.larnedu.com/wp-content/uploads/2019/03/JAMB-Chemistry-Past-Questions-1983-2004.pdf)

## Checks and remaining review

IDs and case-sensitive normalized question-plus-option fingerprints are unique. Numbers, charges, punctuation and chemical-symbol case are preserved in duplicate comparisons. Option order is ignored. Similar stems are flagged for review rather than automatically removed. Missing full stops after clearly spaced option labels were normalized during extraction.

Every record needs formula/reaction review: arrows, subscripts, superscripts, ionic charges and structural diagrams can be lost. 135 records have diagram review flags; 270 have shared-context flags (these groups overlap and flags are heuristic). Images are not embedded or hosted; image_url is null. Source PDF page links and raw column contexts help recover shared information. Raw contexts may themselves contain extraction errors. Source years are intentionally blank.

Trailing bracketed reference data containing equals signs, such as atomic masses, has been moved from the final option to additional_context. Both the JSON and CSV retain it. No scientific correction or answer inference is implied.

Before serving questions, recover missing context and images, repair chemical notation, verify answers, review near duplicates, and replace invalid records. The current count must not be represented as 1,000 finished questions.

## Attribution and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing but prohibit direct or indirect monetisation. Exam-body rights are not independently verified. This collection is not cleared for a commercial or ad-supported bot.
