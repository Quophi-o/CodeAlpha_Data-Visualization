# CodeAlpha Data Analytics Internship

## Task 3 — Data Visualization: Book Listings Dataset

## 1. Overview

Building on the exploratory analysis in Task 2, this task focuses on presenting the book listings dataset (1,000 books scraped from books.toscrape.com in Task 1) through clear, easy-to-read charts. The goal here shifts from exploring the data to communicating its story — turning the same underlying numbers into visuals that let someone unfamiliar with the dataset grasp the key insights at a glance.

## 2. Tool Used

All charts were built directly in Excel using PivotTables and PivotCharts, based on the cleaned dataset (Title, Price, Rating) from Task 1.

## 3. Charts Produced

| Chart | Type | Key Message |
| --- | --- | --- |
| Distribution of book prices | Histogram of price buckets (£10–£61) | Prices are spread broadly and evenly across the range — no single price tier dominates the catalogue. |
| Average book price by rating | Combo chart: count + average price per rating | Average price barely changes across ratings (£34.56–£36.09) — price is not a signal of perceived quality. |
| Number of books per rating | Horizontal bar chart, books per star level | Each rating (1–5 stars) holds a similar share of the catalogue (~180–230 books), so ratings are evenly distributed. |

## 4. The Data Story

Together, the three charts tell a simple story about the books.toscrape.com catalogue: it is a broad, evenly spread collection — both in terms of price and in terms of customer rating — where price and quality perception (rating) do not move together. A shopper cannot assume a pricier book is better rated, or that a cheaper one is worse rated; the two variables are effectively independent in this dataset.

## 5. Design Choices

- Used PivotCharts so each chart stays linked to the underlying pivot table and updates automatically if the source data changes.
- Grouped prices into equal-width buckets for the price distribution chart, making the spread easy to read at a glance.
- Paired count and average-price series on the same chart (rating breakdown) so the volume and price relationship can be read together, in one view.
- Kept chart titles short and descriptive so each chart's takeaway is clear without needing the write-up.

## 6. Conclusion

These visualizations translate the Task 2 findings into a format that is quick to interpret: prices and ratings are both broadly distributed across the catalogue, and there is no meaningful relationship between how much a book costs and how it is rated. The charts are included in the accompanying Excel workbook.

## 7. Files Included in This Repository

- BOOKS_CLEAN.xlsx — dataset with the pivot tables and charts referenced above
- Task3 — this write-up document
