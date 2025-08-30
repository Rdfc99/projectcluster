# Foundational Problem-Solving Patterns in Benchmark Tasks: A Mixed-Type Clustering Analysis of SWE-Bench Verified

## Overview
This project implements various clustering techniques on the SWE-Bench Verified dataset, a curated subset of 500 software engineering tasks from real GitHub issues. The analysis explores mixed-type data clustering using numerical, categorical, ordinal and text features. The analysis is divided into three main components: traditional clustering methods, semantic text analysis, and unified clustering approaches.

## Project Structure
```
├── README.md
├── ensembled_annotations_public.csv    # Required data file
├── swe_bench_verified_test.csv         # Required data file
├── ThesisCode_DataExploration+KMeans+Kprototypes.ipynb
├── ThesisCode_semanticexploration.ipynb
└── ThesisCode_UnifiedSphericalClustering.ipynb
```

## Notebooks Description

### 1. Data Exploration and Traditional Clustering
**File:** `ThesisCode_DataExploration+KMeans+Kprototypes.ipynb`
- Exploratory data analysis of the datasets
- Implementation of K-Means clustering for numerical features
- Implementation of K-Prototypes for mixed numerical and categorical data
- Visualisation of clustering results

### 2. Text/Semantic Data Exploration
**File:** `ThesisCode_semanticexploration.ipynb`
- Text data preprocessing and exploration
- Semantic analysis of text features
- Text vectorisation techniques
- Exploratory analysis of semantic patterns

### 3. Unified Clustering on Mixed-Type Data
**File:** `ThesisCode_UnifiedSphericalClustering.ipynb`
- Integration of numerical, categorical, and text features
- Implementation of unified clustering approach
- Comparison of different clustering strategies
- Final clustering results and evaluation

## Data Files

### Required Datasets
- **swe_bench_verified_test.csv**: OpenAI's SWE-Bench Verified task dataset (500 tasks, subset of SWE-Bench)
- **ensembled_annotations_public.csv**: Annotation data for the tasks on SWE-Bench Verified, provided by OpenAI

**Note:** Both CSV files must be present in the same directory as the notebooks for proper execution.

## Requirements
```
# Core libraries
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
scipy>=1.7.0

# For clustering
kmodes>=0.12.0

# For text processing
nltk>=3.6.0
transformers>=4.20.0
sentence-transformers>=2.2.0
unidiff>=0.7.0

# For notebooks
jupyter>=1.0.0
ipykernel>=6.0.0
```
## Usage
Run the notebooks in order:

- Start with notebook 1 for data exploration and basic clustering
- Proceed to notebook 2 for text analysis
- Finish with notebook 3 for the unified approach





## Author
Renuka Fernandez
## License
MIT License - see LICENSE file for details
