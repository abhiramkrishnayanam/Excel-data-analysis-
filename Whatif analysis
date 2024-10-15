# What-If Analysis in Excel

## Overview
**What-If Analysis** in Excel is a powerful set of tools used for decision making by allowing users to test various scenarios, forecasts, or changes in data inputs. The main tools are:
- **Goal Seek**: Finds the input value required to achieve a specific output.
- **Scenario Manager**: Allows you to create and compare multiple scenarios with different sets of inputs.
- **Data Table**: Enables analysis of how changes in one or two variables affect the result of a formula.

## Prerequisites
- Basic Excel knowledge, including formulas and cell references.
- A well-structured dataset to apply analysis to.

## Sample Dataset

Below is a sample dataset that you can use for What-If Analysis in an electronics store context.

| Product     | Units Sold | Unit Price (₹) | Cost Price (₹) | Total Revenue (₹) | Total Cost (₹) | Profit (₹)      |
|-------------|------------|----------------|----------------|-------------------|----------------|-----------------|
| Laptop      | 100        | 50,000         | 45,000         | `=B2*C2`          | `=B2*D2`       | `=E2-F2`        |
| Smartphone  | 200        | 30,000         | 25,000         | `=B3*C3`          | `=B3*D3`       | `=E3-F3`        |
| Tablet      | 150        | 20,000         | 15,000         | `=B4*C4`          | `=B4*D4`       | `=E4-F4`        |
| Smartwatch  | 80         | 10,000         | 8,000          | `=B5*C5`          | `=B5*D5`       | `=E5-F5`        |
| Headphones  | 300        | 2,000          | 1,500          | `=B6*C6`          | `=B6*D6`       | `=E6-F6`        |

### Column Descriptions:
- **Units Sold**: Number of items sold.
- **Unit Price**: Price per unit of the product.
- **Cost Price**: Manufacturing cost or purchase cost per unit.
- **Total Revenue**: Formula = Units Sold * Unit Price.
- **Total Cost**: Formula = Units Sold * Cost Price.
- **Profit**: Formula = Total Revenue - Total Cost.

---

## 1. Goal Seek

Use **Goal Seek** to determine what value of one input is needed to achieve a specific outcome.

### Example: Find the number of laptops sold to achieve a profit of ₹600,000.

1. Navigate to the `Data` tab, and select **What-If Analysis > Goal Seek**.
2. In the **Set Cell** box, enter the reference to the Profit cell (e.g., `G2` for Laptops).
3. In the **To Value** box, enter `600000`.
4. In the **By Changing Cell** box, enter the reference for the **Units Sold** cell (e.g., `B2` for Laptops).
5. Click **OK** to see the required number of units to achieve the target profit.

---

## 2. Scenario Manager

Use **Scenario Manager** to create and compare multiple scenarios by changing input values.

### Example: Compare different pricing strategies.

1. Navigate to the `Data` tab and select **What-If Analysis > Scenario Manager**.
2. Click **Add** to create a scenario:
   - **Scenario 1**: Increase the unit prices by 10%.
   - **Scenario 2**: Reduce cost prices by 5%.
3. Enter the cells to change (e.g., the Unit Price or Cost Price columns).
4. Input different values for each scenario and click **OK**.
5. Use the **Show** button to view the impact of each scenario.

---

## 3. Data Table

Use **Data Tables** to analyze how changing one or two variables affects a result.

### Example: Analyze the impact of changing smartphone sales on total profit.

1. Set up a table with different values for **Units Sold** for smartphones (e.g., 100, 150, 200, 250, 300) in a column.
2. In the cell next to the first entry of **Units Sold**, reference the total profit formula (`G3` for smartphones).
3. Highlight the entire table range (including the profit formula).
4. Navigate to the `Data` tab, and select **What-If Analysis > Data Table**.
5. In the **Column Input Cell** box, enter the reference for the **Units Sold** cell (e.g., `B3` for smartphones).
6. Click **OK** to generate the profit for each sales quantity.

---

## Additional Tips
- Save your workbook before running complex scenarios or Goal Seek processes.
- Experiment with different pricing, costs, or units sold to understand how changes impact profit.

## Conclusion
Using these tools, you can perform sophisticated What-If Analysis to help make better data-driven decisions in Excel. Apply them to your business scenarios, financial forecasts, or any dataset where you need to explore various possibilities.
