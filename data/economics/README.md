# Economics — 923 draft records

Updated 24 November 2026: **19 additional draft records** were recovered from the existing source PDF and screened. The requested expansion of 1,000 per subject remains incomplete; 981 additions remain for this subject.

- [Additional JSON](economics_additional_2026_11_24.json)
- [Additional CSV](economics_additional_2026_11_24.csv)
- [Complete repository import manifest](../manifest.json)
- [Current expansion report](../../research/expansion_progress_2026_11_24.json)

Load the original batch plus this additional batch, using one format only. Answers are blank and all new records have approved_for_bot set to false. The original quality report describes the original batch; the current expansion report covers the additions. Existing records have been preserved.

## Original batch documentation

# Economics — 904 draft questions

Target: **1,000**. Extracted draft: **904**. Shortfall: **96**.

Every record contains a question and four or five labelled options. All still need review. Correct answers and explanations are blank, and `approved_for_bot` is false throughout. No answers or filler questions were generated.

## Files

- [CSV for spreadsheets](economics_candidates.csv)
- [JSON for database import](economics_candidates.json)
- [Raw source-column contexts](source_contexts.json)
- [Quality report and duplicate review lists](quality_report.json)
- [Original LarnEDU PDF with graphs and tables](https://www.larnedu.com/wp-content/uploads/2019/03/JAMB-Economics-Past-Questions-1983-2004.pdf)

## Duplicate and extraction checks

Two reading orders were merged by page, column and extracted question number. Recognizable option labels were normalized and headings were removed. 38 exact duplicate occurrences were removed. All retained IDs and fingerprints are unique. Fingerprints normalize Unicode and whitespace and ignore option order while retaining case, numbers, punctuation and symbols because these can change mathematical meaning.

Three additional duplicates were removed after comparing wording and options, and one record with a truncated option was excluded. The quality report records these exclusions. IDs retain their original values, so there are gaps.

4 similar-stem pairs remain for review. They are not automatically removed: different numbers, options or graph contexts can change the question. This is not a guarantee of semantic uniqueness.

## Graphs, tables and other irregular questions

There are 92 graph/diagram review flags, 112 shared-context flags, 110 calculation/notation flags and 26 historical-context flags. These categories overlap and are heuristic. Mentioning a curve can trigger a flag even when no image is needed.

Images are not hosted; `image_url` is null. Every question has a source-page link and a raw column context reference. Raw context text is an aid to review, not a substitute for the PDF: table columns, graph labels, subscripts, fractions and currency symbols can be lost or jumbled. A question can continue onto the next column or page. Keep affected questions unavailable until the missing material is correctly attached and checked.

Source years are deliberately null. The PDF filename/cover says 1983–2004 while its running header says 1983–2003, and internal heading order is unreliable. Source numbering, authenticity, spelling and option associations have not been fully verified. All records need text and answer review, including those without flags. Historical facts must be checked in the original exam context.

## Attribution and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing but prohibit direct or indirect monetisation. Exam-body rights have not been independently verified. This collection is not cleared for a paid or ad-supported bot.
