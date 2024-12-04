# Excel SUMIFS() Function

The `SUMIFS` function in Excel is used to sum the values in a range that meet multiple criteria. It is a powerful function for conditional summing.

## Syntax

```excel
SUMIFS(sum_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)
```

- **sum_range**: The range of cells to sum.
- **criteria_range1**: The range of cells that you want to apply the first criteria to.
- **criteria1**: The criteria to apply to criteria_range1.
- **criteria_range2, criteria2, ...**: Additional ranges and criteria (optional).

## Example Dataset

| Product | Region | Sales | Month  |
|---------|--------|-------|--------|
| A       | North  | 100   | Jan    |
| B       | South  | 200   | Jan    |
| A       | North  | 150   | Feb    |
| B       | South  | 250   | Feb    |
| A       | East   | 100   | Mar    |
| B       | West   | 300   | Mar    |
| A       | East   | 200   | Apr    |
| B       | West   | 350   | Apr    |

## Examples

### Example 1: Sum Sales for Product A in the North Region

```excel
=SUMIFS(C2:C9, A2:A9, "A", B2:B9, "North")
```

This formula sums the sales for Product A in the North region. The result is `250` (100 from Jan and 150 from Feb).

### Example 2: Sum Sales for Product B in the South Region in January

```excel
=SUMIFS(C2:C9, A2:A9, "B", B2:B9, "South", D2:D9, "Jan")
```

This formula sums the sales for Product B in the South region in January. The result is `200`.

### Example 3: Sum Sales for Product A in the East Region

```excel
=SUMIFS(C2:C9, A2:A9, "A", B2:B9, "East")
```

This formula sums the sales for Product A in the East region. The result is `300` (100 from Mar and 200 from Apr).

## Practice

Use the example dataset above to practice creating your own `SUMIFS` formulas. Try summing sales for different products, regions, and months to get a better understanding of how the function works.
