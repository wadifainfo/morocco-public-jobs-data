# Morocco upcoming public recruitment exams — calendar

Every Moroccan civil-service recruitment exam (concours) with an exam date still to come, as announced on the official public-employment portal: employer (French and Arabic), grade, specialty, number of posts, required diploma, region and city, publication date, application deadline, **exam date**, the official notice on emploi-public.ma, and the exam's page on Wadifa Info (French and Arabic).

**Snapshot of 25 November 2026: 364 exams, 22,373 posts.** This dataset is refreshed monthly; each refresh replaces the file (see the commit history for past snapshots).

| column | description |
|---|---|
| id | exam id on Wadifa Info |
| employer_fr, employer_ar | recruiting administration |
| grade_fr, grade_ar, specialty_fr | grade and specialty |
| posts | number of posts |
| diploma_fr, region_fr, city_fr | required diploma, place |
| published, application_deadline, exam_date | dates (YYYY-MM-DD) |
| recruitment_type_fr | regular recruitment, contract, etc. |
| official_notice | the notice on emploi-public.ma (the reference) |
| page_url_fr, page_url_ar | the exam's page on Wadifa Info (lists, results, past papers) |

## Source and caveats
Exam data comes from the official notices published on emploi-public.ma, collected by Wadifa Info. Dates can change after publication: the official notice is the reference. Live calendar: [Calendrier des concours au Maroc](https://www.wadifa-info.com/fr/calendrier-concours-maroc).

Related datasets: [results timing](https://huggingface.co/datasets/wadifainfo/morocco-public-exam-results-timing) · [recruitment notices since August 2026](https://huggingface.co/datasets/wadifainfo/morocco-public-recruitment-notices) · [past exam papers index](https://huggingface.co/datasets/wadifainfo/morocco-public-exam-papers-index).

Licence: CC BY 4.0. Prepared by Wadifa Info.


Also on Hugging Face: https://huggingface.co/datasets/wadifainfo · part of [morocco-public-jobs-data](../../README.md).
