# Advancing Cognitive Pairwise Comparisons for Human-Centric AI and Data Science (CPC-HCAD)

Official repository containing software demonstrations, computational workflows, and processed datasets accompanying the research paper:

> **Yuen, K. K. F. (2026).** *Advancing Cognitive Pairwise Comparisons for Human-Centric AI and Data Science*. (Manuscript under review).

---
## Overview
The **CPC-HCAD** framework advances and extends **Cognitive Pairwise Comparisons (CPC)** into core machine learning operations. By integrating human preference elicitation directly into data preprocessing, feature selection, model evaluation, dimensionality reduction, and rule mining, CPC-HCAD empowers domain experts and decision-makers to guide machine learning workflows while maintaining mathematical consistency and interval-scale rigor.

---
## Interactive Demonstration Modules

This repository provides live, interactive HTML modules demonstrating the application of CPC across key data science and machine learning paradigms:

### 1. Data Cleaning & Feature Engineering (`s1dataTransformation.html`)
* **Purpose:** Preprocesses raw metadata and user evaluation logs into structured analytical tables.
* **Key Capabilities:** Title and release year parsing, anomaly filtering, multi-category one-hot encoding, and statistical aggregation of user evaluation metrics.

### 2. CPC Discretization & Categorical Encoding (`s2cpcTransformation.html`)
* **Purpose:** Transforms continuous numerical attributes into preference-proportional discrete intervals.
* **Key Capabilities:** Pairwise Opposite Matrix (POM) construction, interval width optimization via the NRAU operator, and dummy variable architecture generation.

### 3. CPC-Guided Regression & Feature Selection (`s3cpcRegression.html`)
* **Purpose:** Demonstrates human-in-the-loop continuous score prediction and feature prioritization.
* **Key Capabilities:** Cognitive training-validation-testing dataset partitioning and preference-guided forward feature selection based on validation performance trajectories.

### 4. Multi-Criteria Classification Model Selection (`s4cpcClassification.html`)
* **Purpose:** Evaluates and ranks candidate classification algorithms across multi-dimensional criteria.
* **Key Capabilities:** Multi-metric benchmarking (accuracy, precision, recall, NPV, specificity), cross-validation profiling, and multi-criteria decision matrix aggregation to identify optimal predictive models.

### 5. Preference-Weighted PCA & Clustering (`s5cpcClustering.html`)
* **Purpose:** Integrates user preferences into dimensionality reduction and audience segmentation.
* **Key Capabilities:** User-Preference-Weighted Principal Component Analysis (PCA), weighted Euclidean distance metric formulation, automated cluster structure detection, and preference-aligned recommendation extraction.

### 6. Association Rule Mining & Preference Re-ranking (`s6cpcAssociation.html`)
* **Purpose:** Discovers transactional co-occurrence patterns and re-ranks decision rules by user preferences.
* **Key Capabilities:** Discretized itemset generation, Apriori rule mining, and preference-based re-ranking to deliver tailored, context-aware suggestions.

---
## Repository Structure

```
cpcHCADDemos/
├── outputData/                  # Directory: Stores executed resulting files and exported datasets
├── s1dataTransformation.html    # Module 1: Data Cleaning & Feature Engineering
├── s2cpcTransformation.html     # Module 2: CPC Discretization & Categorical Encoding
├── s3cpcRegression.html         # Module 3: CPC Regression & Forward Feature Selection
├── s4cpcClassification.html     # Module 4: Multi-Criteria Classification Selection
├── s5cpcClustering.html         # Module 5: Preference-Weighted PCA & K-Means Clustering
├── s6cpcAssociation.html        # Module 6: Association Rule Mining & Re-ranking
└── README.md                    # Project overview & documentation
```

* **outputData:** Folder storing all executed resulting data files, exported dataset tables, and intermediate computational outputs generated across the workflow modules.

---
## Getting Started

### Online Demos
All modules can directly be executed in your web browser via GitHub Pages.    
https://kkfyuen.github.io/cpcHCADDemos/ 

### Local Execution
1. Clone the repository and open any `.html` demonstration file in a modern web browser to inspect interactive tables, visualizations, and computational steps.
2. Access all processed result files directly in the `outputData` directory.

---

## Citation

If you use this software, methodology, or processed data in your research, please cite:

Yuen, K. K. F. (2026). Advancing Cognitive Pairwise Comparisons for Human-Centric AI and Data Science. Manuscript under review.

---

## License

Distributed under the MIT License. See the LICENSE file for details.
