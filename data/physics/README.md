# Physics — 844 draft records

Updated 24 November 2026: **2 additional draft records** were recovered from the existing source PDF and screened. The requested expansion of 1,000 per subject remains incomplete; 998 additions remain for this subject.

- [Additional JSON](physics_additional_2026_11_24.json)
- [Additional CSV](physics_additional_2026_11_24.csv)
- [Complete repository import manifest](../manifest.json)
- [Current expansion report](../../research/expansion_progress_2026_11_24.json)

Load the original batch plus this additional batch, using one format only. Answers are blank and all new records have approved_for_bot set to false. The original quality report describes the original batch; the current expansion report covers the additions. Existing records have been preserved.

## Original batch documentation

# Physics — 842 draft question records

Target: **1,000**. Current extraction: **842**, a shortfall of **158**. These are extraction candidates, not validated teaching material. Correct answers and explanations remain blank. **approved_for_bot is false on every record.**

## Files

- [CSV](physics_candidates.csv)
- [JSON](physics_candidates.json)
- [Quality report](quality_report.json)
- [Source PDF with original diagrams and mathematical layout](https://www.larnedu.com/wp-content/uploads/2019/03/JAMB-Physics-Past-Questions-1983-2004-By-Larnedu.pdf)

## Quality and images

All 842 records have unique IDs and case-sensitive normalized question-plus-option fingerprints. Option order is ignored for exact duplicate detection. Mathematical punctuation, numbers and unit case are retained in the comparison. Similar stems are flagged separately because changed quantities can make two questions different.

**203 records have diagram/context review flags.** These flags are heuristic, not exhaustive. image_url is null: diagrams remain in the source PDF, with a page link on every record. All 842 records require formula/unit review. Text extraction can flatten powers, omit roots, rearrange fractions and mix adjacent columns. Four or five option labels do not establish that an item is complete or correct.

Spot checks confirmed damaged scientific notation and stray text. For example, some extracted angles appear as 450, and some powers appear as 106; these must be checked visually rather than guessed. Historical year and source question numbers are not authenticated. Year is left null to avoid misleading labels. The compilation also has inconsistent running headers, including an Economics header on a page containing Physics content.

## Source and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) request credit for sharing and prohibit direct or indirect monetisation. Exam-body rights have not been independently verified. This collection is not cleared for a commercial or ad-supported bot.

## Remaining work

Review text against the source PDF, recover mathematical layout and diagrams, verify answers and possible near duplicates, replace rejected items, and obtain enough additional complete reusable questions to reach 1,000. Do not serve these drafts directly to students.
