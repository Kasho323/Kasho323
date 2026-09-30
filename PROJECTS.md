# Project index

A guided route through the public portfolio. Project status describes the repository, not a guarantee that an external deployment or API is currently available.

## Research and AI engineering

| Project | Start with | Inspect the evidence | Boundary |
|---|---|---|---|
| [Local SLM Benchmark](https://github.com/Kasho323/msc-dissertation-slm-benchmark) | `python reproduce.py` | [Validation and provenance](https://github.com/Kasho323/msc-dissertation-slm-benchmark/blob/main/reproduction/VALIDATION.md) | Reproducing retained statistics is separate from running fresh generations. |
| [Codebase Explainer Agent](https://github.com/Kasho323/codebase-explainer-agent) | README quick start and local demo | [Tests](https://github.com/Kasho323/codebase-explainer-agent/tree/main/tests) and [golden cases](https://github.com/Kasho323/codebase-explainer-agent/tree/main/eval/golden_cases) | Python repository support; live chat uses an external model provider. |
| [Diabetes Risk Prediction](https://github.com/Kasho323/diabetes-risk-prediction) | Streamlit app or ordered notebooks | [Classification notebook](https://github.com/Kasho323/diabetes-risk-prediction/blob/main/notebooks/04_Classification.ipynb) | Notebook metrics do not validate the separate five-input demonstration. |

## Practical software and data systems

| Project | Start with | Inspect the implementation | Boundary |
|---|---|---|---|
| [Kasho Hotel](https://github.com/Kasho323/kasho-hotel) | Local front-desk launcher | [Inventory logic](https://github.com/Kasho323/kasho-hotel/blob/main/frontdesk/inventory.py) and [tests](https://github.com/Kasho323/kasho-hotel/tree/main/frontdesk/tests) | Local operation; platform availability still needs manual updates. |
| [Asset Dashboard](https://github.com/Kasho323/asset-dashboard) | `index.html` with sample data | [Browser app](https://github.com/Kasho323/asset-dashboard/blob/master/index.html) | Browser storage; optional OCR sends submitted content to configured services. |
| [COVID Data Pipeline](https://github.com/Kasho323/covid-data-pipeline) | Bundled CSV workflow | [Pipeline tests](https://github.com/Kasho323/covid-data-pipeline/blob/main/covid_pipeline/test_main.py) | Demonstration data; upstream API availability is separate. |
| [Basket Graph Analytics](https://github.com/Kasho323/basket-graph-analytics) | CLI companion-item query | [Graph implementation](https://github.com/Kasho323/basket-graph-analytics/blob/main/basket_graph/basket.py) and benchmark | Pairwise associations; query ranking is not constant time. |

## Historical work

[PAI Individual Assignment](https://github.com/Kasho323/PAI-Individual-Assignment) is an archived source-history repository. Its maintained successors are COVID Data Pipeline and Basket Graph Analytics.

Private work and other owners' repositories are not presented here as public portfolio projects.
