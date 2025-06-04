# NLP Political Speech Classification Project

This project uses **ordinal regression** to classify political speeches into four levels of rhetorical extremity: *apathetic*, *moderate*, *strongly worded*, and *extreme*.

## Overview

Using a dataset of 500 annotated political speeches from publicly available datasets, the notebook trains an ordinal regression model that leverages the natural order of labels. This allows for more nuanced modeling compared to traditional classification approaches.

## Key Results

- **Model Accuracy**: ~70% on the test set
- **Confidence Interval**: 95% CI = [67%, 73%]
- Outperforms a majority baseline and standard logistic regression, especially in preserving ordinal structure

## Key Features

- Ordinal regression implementation using `statsmodels`
- Custom accuracy and error analysis for ordinal labels
- 95% confidence intervals computed via bootstrapping
- Confusion matrix and residual analysis for qualitative insights

## Requirements

- Python 3.8+
- `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `statsmodels`, `seaborn`

Install dependencies with:

```bash
pip install -r requirements.txt

