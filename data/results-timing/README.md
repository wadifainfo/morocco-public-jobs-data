# Morocco public-exam results timing: days from the application deadline to each list

How long does a candidate to a Moroccan civil-service recruitment exam (concours) wait for the next list? No official figure exists. Wadifa Info records the publication date of every list attached to a recruitment notice (shortlist for the written exam, shortlist for the oral, final results, waiting list) and measures the delay in calendar days after the application deadline.

- **Files:** `results_timing_by_stage.csv`, `results_timing_by_employer.csv` (UTF-8 with BOM)
- **Rows:** 4 stages (2,604 lists); 59 employers with enough lists. Each employer row links that employer's concours page on Wadifa Info.
- **Observation window:** lists observed from 31 July 2026 (notices with a deadline from August 2026) to 30 October 2026.
- **No personal data:** publication dates only. No candidate names.
- **Licence:** CC BY 4.0. Credit as "Source : Wadifa Info" with the `url` of each row you reuse.
- **Source:** notices and lists on emploi-public.ma, collected by Wadifa Info. Live tables and method: [Délai des résultats des concours](https://www.wadifa-info.com/fr/delai-resultats-concours-maroc) · [متى تظهر نتائج المباريات](https://www.wadifa-info.com/%D9%85%D8%AA%D9%89-%D8%AA%D8%B8%D9%87%D8%B1-%D9%86%D8%AA%D8%A7%D8%A6%D8%AC-%D8%A7%D9%84%D9%85%D8%A8%D8%A7%D8%B1%D9%8A%D8%A7%D8%AA). Notices are also in the free [JSON API](https://www.wadifa-info.com/en/api).

## Columns: `results_timing_by_stage.csv`
| Column | Meaning |
|---|---|
| `stage` | `written_exam_shortlist`, `oral_exam_shortlist`, `final_results` or `waiting_list` |
| `stage_fr` | Stage name in French |
| `q1_days`, `median_days`, `q3_days` | First quartile, median and third quartile of the delay, in days after the deadline |
| `n_lists` | Number of lists measured |
| `url` | Page with the live table |

## Columns: `results_timing_by_employer.csv`
| Column | Meaning |
|---|---|
| `employer_fr` | Employer name as published |
| `written_median_days`, `written_n` | Median delay to the written-exam shortlist, and number of lists |
| `oral_median_days`, `oral_n` | Same for the oral-exam shortlist |
| `final_median_days`, `final_n` | Same for the final results |
| `url`, `url_ar` | Employer's concours page on Wadifa Info, in French and in Arabic |

Empty = not enough lists for that stage.

## Limits
- Preliminary: biased towards short delays, because slow results are not all observed yet.
- These are observed publication dates, not official dates. The official notice prevails.

## Citation
Wadifa Info (2026). *Morocco public-exam results timing* [Data set]. https://www.wadifa-info.com/fr/delai-resultats-concours-maroc — CC BY 4.0.
