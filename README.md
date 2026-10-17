# E-commerce Sales Analysis

## Project overview

A Power BI analysis of 2018 e-commerce orders, connecting order-line sales and profit with customer geography and order dates. The local source is split across `Details.csv` (line-level amounts, profit, quantity, category, sub-category, and payment mode) and `Orders.csv` (order date and customer/state/city details).

## Data

The details file contains **1,500 order lines** across three categories and five payment methods; the order file contains **500 order records**. All 1,500 detail rows matched to an order record in the supplied files. The order dates span **January 1–December 31, 2018**.

## Findings from the supplied data

- Recorded sales total **437,771** and recorded profit totals **36,963**, for an overall margin of approximately **8.4%**.
- **529 of 1,500 order lines** show a loss. Positive aggregate profit therefore masks a substantial share of loss-making lines.
- Electronics generates the most sales (**166,267**) and profit (**13,162**); clothing is next in sales (**144,323**) and has the highest category profit (**13,325**). Furniture contributes **127,181** in sales and **10,476** in profit.
- COD is the largest payment mode by sales at **155,181**, followed by credit card (**86,932**) and EMI (**77,881**).
- Maharashtra leads the available state-level sales at **102,498**, followed by Madhya Pradesh at **87,463**.

## Portfolio summary

Joined order-line and order-header data to examine sales, profit, product mix, payment behavior, and geography. The analysis highlights electronics as the leading category by sales, COD as the most-used sales channel by value, and a meaningful loss-making share that merits follow-up at the product or sub-category level.

## Reproducibility note

Findings are calculated from the two adjacent CSVs. Amounts are reported in the source's unspecified currency. The `.pbix` did not expose a standard `Report/Layout` entry during inspection, so the report's exact visuals and any DAX-specific definitions could not be verified.
