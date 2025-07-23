# Real Estate Investment Strategy & Unit Mix Optimization

In today’s competitive real estate market, choosing the right city and designing the optimal unit mix can significantly impact a project’s profitability and risk. This project tackles a realistic investment challenge: guiding a multifamily developer on where to build and how to allocate apartment types to maximize returns under real-world constraints.

---

## Project Overview

A real estate development team is planning to build a new 85-unit Class B apartment building. They are deciding between three U.S. markets and need to determine:
1. **Which city offers the best return on investment** based on historical property performance.
2. **What is the ideal mix of Studio and 1-Bedroom units** to optimize Net Operating Income (NOI), while respecting constraints around floor space, cost structure, and local demand saturation.

I developed a data-backed strategy that helped answer both questions using advanced analytics and simulation modeling.

---

## Business Objective

Deliver an investment recommendation that:
- Identifies the most financially attractive market.
- Recommends an optimal unit mix that balances profit, cost, and demand.
- Accounts for volatility and operational risk across cities.

---

## Approach

**1. Market Analysis**  
Analyzed 300+ historical records on NOI, rent growth, vacancy, and expenses across Fairview, New Hope, and Springfield.

**2. Risk-Return Evaluation**  
Assessed volatility using Coefficient of Variation and Standard Deviation to evaluate the trade-off between high-return vs low-risk markets.

**3. Simulation-Based Unit Mix Modeling**  
Used Monte Carlo simulation to account for uncertain rental income and operating costs. Applied linear programming to find the best mix of Studio and 1-Bedroom units, while staying within:
- A fixed unit count (85)
- Total floor space (80,000 sq ft)
- Rent-driven market demand caps

**4. Strategic Recommendation**  
Delivered a clear, evidence-based strategy optimized for both profitability and feasibility.

---

## Outcome

Recommended investing in **New Hope** with a **55 Studio / 30 1-Bedroom** mix. This configuration:
- Projects **$1.1M+ in annual Net Operating Income**
- Offers the strongest rent and equity growth upside
- Keeps risk within acceptable limits based on historical volatility

---

## Tools Used

- Python (Pandas, NumPy, Matplotlib)
- Excel
- Monte Carlo Simulation
- Linear Programming / Optimization Modeling
- Executive Presentation Design

---

## Files in This Repository

| File | Description |
|------|-------------|
| `strategy recommendation.pdf` | Final presentation deck with strategy, visuals, and recommendation |
| `simulation model.ipynb` | Python notebook for simulation and optimization |
| `historical property data.xlsx` | Dataset of historical building performance |
| `modeling assumptions.pdf` | Key assumptions including cost, demand constraints, and sizing |
| `data documentation.pdf` | Metadata and column descriptions for the dataset |

---


This project brings together market analysis, financial modeling, and simulation to solve a real-world investment challenge. It reflects my approach to business problem-solving: structure the question, analyze the data, model the possibilities, and deliver insights that drive decisions.


