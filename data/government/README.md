# Government — 963 draft questions

The 1,000-question target is **37 questions short**. These records have four or five labelled options but still need text, historical-context and answer review. All records have `approved_for_bot: false`. Answers and explanations are blank; none were invented.

- [Download/view CSV](government_candidates.csv)
- [JSON for database import](government_candidates.json)
- [Quality report, removed duplicates and similar stems](quality_report.json)
- [Source PDF from LarnEDU](https://www.larnedu.com/wp-content/uploads/2019/03/JAMB-Government-Past-Questions-1983-2004.pdf)

## Extraction and duplicate checks

Two PDF reading orders were merged by page, column and printed question number. Large headings and page headers were removed before splitting columns. Recognizable bare option labels were normalized. No question or answer text was generated to fill gaps.

33 exact duplicate occurrences were removed using normalized question text and option text, ignoring option order. 12 similar-stem pairs remain flagged for manual review. All retained IDs and fingerprints are unique. This does not guarantee that differently worded questions test different facts.

Every record links to its source PDF page. `source_column` is zero-based; question numbers are as extracted and can be incorrect in the source. `year` is deliberately null because the PDF year headings and reading order are unreliable. Some questions continue onto the next column or page.

## Before using in a bot

Review the original question and all options, resolve possible duplicate pairs, then verify the correct answer. Source typos and extraction errors can remain even when all option labels are present.

237 records are flagged for historical-context review. Questions about current officeholders or institutional arrangements must be checked against their original exam date; do not answer them using today's facts without that context. This flag is a heuristic and every record still needs review.

No diagram references were detected by the heuristic; this is not visual verification of every item. `image_url` is null. Any item requiring a diagram or missing context must remain unavailable to students until that material is restored.

## Attribution and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing but prohibit direct or indirect monetisation. Exam-body rights have not been independently verified. This dataset is not cleared for a paid or ad-supported bot.
