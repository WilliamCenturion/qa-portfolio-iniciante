
# Regression Test Cases — Product Catalog

## REG-CATALOG-001 — Filter by Category

- **Preconditions:** Product catalog is loaded.
- **Steps:**
  1. Select the `hand tools` category.
  2. Observe the displayed products.
- **Expected Result:** Only products belonging to the selected category are displayed.
- **Status:** Not executed as a regression test.

## REG-CATALOG-002 — Filter by Another Category

- **Preconditions:** Product catalog is loaded.
- **Steps:**
  1. Select a different category that worked during exploratory testing.
  2. Observe the displayed products.
- **Expected Result:** Only products belonging to the selected category are displayed.
- **Status:** Not executed as a regression test.

## REG-CATALOG-003 — Combine Category Filter and Price Sorting

- **Preconditions:** Product catalog is loaded.
- **Steps:**
  1. Select a product category.
  2. Sort products by price in ascending order.
  3. Inspect the displayed products and their prices.
- **Expected Result:** All displayed products belong to the selected category and are sorted by ascending price.
- **Status:** Not executed as a regression test.

