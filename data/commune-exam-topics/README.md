# Morocco local-government professional exam topics (2010–2021)

What do Moroccan communes, provinces and prefectures ask in the **professional aptitude exam** (امتحان الكفاءة المهنية) that their staff sit for promotion? This dataset maps **158 real past exam papers** (administrators, clerks, technicians, administrative and technical assistants) to the questions they ask and to **25 recurring themes**.

- `papers.jsonl` — one row per paper: grade, year, employer, the topics asked (Arabic paraphrase of each question), the themes it falls under, and a link to the paper's page (scan, free).
- `themes.jsonl` — one row per theme: number of papers that ask it, breakdown by grade, years, example questions with paper ids.

Top themes: the staff member's role in the commune (47 papers), modernising the administration and service to citizens (43), local development and the commune's action programme (29), human resources and training (24), the commune's powers under Organic Law 113.14 (23), digital administration (20), good governance and accountability (20).

## Method and limits
Topics were read from the OCR of each scan and grouped into themes by hand-checked clustering; counts are papers per theme (one paper can count under several themes). 71 of the 158 papers are from 2018 and 14 have no year, so counts mostly reflect 2016–2019. OCR is noisy: 2 papers are marked unreadable and 33 have partly-read topics.

## Source
Papers from the Wadifa Info exam-paper library (scans of papers that circulated publicly). Browse them by grade: [نماذج امتحانات الكفاءة المهنية – الجماعات الترابية](https://www.wadifa-info.com/نماذج-مباريات/امتحانات-الكفاءة-المهنية/الجماعات-الترابية).

Related: [Organic Law 113.14 on communes, machine-readable](https://huggingface.co/datasets/wadifainfo/morocco-organic-law-113-14-communes).

Licence: CC BY 4.0 (the topic map and counts). Cite as: Wadifa Info (2026). *Morocco local-government professional exam topics*.


Also on Hugging Face: https://huggingface.co/datasets/wadifainfo · part of [morocco-public-jobs-data](../../README.md).
