# Excel's SUM() Function

The `SUM()` function in Excel is used to add together a range of numbers. It is one of the most commonly used functions in Excel for performing arithmetic operations.

## Syntax
```excel
SUM(number1, [number2], ...)
```
- `number1`: The first number or range to add.
- `[number2], ...`: Additional numbers or ranges to add (optional).

## Examples

### Example 1: Sum of a Range
To sum the numbers in the range A1 to A5:
```excel
=SUM(A1:A5)
```

### Example 2: Sum of Individual Cells
To sum the numbers in cells A1, B1, and C1:
```excel
=SUM(A1, B1, C1)
```

### Example 3: Sum of Multiple Ranges
To sum the numbers in the ranges A1:A5 and B1:B5:
```excel
=SUM(A1:A5, B1:B5)
```

## Example Dataset to Practice

| A   | B   | C   |
|-----|-----|-----|
| 10  | 20  | 30  |
| 15  | 25  | 35  |
| 20  | 30  | 40  |
| 25  | 35  | 45  |
| 30  | 40  | 50  |

### Practice Exercises

1. Sum the values in column A:
    ```excel
    =SUM(A1:A5)
    ```

2. Sum the values in row 1:
    ```excel
    =SUM(A1:C1)
    ```

3. Sum the values in the entire dataset:
    ```excel
    =SUM(A1:C5)
    ```

4. Sum the values in columns A and B:
    ```excel
    =SUM(A1:A5, B1:B5)
    ```

By practicing with the above dataset and exercises, you can become proficient in using the `SUM()` function in Excel.