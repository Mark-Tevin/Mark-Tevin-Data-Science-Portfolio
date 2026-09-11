# Quiz: Evaluating Model Performance & Managing Data Storage

## Overview

This notebook contains two practical Python exercises from the **AWS AI & ML Scholars Program**.

The exercises introduce fundamental concepts that are useful when working with Artificial Intelligence and Machine Learning projects:

1. **Evaluating Model Performance** – calculating the mean prediction accuracy of a model.
2. **Managing Data Storage** – calculating dataset storage requirements and determining remaining storage capacity.

Although the calculations are simple, they demonstrate important skills in **Python, basic statistics, data management, and resource planning** that are applicable to real-world AI/ML workflows.

---

## Learning Objectives

By completing these exercises, I practiced how to:

- Store numerical data using Python lists.
- Calculate the mean of multiple values.
- Use Python's built-in `sum()` and `len()` functions.
- Perform arithmetic operations using variables.
- Calculate storage requirements for datasets.
- Convert storage measurements from KB to MB.
- Calculate remaining storage capacity.
- Format numerical results for clear presentation.

---

# Quiz 1: Evaluating Model Performance

## Scenario

A machine learning project requires analysis of the average prediction accuracy of a model over the last three months.

The recorded accuracy scores are:

| Month | Prediction Accuracy |
|---|---:|
| Month 1 | 85.5% |
| Month 2 | 90.2% |
| Month 3 | 87.3% |

## Task

Calculate the **mean prediction accuracy** across the three months.

## Approach

The accuracy scores are stored in a Python list:

```python
accuracy_scores = [85.5, 90.2, 87.3]