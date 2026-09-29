# Duplicate Record Check Report

## Dataset

Superstore Dataset

## Objective

The objective of this task is to identify duplicate records and prepare a clean dataset for further analysis.

## Tools Used

- Google Sheets
- Python
- Pandas

## Method

The dataset was checked in Google Sheets using:

**Data → Data cleanup → Remove duplicates**

The dataset was also analyzed using Pandas.

The following Pandas functions were used:

```python
df.duplicated().sum()