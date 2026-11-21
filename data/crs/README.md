# Christian Religious Studies (CRS / CRK) — 970 draft questions

Target **1,000**; extracted draft **970**; shortfall **30**. All questions have four or five labelled options. Correct answers and explanations are blank pending verification; every record has `approved_for_bot: false`.

- [CSV for spreadsheets](crs_candidates.csv)
- JSON for database import: [Part 1 (485 questions)](crs_candidates_part_01.json), [Part 2 (485 questions)](crs_candidates_part_02.json)
- [JSON manifest and counts](crs_manifest.json)
- [Raw source-column contexts](source_contexts.json)
- [Quality report, duplicate log and formatting repairs](quality_report.json)
- [Original LarnEDU PDF](https://www.larnedu.com/wp-content/uploads/2019/03/JAMB-Christian-Religious-Studies-CRS-Past-Questions-1983-2004-1.pdf)

The CSV contains all 970 records. For JSON import, concatenate the two arrays listed in the manifest. The parts are disjoint and together contain exactly the same records as the CSV.

## Extraction and duplicate checks

Two PDF reading orders were merged by page, column and extracted question number. Page headings were removed and recognizable option labels were normalized. 17 exact duplicate occurrences were removed initially, 8 additional normalized repeats were removed, and 17 repeated questions were removed after reviewing their wording and options. The source repeats material under a second 1989 heading.

All retained IDs and fingerprints are unique. Fingerprints ignore capitalization, quotation-mark style, option order and terminal full stops while retaining words and numbers. IDs have gaps because excluded records retain their original identifiers in the review log. 0 similar-stem pair(s) remain for review; differently worded duplicates can still exist. Two explicit formatting repairs are recorded in the quality report. No answers or filler questions were generated.

## Before using in a bot

Verify biblical names, quotation wording, speaker, narrative context and the correct answer against the relevant passage and exam requirements. Source spelling and transcription mistakes remain. The cover says “Questions And Answers”, but an answer key was not identified in the PDF.

408 records have shared-context review flags and 358 have quotation-review flags; these groups overlap. A quotation may already be present in the stem. Source-page links and raw column contexts help recover missing information. Raw text itself may be jumbled; check adjacent columns/pages when a question continues. Images are not hosted and image_url is null.

The filename and cover say 1983–2004, while running headers also say 1983–2003. Repeated or misplaced year headings make individual question years unreliable, so year is null. Source numbering and exam authenticity are not fully verified. These are extraction drafts, not a validated teaching dataset.

## Attribution and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing but prohibit direct or indirect monetisation. Exam-body rights have not been independently verified. This collection is not cleared for a paid or ad-supported bot.
