# inscore

all lines insurance license Texas course and materials

Study set for the Texas all-lines insurance adjuster license. Texas statutes, TDI pages, and TDI-prescribed forms lead. National forms are included where a card asks about that form. California course notes, IRMI, Cornell, and Wikipedia are marked general-concept only.

## Start here

[STUDY_PLAN.md](STUDY_PLAN.md) is the reading order. One file per section is in [reading/](reading/).

The sourced pass scored 511 of 597 on the first blind round. The final tally is 566 cards that match the key with a citation, 24 key discrepancies (the key looks outdated against current Texas law), and 7 unsupported cards. Details are in [reports/summary.md](reports/summary.md). On a discrepancy, study the sourced answer in [data/final_answers.csv](data/final_answers.csv).

## Layout

| Path | What it is |
| --- | --- |
| [data/questions.txt](data/questions.txt) | 597 cards, each tagged `CARD-NNNN` and its source deck |
| [data/answer_key.txt](data/answer_key.txt) | Original answer key. Its header says the answers are unverified |
| [data/final_answers.csv](data/final_answers.csv) | Sourced answer, citations, rounds, final grade, and note for each card |
| [data/final_answers.jsonl](data/final_answers.jsonl) | Same pass, with the matched snippet from each cited page |
| [data/card_sections.csv](data/card_sections.csv) | Which study section and subtopic each card is in |
| [sources/citations.csv](sources/citations.csv) | Round-1 citation list |
| [sources/citations_final.csv](sources/citations_final.csv) | Cleaned citations and how many cards each source supports |
| [sources/removed_sources.csv](sources/removed_sources.csv) | Citations removed, and why |
| [sources/top_sources.md](sources/top_sources.md) | Ranked sources |
| [reports/summary.md](reports/summary.md) | Scores, the 24 discrepancies, and the 7 unsupported cards |
| [reports/grades_round1.csv](reports/grades_round1.csv) | Round-1 grade for every card |
| [reports/grades_round2.csv](reports/grades_round2.csv) | Round 2, the cards round 1 missed |
| [reports/grades_round3.csv](reports/grades_round3.csv) | Round 3, the cards still unsupported after round 2 |
| [reading/](reading/) | Assigned reading, key facts, and a self-check for each section |

The summary's closing file list uses the research-pass filenames. The table above is where those files live in this repo.

## Sections

The plan is 10 sections, in study order. Sections 1 and 3 are long enough to split across two sittings. The pace is flexible.

1. Insurance basics and contract law (179)
2. Negligence and liability law (31)
3. Dwelling, homeowners, and the Texas forms (92)
4. Personal auto and the Texas PAP (65)
5. Commercial property, the package policy, and Texas BOP (46)
6. CGL and other commercial liability (45)
7. Workers' compensation and the Texas Labor Code (44)
8. Surety, crime, marine, flood, and equipment breakdown (34)
9. Texas adjuster licensing, regulation, and ethics (41)
10. Claims handling, the DTPA, and unfair practices (20)
