# Excel COUNTIFS() Function

The `COUNTIFS` function in Excel counts the number of cells that meet one or more criteria. It is a powerful function for data analysis and can handle multiple conditions.

## Syntax

```excel
COUNTIFS(criteria_range1, criteria1, [criteria_range2, criteria2], ...)
```

- `criteria_range1`: The first range in which to evaluate the associated criteria.
- `criteria1`: The criteria to use on `criteria_range1`.
- `[criteria_range2, criteria2], ...`: Optional. Additional ranges and their associated criteria.

## Example Dataset

| Name    | Department | Age | Salary |
|---------|------------|-----|--------|
| John    | HR         | 28  | 50000  |
| Alice   | IT         | 34  | 70000  |
| Bob     | HR         | 45  | 55000  |
| Carol   | IT         | 29  | 60000  |
| David   | Finance    | 31  | 65000  |
| Eve     | HR         | 38  | 52000  |

## Examples

### Example 1: Count employees in the HR department

```excel
=COUNTIFS(B2:B7, "HR")
```

**Result:** 3

### Example 2: Count employees in the IT department who are older than 30

```excel
=COUNTIFS(B2:B7, "IT", C2:C7, ">30")
```

**Result:** 1

### Example 3: Count employees in the HR department with a salary greater than 50000

```excel
=COUNTIFS(B2:B7, "HR", D2:D7, ">50000")
```

**Result:** 1

### Example 4: Count employees in the Finance department who are younger than 35

```excel
=COUNTIFS(B2:B7, "Finance", C2:C7, "<35")
```

**Result:** 1

## Practice

Use the example dataset provided above to practice the `COUNTIFS` function with different criteria. Try creating your own criteria to count specific subsets of data.

- Count employees in the IT department with a salary less than 65000.
- Count employees older than 30 with a salary greater than 60000.
- Count employees in the HR department who are younger than 40.

By practicing with different criteria, you can become proficient in using the `COUNTIFS` function for various data analysis tasks in Excel.
