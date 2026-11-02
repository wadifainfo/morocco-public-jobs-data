# Morocco open public-service concours: snapshot of 2 November 2026

The recruitment exams (concours) still open for applications on 2 November 2026, as listed by Wadifa Info from notices on the official portal emploi-public.ma. Each row links the notice page, in French and in Arabic. For the full history, see [`data/concours`](../concours).

- **File:** `open-2026-11-02.csv` (UTF-8 with BOM)
- **Rows:** 193 concours from 70 employers. 176 notices state the number of posts, 839 in total; the other 17 do not.
- **Sorted by:** application deadline, soonest first.
- **No personal data:** notices only. No candidate lists.
- **Licence:** CC BY 4.0. Credit as "Source : Wadifa Info" with the `url` of each row you reuse.
- **Source:** notices on emploi-public.ma, collected by [Wadifa Info](https://www.wadifa-info.com/fr/concours-emplois-publics-maroc). The same data is available live from the [JSON API](https://www.wadifa-info.com/en/api). Dates in the official notice prevail.

## Columns
| Column | Meaning |
|---|---|
| `id` | Wadifa Info notice id (the page is `url`) |
| `published` | Date the notice appeared on emploi-public.ma (YYYY-MM-DD) |
| `deadline` | Application deadline, empty if not given |
| `exam_date` | Exam date announced in the notice, empty if not given |
| `employer_type` | `administration_etat`, `etablissement_public` or `collectivite_territoriale` |
| `employer_fr`, `employer_ar` | Employer name as published |
| `grade_fr`, `grade_ar` | Grade (post) opened |
| `posts` | Number of posts, empty if the notice does not state it |
| `region_fr`, `city_fr` | Place of work when known |
| `diplomas_fr`, `specialties_fr` | Required diplomas and specialties, separated by `; ` |
| `recruitment_type_fr` | Regular recruitment or contract |
| `net_monthly_salary_mad` | Net monthly pay for the grade from the [civil-service pay grid](https://www.wadifa-info.com/fr/grille-salariale-fonction-publique-maroc), empty when the grade is not on the grid |
| `url`, `url_ar` | Notice page in French and in Arabic, with the link to the official announcement |

## Limits
- A snapshot: deadlines pass and notices change after the date above. Check the notice before applying.
- Region and city are empty when the notice does not give a single place of work. For a multi-site employer they follow the employer's seat, which may differ from the post.
- Diplomas and specialties are free text from the notices.
