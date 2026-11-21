# George-Stores-Analysis
I built an Excel dashboard to explore how George Store’s sales and order volume vary across months, customer groups, states, and sales channels. The workbook brings six PivotTable summaries into one report.
Download [the Excel workbook](./George%20Store%20Data%20Analysis.xlsx), open it in Microsoft Excel, and select **George Store Report 2026**. To inspect the figures behind a chart, open its corresponding analysis sheet. The **George Store** sheet contains the underlying records.

Analysis sheet | Question it answers |
| --- | --- |
| Sales Vs Orders | How do sales amount and order volume change from month to month? |
| Men Vs Women(Sales) | How do sales amounts compare across the gender groups in the data? |
| Order Status | How are order records distributed across statuses? |
| Sales,Top 5 States | Which five states account for the highest sales amounts? |
| Age and Gender | What share of order records comes from each age and gender group? |
| Channels | What share of order records comes through each sales channel? |

## How I built it

1. I cleaned and processed the store records in Excel to prepare them for analysis.
2. I created PivotTables to summarize sales amounts and count order records across the six views.
3. I built dashboard charts from those tables so readers can compare trends and explore the underlying figures.

The workbook measures sales by summing the Amount field. It measures order volume by counting entries in the Order ID field, so repeated IDs contribute once per record.

## Findings

- Women accounted for 64.0% of total sales value.
- Maharashtra ranked first by sales value, followed by Karnataka and Uttar Pradesh. Together, the three states accounted for 36.6% of sales value.
- Customers aged 30–49 accounted for 50.1% of order records, the largest share of any age group. Women in this age group accounted for 34.6% of all order records.
- Amazon (35.5%), Myntra (23.4%), and Flipkart (21.6%) were the largest channels by order volume. Together, they accounted for 80.4% of order records.

## Recommendation

Test a campaign aimed at women aged 30–49 in Maharashtra, Karnataka, and Uttar Pradesh, using ads or channel-specific coupons on Amazon, Myntra, and Flipkart. The dashboard identifies the leading states and channels separately. Before allocating the budget, compare orders from this customer group across each state and channel. Track incremental sales and margin after discounts and ad spend to decide where to expand the campaign.



