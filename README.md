

# **Understanding Price Elasticity of Demand (PED) and Its Business Implications**

## **1. What is PED and How is it Calculated?**
### **Formula:**
\[
PED = \frac{\%\Delta Q}{\%\Delta P}
\]

Where:
- \(\%\Delta Q\) = Percentage change in quantity demanded
- \(\%\Delta P\) = Percentage change in price

A **log-log regression model** can be used to estimate PED:
\[
\log(Q) = \beta_0 + \beta_1 \log(P) + \epsilon
\]
- **β₁ (Slope)** = PED
- If **β₁ < 0**, demand is inversely related to price (downward sloping curve).

## **2. Why is β₁ the PED in a Log-Log Model?**
The regression equation:
\[
\log(Q) = \beta_0 + \beta_1 \log(P) + \epsilon
\]
Exponentiating both sides:
\[
Q = e^{\beta_0} P^{\beta_1} e^{\epsilon}
\]
Since PED is \( \frac{dQ}{dP} \times \frac{P}{Q} \), differentiating and simplifying confirms that **β₁ directly represents PED**.

## **3. What Happens When β₁ Varies?**
| **PED (β₁)** | **Demand Type** | **Effect** |
|-------------|-----------------|-----------|
| β₁ < -1 | Elastic | Lowering price increases total revenue |
| -1 < β₁ < 0 | Inelastic | Raising price increases total revenue |
| β₁ = -1 | Unit Elastic | Revenue remains unchanged |
| β₁ > 0 | Veblen Goods | Higher price increases demand |

## **4. Why is e^β₀ Ignored in PED Calculation?**
- It is a **constant scaling factor**, not affecting **relative percentage changes**.
- PED measures **elasticity (proportional response)**, not absolute demand.

## **5. Visual Representation of Price vs. Quantity (PED Graphs)**
- **Downward-sloping curve**: Normal demand (β₁ < 0)
- **Flat line**: Perfectly inelastic demand (β₁ = 0)
- **Upward-sloping curve**: Veblen goods (β₁ > 0)

## **6. How is PED Used in Business?**
### **Pricing Strategy**
- **Elastic Demand**: Lower prices to increase revenue.
- **Inelastic Demand**: Raise prices to boost revenue.

### **Demand Forecasting**
- Predicts **impact of price changes on sales**.
- Helps in **inventory management & supply chain planning**.

### **Marketing & Promotions**
- If **elastic**, price cuts boost sales.
- If **inelastic**, promotions have little effect.

## **7. Why Does the Significance of Regression Matter?**
- **p-value < 0.05** → Price significantly affects demand.
- **Low R²** → Price alone does not explain demand (add other factors like seasonality).
- **Confidence Interval for β₁** → Narrower intervals mean more precise PED estimates.

## **8. What If Regression is Not Significant?**
- **Check omitted variables** (e.g., seasonality, competitor pricing).
- **Use different models** (time-series, panel data).
- **Improve data quality** (clean pricing and demand data).

## **9. Significance Level and Business Decisions**
| **Scenario** | **PED Value (β₁)** | **Significance (p-value)** | **Action** |
|-------------|------------------|--------------------|---------|
| High Elasticity | \( \beta_1 < -1 \) | p < 0.05 | Lower price to increase revenue |
| Low Elasticity | \( -1 < \beta_1 < 0 \) | p < 0.05 | Raise price to increase revenue |
| No Significance | Any β₁ | p > 0.05 | Consider other demand drivers |

## **10. Sensitivity Analysis in Pricing and Revenue Optimization**
- **Tornado Charts**: Identifies which variables impact revenue the most.
- **Scenario Analysis**: Compares revenue under different price assumptions.
- **Price Elasticity Simulation**: Tests different pricing strategies to find optimal pricing.

## **Final Takeaway**
- **PED is critical** for pricing, demand forecasting, and revenue optimization.
- **Statistical significance ensures reliable PED estimates** before making business decisions.
- **If regression isn’t significant**, explore additional demand-influencing factors.
