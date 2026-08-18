# Higher Education & Municipal Development — BI Proposal

Business-intelligence solution design relating the supply of undergraduate courses in Brazil to the economic development of municipalities.

## Business question

Does the presence of higher-education institutions contribute to local economic development, and where are the regional gaps in access to undergraduate education?

The proposal covers the business context, two user personas — a municipal public manager and a prospective student — their goals, the indicators that answer them, and the data sources that feed the model.

Full document: [`report/business-intelligence-report.pdf`](report/business-intelligence-report.pdf).

## Data sources

The source files are large public datasets and are **not versioned here**. Download them from the official portals:

| Dataset | Source |
|---|---|
| Undergraduate courses in Brazil (institution, course, degree, seats, municipality, region) | [INEP / Dados Abertos](https://dadosabertos.mec.gov.br/) |
| GDP of Brazilian municipalities, 2010–2023 | [IBGE — PIB dos Municípios](https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9088-produto-interno-bruto-dos-municipios.html) |
| Municipal territorial division (DTB) 2024 | [IBGE — Divisão Territorial Brasileira](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/estrutura-territorial/23701-divisao-territorial-brasileira.html) |
| Localities / coordinates (BR_Localidades 2010) | [IBGE — Geociências](https://www.ibge.gov.br/geociencias/downloads-geociencias.html) |

The course dataset alone is ~226 MB, which is why it stays outside version control.
