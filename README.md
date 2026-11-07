# MSc_Thesis_Datasets
This repository contains the research datasets supporting the MSc Artificial Intelligence thesis: "On the Value of US-Developed Large Language Models for Financial Literacy in Mozambique"

**Author:** Kadzuwa Kuyeri  
**Institution:** IU International University of Applied Sciences  
**Degree:** MSc Artificial Intelligence  
**Submission year:** 2026

## Study overview
The study examines how three US-developed large language models (ChatGPT, Claude and Gemini) adapt financial literacy guidance to Mozambican and American user contexts, and whether contextual adaptation differs between English and Portuguese prompting for Mozambican scenarios.

The empirical design contains:
- 3 LLMs;
- 12 standardized financial literacy scenarios;
- 4 domains: Budgeting, Savings, Credit/Debts and Investing;
- 3 prompt conditions: English–Mozambique (EN-MOZ), English–United States (EN-USA), and Portuguese–Mozambique (PT-MOZ);
- 108 generated responses in total.

The repository is provided to support transparency and reproducibility of the thesis analyses.

## Repository contents
**data/llm_responses_108.xlsx**: Complete generated-response dataset, identified as R001–R108.
**data/verified_claims_164.xlsx**: Final unique-claim verification dataset: all 94 High-materiality claims and 70 selected Medium-materiality claims. 
**data/verified_claim_occurrences_438.xlsx**: Occurrence-level dataset mapping the 164 verified claims to their 438 occurrences across generated responses, including contextual-applicability and jurisdiction-leakage coding
**data/structured_comparative_content_analysis.xlsx**: Structured response-content coding used to compare contextualisation patterns across prompt conditions and models.
**data/thematic_verification_batches_14.xlsx**: Final thematic verification batches used to organise the factual-verification analysis.
**docs/DATASET_NOTES.md**: Notes on analytical units, denominators and interpretation. |

## Key analytical denominators
The complete generated-response dataset contains **108 responses**. Claim extraction and consolidation produced **323 unique claims**: 94 High-, 198 Medium- and 31 Low-materiality claims. The final factual-verification set contains **164 unique claims**, comprising the complete set of 94 High-materiality claims and 70 selected Medium-materiality claims. These verified claims occur **438 times** across the response dataset.

Contextual applicability is assessed separately from factual verification at the **Claim × Scenario Country** level. Because four non-jurisdiction-specific claims appeared in both country contexts, the 164 unique verified claims produce **168 contextual-applicability units**.

## Important interpretation notes
- The 94 High-materiality claims constitute a census of all High-materiality claims identified in the study.
- The 70 Medium-materiality claims are a predefined selected sample from the 198 Medium-materiality claims and should not be interpreted as representing a census of all Medium claims.
- Factual verification outcome and contextual applicability are separate analytical dimensions.
- "Unable to Verify" does not mean that a claim was false; it indicates that sufficient authoritative evidence was not identified to support or reject the claim under the study procedure.
- The datasets represent model outputs and financial-information verification at a specific period in **2026**. Financial products, rates, regulations and model behaviour may change over time.

## Privacy and research-participant data
Raw evaluator survey exports, evaluator contact information and other participant-identifying data are **not included** in this repository. Evaluator findings are reported in aggregated or appropriately anonymised form in the thesis.

## Use of the data
The generated LLM responses are research data and **must not be interpreted as professional financial advice**. Factual-verification classifications reflect the evidence and research procedure documented in the thesis and its Factual and Contextual Verification Framework.



## Thesis availability
The thesis itself is not included in this repository at this stage. The repository is intended to accompany the final submitted thesis and provide access to the underlying research datasets referenced in the methodology and results chapters.
