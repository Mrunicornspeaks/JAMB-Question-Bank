# JAMB question bank — 8,339 draft records

Extracted past-question candidates for 10 subjects. These are unverified drafts, not a validated teaching-bot database.

## Expansion status — 24 November 2026

The request is **1,000 additional questions per existing subject**, or 10,000 additions. **201 draft records have been added: 79 English records, 97 records in the first recovery batch, and 25 records in the latest manual recovery batch. 9,799 additions remain.** Commerce has no additions.

| Subject | Current drafts | Cumulative additions | Requested final total |
| --- | ---: | ---: | ---: |
| [Mathematics](data/mathematics/) | 761 | 24 | 1737 |
| [Biology](data/biology/) | 955 | 32 | 1923 |
| [Physics](data/physics/) | 847 | 5 | 1842 |
| [Chemistry](data/chemistry/) | 872 | 7 | 1865 |
| [Government](data/government/) | 990 | 27 | 1963 |
| [Economics](data/economics/) | 928 | 24 | 1904 |
| [Commerce](data/commerce/) | 476 | 0 | 1476 |
| [Principles of Accounts](data/accounts/) | 460 | 2 | 1458 |
| [Christian Religious Studies](data/crs/) | 971 | 1 | 1970 |
| [Use of English](data/english/) | 1079 | 79 | 2000 |
| **Total** | **8,339** | **201** | **18,138** |

[Expansion progress, checks and exclusions](research/expansion_progress_2026_11_24.json)

## Download and import

Use **Code → Download ZIP** for the complete repository, or open a CSV/JSON file and select **Download raw file**.

Follow the [complete import manifest](data/manifest.json). Choose JSON or CSV and load every listed part for each subject. Do not import both formats as separate questions. Original files retain their original counts; additions are in separate dated files. Deduplicate by id.

## Quality status

Answers and explanations are unverified and generally blank. Questions and year labels come from third-party compilations and have not been authenticated against original JAMB papers. Structural and duplicate checks do not prove educational accuracy or semantic uniqueness.

The latest 25 records were manually recovered from source PDF page images and checked against both original and previously added subject records. One repaired Economics candidate was excluded as a near duplicate. The batch adds 9 Mathematics, 6 Biology, 5 Economics, 3 Physics and 2 Chemistry records. Source-page links and transcription changes are recorded. These remain drafts: source wording errors are documented, subject review is still required, answers and explanations are null, and approved_for_bot is false. Earlier batches still require visual and subject review.

The earlier 79 English additions require comprehension passages available from their external PDF links. Passage text is not embedded in that batch. Other subject records may require diagram, table, notation or context review; consult their quality reports.

Known issues in the original English batch include mismatched options in JAMB-ENG-1990-087, trailing passage-header text in JAMB-ENG-1986-100, and a suspicious source number in JAMB-ENG-1986-005. This expansion does not repair those existing records. [Original English notes](data/english/NOTES.md)

## Sources and reuse

Credit: **LarnEDU**. [Publisher terms](https://www.larnedu.com/jamb-past-practice-questions/) permit credited sharing and prohibit direct or indirect monetisation. Exam-body and third-party passage rights have not been independently verified. This repository does not grant an unrestricted licence and is not cleared for a paid or ad-supported bot.

More reusable sources are needed to complete the expansion. [Literature, IRS, Computer Studies and Hausa research](research/literature_irs_computer_hausa_sources.json) contains source findings, not question additions.
