# Excel COUNTIF() Function

The `COUNTIF` function in Excel is used to count the number of cells that meet a criterion; for example, to count the number of times a particular value appears in a range of cells.

## Syntax

```excel
COUNTIF(range, criteria)
```

- `range`: The range of cells that you want to apply the criteria to.
- `criteria`: The condition that must be met for a cell to be counted.

## Examples

### Example 1: Counting Specific Text

Suppose you have the following dataset in cells A1:A5:

| A       |
|---------|
| Apple   |
| Banana  |
| Apple   |
| Orange  |
| Apple   |

To count the number of times "Apple" appears in the range A1:A5, use the following formula:

```excel
=COUNTIF(A1:A5, "Apple")
```

### Example 2: Counting Numbers Greater Than a Value

Suppose you have the following dataset in cells B1:B5:

| B   |
|----|
| 10 |
| 20 |
| 30 |
| 40 |
| 50 |

To count the number of cells with values greater than 25 in the range B1:B5, use the following formula:

```excel
=COUNTIF(B1:B5, ">25")
```

### Example 3: Counting Cells with Specific Date

Suppose you have the following dataset in cells C1:C5:

| C          |
|------------|
| 01/01/2023 |
| 02/01/2023 |
| 01/01/2023 |
| 03/01/2023 |
| 01/01/2023 |

To count the number of times the date "01/01/2023" appears in the range C1:C5, use the following formula:

```excel
=COUNTIF(C1:C5, "01/01/2023")
```

## Practice Dataset

You can use the following dataset to practice the `COUNTIF` function:

| A       | B   | C          |
|---------|-----|------------|
| Apple   | 10  | 01/01/2023 |
| Banana  | 20  | 02/01/2023 |
| Apple   | 30  | 01/01/2023 |
| Orange  | 40  | 03/01/2023 |
| Apple   | 50  | 01/01/2023 |

Try using the `COUNTIF` function to answer the following questions:
1. How many times does "Apple" appear in column A?
2. How many numbers in column B are greater than 25?
3. How many times does the date "01/01/2023" appear in column C?
