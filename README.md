# Morocco public jobs data

Open datasets on public-sector employment in Morocco, compiled from official sources by [Wadifa Info](https://www.wadifa-info.com) and released under **CC BY 4.0**.

| Dataset | Rows | Folder | Live page |
|---|---|---|---|
| Civil-service net salaries by grade, 2026 | 370 grades, 71 corps | [`data/salaries`](data/salaries) | [Grille salariale de la fonction publique](https://www.wadifa-info.com/fr/grille-salariale-fonction-publique-maroc) |
| Civil-service gross and net pay by step (échelon), 2026 | 307 grades, 2394 rows | [`data/salaries`](data/salaries) | [Simulation salaire fonction publique](https://www.wadifa-info.com/fr/calcul-des-salaires-fonction-publique-maroc) |
| CRMEF teacher-training seats 2024/2025, by specialty and region | 14,450 seats | [`data/crmef-seats`](data/crmef-seats) | [مناصب مباراة التعليم حسب التخصص](https://www.wadifa-info.com/مناصب-مباراة-التعليم-حسب-التخصص) |
| Index of past public-sector exam papers, 1988–2026, with links to 27 interactive QCMs | 5,189 papers | [`data/exam-papers`](data/exam-papers) | [Modèles de concours](https://www.wadifa-info.com/fr/modeles-concours) · [QCM des concours](https://www.wadifa-info.com/fr/qcm-concours) |
| School practice tests with full corrections and printable PDFs, 5th primary to Tronc commun (فروض محروسة مع التصحيح) | 138 tests | [`data/practice-tests`](data/practice-tests) | [Devoirs surveillés corrigés](https://www.wadifa-info.com/fr/devoirs-surveilles-corriges) |
| Real past-exam MCQs (civil service and teachers), Arabic / French / English, with answer source | 1,575 questions, 44 papers | [`data/past-exam-mcq`](data/past-exam-mcq) | [QCM des concours](https://www.wadifa-info.com/fr/qcm-concours) |
| Ministry of Education documents removed from men.gov.ma (2025 exam frameworks, concours descriptions), dead URL → working copy | 146 documents | [`data/men-removed-documents`](data/men-removed-documents) | [Documents officiels archivés](https://www.wadifa-info.com/fr/documents-officiels-men-archives) |
| Public-service recruitment notices, Aug 2024 – Oct 2026 (one row per concours) | 8,582 concours, 104,875 posts | [`data/concours`](data/concours) | [Qui recrute dans la fonction publique ?](https://www.wadifa-info.com/fr/qui-recrute-fonction-publique-maroc) |
| Arabic–French glossary of civil-service terms (grades, employers) | 924 pairs | [`data/glossary`](data/glossary) | [Grille salariale](https://www.wadifa-info.com/fr/grille-salariale-fonction-publique-maroc) |
| Data studies 2026: posts per 100k by region, entry salary by diploma, recruitment fragmentation 2012–2025, 2026 vs 2025 | 4 tables | [`data/studies`](data/studies) | [Statistiques du recrutement](https://www.wadifa-info.com/fr/statistiques-recrutement-fonction-publique-maroc) |
| Minimum wage (SMIG/SMAG) history, 1971–2026, with decree and Bulletin officiel per change | 35 changes | [`data/minimum-wage`](data/minimum-wage) | [Historique du SMIG au Maroc](https://www.wadifa-info.com/fr/historique-smig-maroc) |
| Budget posts created by each finance law, 2020–2027, total and by department | 8 years, 11 departments | [`data/budget-posts`](data/budget-posts) | [Postes budgétaires](https://www.wadifa-info.com/fr/postes-budgetaires-maroc) |
| Religious holiday dates observed in Morocco, 2000–2026, with the Saudi date | 149 rows | [`data/religious-holidays`](data/religious-holidays) | [Dates des fêtes religieuses](https://www.wadifa-info.com/fr/dates-fetes-religieuses-maroc-historique) · [English](https://www.wadifa-info.com/en/morocco-islamic-holiday-dates-2000-2026) |
| Open concours snapshot, 2 November 2026 (one row per open concours) | 193 concours, 70 employers | [`data/concours-open`](data/concours-open) | [Concours et emplois publics au Maroc](https://www.wadifa-info.com/fr/concours-emplois-publics-maroc) |
| Exam results timing: days from deadline to written, oral and final lists, by stage and employer (Aug–Oct 2026) | 4 stages, 59 employers | [`data/results-timing`](data/results-timing) | [Délai des résultats des concours](https://www.wadifa-info.com/fr/delai-resultats-concours-maroc) |
| Upcoming public recruitment exams with exam date (snapshot 25 Nov 2026, refreshed monthly) | 364 exams, 22,373 posts | [`data/upcoming-exams`](data/upcoming-exams) | [Calendrier des concours](https://www.wadifa-info.com/fr/calendrier-concours-maroc) |
| Professional-aptitude exams of Moroccan communes (امتحانات الكفاءة المهنية للجماعات): papers by grade and the 25 recurring themes | 158 papers, 25 themes | [`data/commune-exam-topics`](data/commune-exam-topics) | [نماذج امتحانات الكفاءة المهنية للجماعات الترابية](https://www.wadifa-info.com/نماذج-مباريات/امتحانات-الكفاءة-المهنية/الجماعات-الترابية) |
| Organic Law 113-14 on communes, Arabic text article by article | 283 articles | [`data/law-113-14`](data/law-113-14) | [Examens d'aptitude des communes](https://www.wadifa-info.com/نماذج-مباريات/امتحانات-الكفاءة-المهنية/الجماعات-الترابية) |
| Moroccan embassies and consulates abroad, with consular district | 161 posts | [`data/diplomatic-posts`](data/diplomatic-posts) | [Consulats et ambassades du Maroc](https://www.wadifa-info.com/fr/consulats-ambassades-maroc-etranger) |
| OFPPT course documents catalogue (module, trade, year, link) | 739 documents | [`data/ofppt-documents`](data/ofppt-documents) | [Cours OFPPT PDF](https://www.wadifa-info.com/fr/cours-ofppt-pdf) |

Each folder has its own README with the columns, the official source and the limits of the data. Files are UTF-8 CSV or JSON Lines.

Website: https://wadifainfo.github.io/morocco-public-jobs-data/

For a thesis or a research project, start with the [data catalogue](https://www.wadifa-info.com/fr/donnees-memoire-pfe-fonction-publique): variable dictionary, ready-made citations and direct CSV links ([Arabic version](https://www.wadifa-info.com/بيانات-مفتوحة-لمذكرات-التخرج)).

## Analysis built on this data

- [Net pay by grade under the 2027 finance bill (bill, not law)](https://www.wadifa-info.com/fr/augmentation-salaire-2027-par-grade)
- [2027 income-tax simulator](https://www.wadifa-info.com/fr/simulateur-ir-2027-maroc)
- [Time from notice to results, by employer](https://www.wadifa-info.com/fr/delai-resultats-concours-maroc)
- [Public-sector posts per 100,000 inhabitants, by region](https://www.wadifa-info.com/fr/emploi-public-par-region)
- [Exam language, from the notices](https://www.wadifa-info.com/fr/langue-epreuves-concours)
- [Civil service in figures](https://www.wadifa-info.com/fr/fonction-publique-maroc-en-chiffres)
- [Time in Morocco: GMT since 20 September 2026](https://www.wadifa-info.com/en/morocco-time-zone)
- [Minimum wage in Morocco 2026](https://www.wadifa-info.com/en/morocco-minimum-wage)
- [CNSS and AMO contribution rates 2026](https://www.wadifa-info.com/en/morocco-social-security-contributions)
- [Severance pay in Morocco](https://www.wadifa-info.com/en/morocco-severance-pay)
- [Overtime and working hours in Morocco](https://www.wadifa-info.com/en/morocco-overtime-pay)
- [Annual leave in Morocco](https://www.wadifa-info.com/en/morocco-annual-leave)

## Live API and MCP server
- Embeddable widgets (iframe, free): https://www.wadifa-info.com/widget/jours-feries (next public holidays, ?lang=en|ar), https://www.wadifa-info.com/widget/vacances-scolaires (next school breaks, ?lang=ar)
- Free JSON API (no key, CC BY 4.0): https://www.wadifa-info.com/en/api, spec at https://www.wadifa-info.com/openapi.json
- MCP server for AI agents (Claude, ChatGPT, Cursor): `https://www.wadifa-info.com/mcp` (Streamable HTTP, no key), listed in the official MCP registry as `com.wadifa-info.www/morocco-public-jobs`

## Also published on
- Zenodo (DOI): https://doi.org/10.5281/zenodo.23078291 (salaries); https://doi.org/10.5281/zenodo.23241447 (data studies 2026)
- Hugging Face: https://huggingface.co/wadifainfo (salaries, recruitment notices, exam-paper index, QCM, budget posts, CRMEF seats, minimum wage, holiday dates)

## Cite

Recruitment notices + glossary: [doi:10.5281/zenodo.23296468](https://doi.org/10.5281/zenodo.23296468) · Interactive demo: [Hugging Face Space](https://huggingface.co/spaces/wadifainfo/morocco-public-jobs-salaries)

> Wadifa Info (2026). *Morocco public jobs data*. https://doi.org/10.5281/zenodo.23078291

## License
Data: [CC BY 4.0](LICENSE). Credit as: "Source: Wadifa Info, https://www.wadifa-info.com" with a link to the dataset or page used, and say if you changed the data.

## Updates and corrections
Figures follow the live pages on wadifa-info.com, which are updated when a new official text is published. Found an error? Open an issue with a link to the official source.

---
**Français :** jeux de données ouverts sur l'emploi public au Maroc (salaires nets par grade, places CRMEF, index des modèles de concours), sources officielles, licence CC BY 4.0.

**العربية:** بيانات مفتوحة حول الوظيفة العمومية بالمغرب (الأجور الصافية حسب الدرجة، مقاعد المراكز الجهوية لمهن التربية والتكوين، فهرس نماذج المباريات)، رخصة CC BY 4.0.
