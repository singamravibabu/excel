# Excel's SUMIF() Function

The `SUMIF` function in Excel is used to sum the values in a range that meet a single condition. The syntax for the `SUMIF` function is:

```
SUMIF(range, criteria, [sum_range])
```

- `range`: The range of cells that you want to apply the criteria to.
- `criteria`: The condition that must be met for a cell to be included in the sum.
- `[sum_range]`: The actual cells to sum. If omitted, Excel sums the cells in the `range`.

## Example Dataset

| Product | Category | Sales |
|---------|----------|-------|
| Apple   | Fruit    | 50    |
| Banana  | Fruit    | 30    |
| Carrot  | Vegetable| 20    |
| Orange  | Fruit    | 40    |
| Broccoli| Vegetable| 25    |

## Examples

### Example 1: Sum Sales for a Specific Category

To sum the sales for the "Fruit" category:

```
=SUMIF(B2:B6, "Fruit", C2:C6)
```

This formula sums the values in the `Sales` column (C2:C6) where the `Category` column (B2:B6) is "Fruit". The result is 120.

### Example 2: Sum Sales Greater Than a Certain Value

To sum the sales that are greater than 30:

```
=SUMIF(C2:C6, ">30")
```

This formula sums the values in the `Sales` column (C2:C6) that are greater than 30. The result is 115.

### Example 3: Sum Sales for a Specific Product

To sum the sales for the product "Apple":

```
=SUMIF(A2:A6, "Apple", C2:C6)
```

This formula sums the values in the `Sales` column (C2:C6) where the `Product` column (A2:A6) is "Apple". The result is 50.

## Practice

Use the example dataset above to practice the `SUMIF` function with different criteria. Try creating your own conditions and see how the function works with various ranges and criteria.
