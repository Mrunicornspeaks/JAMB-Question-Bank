# Biology — 923 draft question records

**The 1,000-question target is incomplete.** This collection contains 923 extracted questions with four or five labelled options. All records require review before bot use. Correct answers and explanations are blank; no answers were invented.

## Files

- [CSV for spreadsheets](biology_candidates.csv)
- [JSON for the bot database](biology_candidates.json)
- [Quality report and possible near duplicates](quality_report.json)
- [Original PDF with diagrams](https://www.larnedu.com/wp-content/uploads/2019/03/JAMB-Biology-Past-Questions_1983-2004.pdf)

## Checks and limitations

All IDs and normalized question-plus-option fingerprints are unique. Option order is ignored in fingerprint comparison. Similar question stems are listed for review, not automatically considered duplicates. Alternative PDF extraction passes were merged by source page, column and question number before deduplication.

152 questions have a conservative diagram/context review flag. Every question has a source-page link. Images are **not extracted or hosted** in this dataset: image_url is null. A bot must hold these items until the required image or context is recovered. Other items also require text and answer review; approved_for_bot is false for every record.

Year is intentionally blank because PDF year headings and column order are unreliable. A question can have all option labels and still contain a transcription mistake; passing structural checks does not establish scientific accuracy. Historical terminology may need syllabus review.

## Attribution and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing but prohibit direct or indirect monetisation. Exam-body rights have not been independently verified. This is not cleared for a paid or ad-supported bot.

## Remaining work

Review possible duplicates, repair extracted text, attach diagrams with the correct question associations, verify answers, and obtain enough additional complete reusable questions to reach 1,000. No generated questions or knowingly incomplete option sets were added to fill the target.
