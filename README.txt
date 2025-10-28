ThePricer.org — Student Affordability Toolkit (SEAT)
Version: v1.2
Release date: 2025-10-23
Homepage: https://www.thepricer.org/student/resources/
Contact: press@thepricer.org
License: CC BY 4.0 (see LICENSE-CCBY4.0.txt)

SUMMARY
This ZIP contains open datasets and classroom-ready CSV templates that power
ThePricer’s student affordability analysis and calculators. The toolkit helps
estimate a realistic monthly student budget and the “hours‑to‑afford” metric
(total monthly costs divided by after‑tax hourly wage).

PREFERRED LINK & CITATION
Preferred link: https://www.thepricer.org/student/resources/
Suggested citation:
  ThePricer.org (2025). Student Affordability Toolkit (SEAT) v1.2. CC BY 4.0.
  Available at https://www.thepricer.org/student/resources/

(If a DOI is minted on a repository such as Figshare/Dataverse, include it here.)

CONTENTS (file manifest)
datasets/
  • student_cost_national_cpi_1990_2019_2024_2025_v11.csv
      – National CPI component indices and wage anchors at four dates (1990‑12,
        2019‑12, 2024‑12, 2025‑08). Includes series IDs used by our basket.
  • student_us_state_inputs_20251.csv
      – State inputs (ACS 2023 median gross rent scaled to 2025 with CPI Rent,
        plus 2025 state minimum wage and notes for split‑rate states).
  • student_us_master_basket_v01.csv
      – 2025 baseline basket with CPI back‑scaling columns (per‑category and TOTAL).

templates/
  • student_budget_template.csv                – Monthly budget + hours‑to‑afford.
  • grocery_basket_template.csv                – Pantry/produce/meals starter.
  • country_student_cost_template.csv          – Inputs for US vs World comps.
  • commute_cost_template.csv                  – Transit vs car monthly cost.
  • meal_plan_template.csv                     – Meal plan vs groceries CPM.
  • roommate_split_template.csv                – FairShare rent/utility split.
  • textbook_optimizer_template.csv            – Buy used vs rent vs ebook.
  • aid_impact_template.csv                    – Grants/work‑study impact.
  • student_state_template_acs_rent_minwage_20251.csv – Blank state worksheet.

docs/
  • DATA_DICTIONARY.csv                        – Field names & descriptions.
  • LICENSE-CCBY4.0.txt                        – Full text of the license (in this ZIP).
  • README.txt                                 – This file.

METHODOLOGY (short)
• Basket categories map to BLS CPI‑U series (NSA): Rent (CUUR0000SEHA),
  Electricity (SEHF01), Piped gas (SEHF02), Food at home (SAF11), Public
  transportation (SETG), Medical care services (SAM2), All items (SA0).
• Wages: Leisure & Hospitality Average Hourly Earnings (CES7000000008) or
  state/federal minimum wage; after‑tax factor 0.92 used in our examples.
• Tuition & books: amortized to monthly. Internet is included via a flat line.
• State rents: ACS table B25064 (2023) scaled to 2025 with the Rent CPI ratio.

USAGE
Open the templates in Google Sheets or Excel. Edit highlighted cells to match
local conditions (rent, utilities, wages). Use the Hours‑to‑Afford field to
see required work hours per month. For reproducible analysis, pin the version
(v1.2) and note any modifications.

PROVENANCE & SOURCES
BLS CPI & CES: https://www.bls.gov/ (series IDs listed above)
Census ACS: https://data.census.gov/ (B25064: Median Gross Rent)
U.S. DOL Minimum Wage: https://www.dol.gov/agencies/whd/minimum-wage
College Board (tuition context): https://research.collegeboard.org/

LIMITATIONS
No PII included. CPI is national level; local conditions vary. Wage selection
matters (min‑wage vs sector AHE). Templates are educational tools, not advice.

SUPPORT
Issues or media requests: press@thepricer.org
