# Crew Toolkit — sources

This lists where each part of the app comes from, so it can be checked and kept up to date.

A scheduled check runs on the 1st of every month. It works through this list and checks every link in the app. If something has changed, it opens a pull request that explains the change in plain English, with the source, for Paul to approve. **Nothing changes on the live app until that pull request is merged.** If nothing has changed, no pull request is opened.

## Rules for any update

- Every change cites an official source, linked in the pull request.
- Facts only, in our own words. No text copied from JRCALC (© AACE) or any other subscription source, and no drug doses.
- Hospital codes come from Paul. The check never changes them.
- If a source is unclear or only partly readable, nothing is changed. It goes in the pull request under "Needs your judgement".
- Only the parts affected by a change are edited. index.html stays a single self-contained file.
- The ECG "What to do" pointers (the `DO` list in index.html) are short summaries in our own words, each with its sources named. Keep them that way: no doses, nothing copied from JRCALC.
- "My notes" on the ECG screen are stored only on the user's phone (browser storage). They are never in this repo and the check never touches them.

## Screen by screen

| Screen | What the app holds | Source | Version in app | Last checked |
|---|---|---|---|---|
| NEWS2 | Scoring bands, aggregate score, risk bands, clinical response | Royal College of Physicians — [NEWS2](https://www.rcp.ac.uk/resources/national-early-warning-score-news-2/) | December 2017 | 28 Oct 2026 |
| Overdose | Arithmetic only. No toxic thresholds are stored — the user enters them from TOXBASE | — | — | — |
| Guidance | 15 cards: "At hospital / Convey if / Alternative" summaries, each linking to the live source (list below) | NICE, JBDS, BSPED | As linked | — |
| Imaging | CT head and cervical spine decision tools | NICE [NG232](https://www.nice.org.uk/guidance/ng232/resources) imaging algorithms | 2023 | — |
| Bloods | Typical UK adult reference ranges; NT-proBNP cut-offs | General UK laboratory ranges; NICE NG106 for NT-proBNP | — | — |
| Under 2s | Developmental milestones | General developmental norms | — | — |
| Under 2s | Routine immunisation schedule, 8 weeks to 3 years 4 months | UKHSA — [The complete routine immunisation schedule](https://www.gov.uk/government/publications/the-complete-routine-immunisation-schedule) | From 1 September 2026 | 28 Oct 2026 |
| Maps | Hospital map links (list below) | Trust websites | — | — |
| ECG | STEMI thresholds (Normal ranges card) | Fourth Universal Definition of Myocardial Infarction | 2018 | 28 Oct 2026 — see open items |
| ECG | "What to do" pointers — arrhythmias, heart block, pacing, defibrillation with implanted devices | Resuscitation Council UK — [Adult ALS guidelines](https://www.resus.org.uk/library/2025-resuscitation-guidelines/adult-advanced-life-support-guidelines) and its tachyarrhythmia and bradyarrhythmia algorithms | 2025 guidelines; tachyarrhythmia algorithm V3, March 2026 | 28 Oct 2026 |
| ECG | "What to do" pointers — hyperkalaemia | Resuscitation Council UK — [Special circumstances](https://www.resus.org.uk/library/2025-resuscitation-guidelines/special-circumstances-guidelines) | 2025 | 28 Oct 2026 |
| ECG | "What to do" pointers — STEMI, NSTEMI and chest pain | NICE [NG185](https://www.nice.org.uk/guidance/NG185/chapter/Recommendations) (acute coronary syndromes) and [CG95](https://www.nice.org.uk/guidance/CG95/chapter/1-Guidance) (chest pain) | As published | 28 Oct 2026 |
| ECG | "What to do" pointers — bundle branch block, paced rhythm, posterior MI, left main pattern | [ESC guidelines for acute coronary syndromes](https://academic.oup.com/eurheartj/article/44/38/3720/7243210) | 2023 | 28 Oct 2026 |
| ECG | "What to do" pointers — AF and flutter | NICE [NG196](https://www.nice.org.uk/guidance/ng196) | Last updated June 2021 | 28 Oct 2026 |
| ECG | "What to do" pointers — pericarditis | [RCEM Learning — pericarditis](https://www.rcemlearning.co.uk/reference/pericarditis/) | — | 28 Oct 2026 |

## Guidance cards

| Card | Source |
|---|---|
| Suspected sepsis — 16 and over | [NICE NG253](https://www.nice.org.uk/guidance/ng253) |
| Stroke and TIA | [NICE NG128](https://www.nice.org.uk/guidance/ng128) |
| Acute coronary syndromes | [NICE NG185](https://www.nice.org.uk/guidance/ng185/resources) |
| Suspected PE | [NICE NG158 visual summary](https://www.nice.org.uk/guidance/ng158/resources/visual-summary-pdf-11193380893) |
| DKA — adults | [JBDS, hosted by ABCD](https://abcd.care/resource/management-diabetic-ketoacidosis-dka-adults) |
| DKA — children and young people | [BSPED](https://www.bsped.org.uk/clinical-resources/bsped-dka-guidelines/) |
| Head injury — CT imaging | [NICE NG232](https://www.nice.org.uk/guidance/ng232/resources) |
| Suspected DVT | [NICE NG158 visual summary](https://www.nice.org.uk/guidance/ng158/resources/visual-summary-pdf-11193380893) |
| Low back pain and sciatica | [NICE NG59](https://www.nice.org.uk/guidance/ng59) |
| Nosebleeds (epistaxis) | [NICE CKS](https://cks.nice.org.uk/topics/epistaxis-nosebleeds/) |
| Falls and long lie | [NICE NG249](https://www.nice.org.uk/guidance/ng249) |
| Suspected sepsis — under 16 | [NICE NG254](https://www.nice.org.uk/guidance/ng254) |
| Suspected sepsis — pregnant or recently pregnant | [NICE NG255](https://www.nice.org.uk/guidance/ng255) |
| Asthma | [NICE NG245](https://www.nice.org.uk/guidance/ng245) |
| Asthma pathway | [NICE NG244](https://www.nice.org.uk/guidance/ng244) |

For each card, look for: guidance updated, withdrawn, replaced or renumbered; recommendations that change what the "At hospital", "Convey if" or "Alternative" lines say; links that no longer open the right page.

## Maps

| Hospital | Link |
|---|---|
| Castle Hill | [Map (PDF)](https://www.nlg.nhs.uk/wp-content/uploads/2023/03/Castle-Hill-Hospital-Map.pdf) |
| Dove House Hospice | No map |
| Goole | [Map (PDF)](https://www.nlg.nhs.uk/wp-content/uploads/2023/03/Goole-2d-NOVEMBER-2022.pdf) |
| Grimsby — Diana, Princess of Wales | [Map (PDF)](https://www.nlg.nhs.uk/wp-content/uploads/2023/03/Diana-Princess-of-Wales-Hospital-internal-2D-2025.pdf) |
| Hull Royal Infirmary | [Map (PDF)](https://www.hey.nhs.uk/wp/wp-content/uploads/2024/04/Hull-Royal-Infirmary-Site-Map.pdf) |
| Scunthorpe General | [Map (PDF)](https://www.nlg.nhs.uk/wp-content/uploads/2023/03/SCUNTHORPE-2d-NOVEMBER-2022.pdf) |

Look for: links that no longer open, and newer versions of the same map on the same trust website.

## Open items

- **Fifth Universal Definition of Myocardial Infarction (ESC/ACC/AHA/WHF, August 2026).** It replaces the Fourth (2018). Its headline changes are to how MI is classified (primary, secondary and procedure-related instead of types 1–5) and sex-specific troponin limits. Its list of new concepts does not mention the ECG, and published commentary describes the STEMI thresholds as unchanged — but on 28 Oct 2026 the ECG section (section 13, table 5, figure 9) could not be opened online. Check that section. If the thresholds match, change the ECG note to cite the Fifth definition. Also report whether its "electrocardiographic features of acute coronary occlusion" would make useful new ECG examples.
