# Morocco civil-service net salaries by grade (2026)

Net monthly salary in Moroccan dirhams (MAD) for 370 grades of the Moroccan civil service, grouped by corps.

- **Rows:** 370 grades, 71 corps
- **Range:** 3,743 to 45,405 MAD net per month; unweighted mean across grades 13,334 MAD
- **Method:** base pay plus statutory allowances, minus pension (CMR) and income tax (IR), as returned by the official salary simulator of the Ministry of Digital Transition and Administration Reform (simulation.mmsp.gov.ma).
- **Settings:** first step (échelon) of each grade, single, no children, no mutuelle, locality in the higher residence-allowance zone. The same grade in Rabat or Casablanca is about 150–350 MAD (roughly 2%) lower.
- **Checked:** 320 of the 370 rows were matched to the simulator to the cent on 30 September 2026; the others are grades the simulator does not list under the same name.
- **Source and updates:** compiled and maintained by Wadifa Info from the official index grid: https://www.wadifa-info.com/fr/grille-salariale-fonction-publique-maroc
- **Licence:** CC BY 4.0. Please cite: "Grille salariale de la fonction publique marocaine 2026, Wadifa Info, https://www.wadifa-info.com/fr/grille-salariale-fonction-publique-maroc"

## Columns
| Column | Meaning |
|---|---|
| `corps_ar` | Corps (statutory body), in Arabic as published |
| `grade_fr` | Grade name in French |
| `net_monthly_salary_mad` | Net monthly salary, MAD |
| `source_url` | Page with the detailed breakdown for that grade |

## Limits
- Figures are first-step pay. A few first-step figures are below the 4,500 MAD public-sector minimum net wage in force since July 2025; the simulator returns them as such.
- The mean is across grades, not across civil servants; it is not the average civil-servant salary.
- Some corps appear under two spellings in the source and are kept as published.


## Pay by step (échelon): `morocco_civil_service_pay_by_echelon_2026.csv`

Gross and net monthly pay (MAD) for **every échelon** of 307 grades (39 corps), 2394 rows, added 8 October 2026.

- **Method and settings:** same official simulator and same settings as the table above (single, no children, no mutuelle, higher residence-allowance zone), one simulation per échelon, run on 8 October 2026.
- **Checks:** a grade is included only when its first-échelon net equals the by-grade table above to within 1 MAD, and when its net never falls by more than 2% from one échelon to the next. Five grades are left out because the official simulator itself returns such a drop.
- **Columns:** `grade_id`, `grade_fr`, `grade_ar`, `corps_fr`, `echelon` (`ex` = exceptional step), `indice`, `brut_mad`, `net_mad`.
- **Online calculator:** https://www.wadifa-info.com/fr/calcul-des-salaires-fonction-publique-maroc (grade + échelon). Also served at https://www.wadifa-info.com/data/salaires-par-echelon-fonction-publique-maroc.csv
- **Licence:** CC BY 4.0, cite "Wadifa Info, salaire brut et net par échelon, fonction publique marocaine 2026".

---
Français : salaire net mensuel (MAD) de 370 grades de la fonction publique marocaine, par corps. Licence CC BY 4.0, source Wadifa Info.
