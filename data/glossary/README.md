# Arabic–French glossary of Moroccan civil-service terms

`ar_fr_civil_service_terms.csv`: 924 Arabic–French pairs from Moroccan public administration.
- **grade** (489): job grades. 307 come from the official salary simulator (simulation.mmsp.gov.ma). The others come from recruitment notices.
- **employer** (435): ministries, agencies, universities, hospitals, provinces and communes.

Columns: `type`, `arabic`, `french`, `source`.

**How it was built**
- Recruitment notices are those published on emploi-public.ma from August 2024 to September 2026; see `../concours/`.
- A notice pair is kept only if it appears in at least 3 notices. When one Arabic term has several French versions, only the most frequent is kept.
- Pairs are kept **as published**: original capitalisation, abbreviations and occasional typos are not corrected.

**Uses**
- Terminology lists and translation memories for administrative MSA ⇆ French.
- Evaluating machine translation on official Moroccan vocabulary.
- Entity linking of employers.

**Licence and credit:** CC BY 4.0. Credit "Wadifa Info" with a link to https://www.wadifa-info.com.
