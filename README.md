Word search analysis of Web of Science (WoS) data, searching for family, genus, and keywords related to in vitro propagation.

Results published in ~
### Pence VC, Bruns EB. 2023. article name. *In Vitro Cell.Dev.Biol.-Plant vol*(issue):pages. URL

Funding provided by the Institute of Museum and Library Services, grant number MG-30-17-0055-17 Awarded to Cincinnati Zoo & Botanical Garden

Script inputs:
- Exports from Web of Science (Excel files)
- Keyword lists (available in input_data_public folder), including:
  - Common names matched with scientific names ("Keyword searches - common_names.csv")
  - Keywords to check the article is relevant topic of interest ("Keyword searches - focus_check.csv")
- List of exceptional species (available in input_data_public folder as "Exceptional Status List - No Justification.csv"; Pence et al. 2022); raw dataset available at https://cincinnatizoo.org/system/assets/uploads/2022/02/Supplementary-data.xlsx
- World Flora Online static backbone v.2021.01; available at http://www.worldfloraonline.org/downloadData
- Seed/non-seed and higher classification from The Plant List and manual searching (available in input_data_public folder as "seed_nonseed_families.csv")

Script output:
List of articles from Web of Science, with columns indicating which families, genera, and keywords were identified. This output was then manually reviewed and edited before analysis.
