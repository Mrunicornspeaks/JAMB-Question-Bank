# JAMB question bank — 8,217 draft records

Extracted past-question candidates for 10 subjects. These are unverified drafts, not a validated teaching-bot database.

## Expansion requested on 24 November 2026

The request is **1,000 additional questions per existing subject**, or 10,000 additions. **79 English draft records were added; 9,921 additions remain.** No additions were made to the other nine subjects in this batch.

| Subject | Current drafts | Added this batch | Requested final total |
| --- | ---: | ---: | ---: |
| [Use of English](data/english/) | 1079 | 79 | 2000 |
| [Mathematics](data/mathematics/) | 737 | 0 | 1737 |
| [Biology](data/biology/) | 923 | 0 | 1923 |
| [Physics](data/physics/) | 842 | 0 | 1842 |
| [Chemistry](data/chemistry/) | 865 | 0 | 1865 |
| [Government](data/government/) | 963 | 0 | 1963 |
| [Economics](data/economics/) | 904 | 0 | 1904 |
| [Commerce](data/commerce/) | 476 | 0 | 1476 |
| [Principles of Accounts](data/accounts/) | 458 | 0 | 1458 |
| [Christian Religious Studies](data/crs/) | 970 | 0 | 1970 |
| **Total** | **8,217** | **79** | **18,138** |

[Expansion progress and checks](research/expansion_progress_2026_11_24.json)

## Download and import

Use **Code → Download ZIP** for the repository, or open a CSV/JSON file and select **Download raw file**.

- English: load both parts listed in [the English manifest](data/english/manifest.json). The original english_1000 files retain their original 1,000 records; the additional batch contains 79.
- [Additional English CSV](data/english/english_additional_2026_11_24.csv)
- [Additional English JSON](data/english/english_additional_2026_11_24.json)
- Other subjects: follow each subject folder's README. CRS has split JSON files and a manifest.
- Choose either CSV or JSON when importing; do not import both representations as separate questions.

## Quality status

Answers and explanations are unverified and generally blank. Questions and year labels come from third-party compilations and have not been authenticated against original JAMB papers. Structural and duplicate checks do not establish educational accuracy or semantic uniqueness.

The 79 new English records have four options, unique IDs and normalized question/option signatures, no exact overlap with the original English bank, and source-page matches. They require the corresponding comprehension passage from the external PDF. Passage text is not embedded in this batch. All 79 have approved_for_bot set to false; none has a verified answer.

Other subjects contain records requiring diagram, table, notation and context review. Read their quality reports before use.

Known issues in the original English batch include mismatched options in JAMB-ENG-1990-087, trailing passage-header text in JAMB-ENG-1986-100, and a suspicious source number in JAMB-ENG-1986-005. This expansion does not repair those existing records. [Original English notes](data/english/NOTES.md)

## Sources and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing and prohibit direct or indirect monetisation. Exam-body and third-party passage rights have not been independently verified. This repository does not grant an unrestricted licence and is not cleared for a paid or ad-supported bot.

Additional reusable sources are still needed to complete the expansion. [Literature, IRS, Computer Studies and Hausa source research](research/literature_irs_computer_hausa_sources.json) does not contain question additions.
