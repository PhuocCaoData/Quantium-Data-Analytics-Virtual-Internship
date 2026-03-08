# Quantium Data Analytics Virtual Internship
Data analytics and commercial strategy project for a retail supermarket.

## 📌 Project Overview
This repository contains my solutions for the **Quantium Data Analytics Virtual Internship** program. The project focuses on deriving actionable insights from retail transaction data and evaluating store performance through A/B testing, ultimately culminating in a commercial report.

## 🛠️ Tools & Technologies
- **Language:** R
- **Libraries:** `tidyverse`, `lubridate`, `scales`, `patchwork`, `knitr`
- **Reporting:** R Markdown (PDF generation via XeLaTeX)

---

## 📊 Project Tasks & Outcomes

### Task 1: Retail Strategy and Analytics
**Requirement:** *Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.*

**Key Insights:**
- **'Older Families - Budget'** and **'Young Singles/Couples - Mainstream'** are the top contributors to total sales.
- 'Young Singles/Couples - Mainstream' have a strong tendency to make impulse purchases and are 23% more likely to purchase **Tyrrells** chips compared to the rest of the population.
- **27.5%** of the customer base consists of one-time buyers.
- Budget products (under $3.00) generate only 19.1% of total revenue.

**Strategic Recommendations:**
1. **Impulse Buying:** Place premium brands like Tyrrells and Doritos in high-visibility areas or near checkout counters to stimulate impulse purchases among Young Singles/Couples.
2. **Promotion:** Run bundle promotions for large packs (380g, 270g) designed specifically for social gatherings.
3. **Pricing Strategy:** Avoid deep discounts for Premium lines (Kettle, Tyrrells) as the target segment accepts higher unit prices ($4.07). Focus on value-add or product novelty.
4. **Supply Chain Optimization:** Ensure shelves are fully restocked with top-selling 175g and 380g packs by Thursday evening to capture Friday and Sunday sales peaks.
5. **Customer Retention:** Implement "bounce-back" vouchers on receipts to incentivize one-time buyers to return.
6. **Family Value Bundles:** Combine preferred brands (Red Rock Deli) with high-margin private labels (Woolworths) to maximize basket volume for 'Older Families - Budget'.
7. **Shelf-Space Reallocation:** Reduce display area for budget products and allocate prime, eye-level shelf space to Mid-tier and Premium segments.

---

### Task 2: Experimentation and Uplift Testing (A/B Testing)
**Requirement:** *Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.*

**Methodology:**
- Selected trial stores (77, 86, 88) were matched with statistically similar control stores based on historical sales magnitude and correlation.
- Evaluated the trial period (Feb 2019 - April 2019) using **T-tests** and **visual bounds testing (95th percentiles)**.

**Results & Insights:**
1. **Stores 77 & 88** demonstrated a statistically significant uplift in both customer volume and total sales revenue compared to their respective control stores during the critical trial months (March & April).
2. **Store 86** saw a highly significant increase in customer footfall, though its sales uplift was not as strongly correlated with the increased traffic.

**Recommendations:**
- The new trial layouts successfully draw higher foot traffic and drive revenue. **Roll out this new layout to all standard stores.**
- Conduct a secondary check on Store 86's merchandising flow to understand why its basket sizes/sales did not increase proportionally with the footfall.

---

### Task 3: Analytics and Commercial Application
**Requirement:** *Use your analytics and insights from Task 1 and 2 to prepare a report for your client, the Category Manager.*

**Overview:**
- Synthesized the findings from the data analysis (Task 1) and the A/B testing evaluation (Task 2) into a comprehensive, commercially viable presentation.
- The final report focuses on delivering clear, data-driven actionable strategies for the Category Manager, supported by professional visualizations and statistical evidence. *(See `Task 3.pdf` for the full presentation).*

---
