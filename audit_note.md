
### Step 8 — Update `audit_note.md`

```markdown
# Data Cleaning Audit Note

## Task

Task 13 - Duplicate Record Check

## Dataset

Superstore Dataset

## Tools Used

- Google Sheets
- Python
- Pandas

## Cleaning Activity

The dataset was checked for complete duplicate records.

## Verification

Pandas was used to verify duplicate records using:

```python
df.duplicated().sum()