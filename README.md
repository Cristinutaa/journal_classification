
# Project Name: Journal classification using LLMs

## Overview
This repository contains datasets and classification results for three different datasets: **Norway**, **VABB_full**, and **VABB_manual**. Each dataset is organized in separate folders with specific results related to classification tasks performed using generative language models (LLMs).

The structure of the project includes multiple subdirectories for detailed analysis and classification results for each dataset.

## Folder Structure

```
|-- Norway/
|   |-- ALL_RESULTS/
|   |   |-- ADDITIONAL_INFO_RESULTS/
|   |   |-- BERT_RESULTS/
|   |   |-- CLASSIFICATION_REPORTS/
|   |   |-- DATA_WITH_ADDITIONAL_INFO/
|   |   |-- CLASSIFICATION_RESULTS/
|   |   |-- RAW_RESULTS/
|
|-- VABB_full/
|   |-- ALL_RESULTS/
|   |   |-- ADDITIONAL_INFO_RESULTS/
|   |   |-- BERT_RESULTS/
|   |   |-- CLASSIFICATION_REPORTS/
|   |   |-- DATA_WITH_ADDITIONAL_INFO/
|   |   |-- CLASSIFICATION_RESULTS/
|   |   |-- RAW_RESULTS/
|
|-- VABB_manual/
|   |-- ALL_RESULTS/
|   |   |-- ADDITIONAL_INFO_RESULTS/
|   |   |-- BERT_RESULTS/
|   |   |-- CLASSIFICATION_REPORTS/
|   |   |-- DATA_WITH_ADDITIONAL_INFO/
|   |   |-- CLASSIFICATION_RESULTS/
|   |   |-- RAW_RESULTS/
|   |   |-- annotator_model_agreement_scores.csv
```
### Folder Descriptions

1. **ALL_RESULTS**:
   - This is the main directory where all results for the dataset are stored.
   - Each dataset (Norway, VABB_full, and VABB_manual) has a corresponding folder under this directory containing subfolders for results and analysis.

2. **DATA_WITH_ADDITIONAL_INFO**:
   - This folder contains the dataset with additional information used for the classification tasks.
   - It includes details like the classification results for the generative LLMs and other relevant output data for each model.

3. **ADDITIONAL_INFO_RESULTS**:
   - This folder contains the data for each LLM based on a chained approach for extracting relevant information from the dataset.

4. **CLASSIFICATION_RESULTS**:
   - Here, you'll find the classification results for each model and experiment.
   - Each model's results are stored separately for easier analysis of the classification performance.

5. **CLASSIFICATION_REPORTS**:
   - This folder contains detailed reports of the classification process, which includes metrics such as precision, recall, F1-score, etc., for each model's experiment.

6. **RAW_RESULTS**:
   - Contains the raw outputs from each model before cleaning the results.

7. **BERT_RESULTS**:
   - This folder includes results from classification results using mBERT.

### Example Usage
- To view the classification results, navigate to the `CLASSIFICATION_RESULTS/` folder.
- To explore the additional data used by the models, check out the `DATA_WITH_ADDITIONAL_INFO/` folder.
