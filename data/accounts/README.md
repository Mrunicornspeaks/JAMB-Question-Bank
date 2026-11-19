# Principles of Accounts — 458 draft questions

Target: **1,000**. Extracted draft: **458**. Shortfall: **542**. The available PDF is a smaller collection covering 1994–2004 internally, despite its filename and running header saying 1983–2004.

All records contain four or five labelled options, but none is approved for bot delivery. Answers and explanations are blank pending verification. No filler questions or answers were generated.

## Files

- [CSV for spreadsheets](accounts_candidates.csv)
- [JSON for database import](accounts_candidates.json)
- [Raw source contexts](source_contexts.json)
- [Quality report and possible duplicate pairs](quality_report.json)
- [Original LarnEDU PDF](https://www.larnedu.com/wp-content/uploads/2019/03/Jamb-Principles-Of-Accounts-Past-Questions-1983-2004-BY-LarnEdu.pdf)

## Extraction and review

Two PDF reading orders were merged by source page, column and question number. Option labels with missing spaces and clearly separated bare labels were recognized. Headings were removed before extraction. Instructions introducing the next shared scenario were separated from the preceding option. No corrections to business facts or answer inference are implied.

All IDs and normalized question-plus-option fingerprints are unique. Option order is ignored; case, numbers and punctuation are retained. 0 exact duplicate occurrences were removed after merging extraction passes. 0 similar-stem pairs are listed for review. Differently worded duplicates may remain.

Two additional duplicates were removed after comparing the partnership and hockey club tables, options and source locations. The quality report records them; retained IDs have gaps. Automated structural checks and sample review are not a full audit.

293 records are flagged for shared-context review, 21 for visual review, 169 for calculations or notation, and 29 for historical context. These groups overlap. Short stems are conservatively flagged because names and phrases such as “the document” can refer to an earlier scenario. Flags are heuristic and do not replace checking every record.

Each record links to its source PDF page and raw column text. Debit and credit columns, T-accounts, brackets indicating negative values and currency units require particular care. Check adjacent columns and pages for continued questions, tables, balance sheets, documents and shared business scenarios. Raw context text can itself be jumbled. Images are not extracted or hosted; image_url is null. Restore missing context, repair text and options, and verify answers before setting approved_for_bot to true.

Year is null because source headings and reading order are unreliable. Numbering, source authenticity, wording and option associations are not fully verified. Historical laws, institutions and business practices need exam-date and syllabus review. Passing structural checks does not establish correctness.

## Attribution and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing but prohibit direct or indirect monetisation. Exam-body rights have not been independently verified. This collection is not cleared for a paid or ad-supported bot.
