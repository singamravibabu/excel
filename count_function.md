# Excel's COUNT() Function

The `COUNT()` function in Excel is used to count the number of cells that contain numbers within a specified range. It is useful for quickly determining the number of numerical entries in a dataset.

## Syntax
```excel
COUNT(value1, [value2], ...)
```
- `value1`: The first item, cell reference, or range within which you want to count numbers.
- `[value2], ...`: Optional additional items, cell references, or ranges within which you want to count numbers.

## Example Dataset
Here is an example dataset to practice the `COUNT()` function:

| A       | B       | C       |
|---------|---------|---------|
| 1       | Text    | 3.5     |
| 2       | 4       |         |
| 5       | 6       | 7       |
| Text    | 8       | 9       |
| 10      |         | Text    |

## Examples

### Example 1: Counting Numbers in a Single Range
To count the number of numerical values in the range A1:A5:
```excel
=COUNT(A1:A5)
```
**Result:** 3 (since cells A1, A2, and A3 contain numbers)

### Example 2: Counting Numbers in Multiple Ranges
To count the number of numerical values in the ranges A1:A5 and B1:B5:
```excel
=COUNT(A1:A5, B1:B5)
```
**Result:** 6 (since cells A1, A2, A3, B1, B2, and B4 contain numbers)

### Example 3: Counting Numbers with Mixed Data Types
To count the number of numerical values in the range A1:C5:
```excel
=COUNT(A1:C5)
```
**Result:** 9 (since cells A1, A2, A3, A4, A5, B2, B3, B4, and C1 contain numbers)

## Practice
Use the example dataset provided above to practice using the `COUNT()` function. Try creating different ranges and see how the function counts the numerical values within those ranges.
