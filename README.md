# A/B Testing Analysis: Statistical and Business Evaluation

This repository contains a comprehensive A/B testing framework that combines traditional hypothesis testing, Bayesian analysis, statistical power evaluation, and business impact modeling. It is built to guide data-driven decisions with both statistical rigor and real-world applicability.

## Project Summary

The goal of this project is to assess whether a product variant leads to improved user conversion compared to a control group. The analysis goes beyond p-values by incorporating effect sizes, power calculations, Bayesian probability of superiority, and revenue projections. The project is structured to simulate a real-world experimentation and business decision-making workflow.

## Key Features

- Data cleaning and preprocessing for binary outcome analysis
- Conversion rate comparison using classical z-test
- Bayesian A/B testing with posterior distributions and lift estimates
- Statistical power analysis with effect size sensitivity
- Business revenue impact analysis and ROI projections
- Final decision recommendations with confidence levels

## Methodology Overview

1. **Classical Hypothesis Testing**
   - Two-proportion z-test to check statistical significance
   - Estimation of effect size using Cohen's h

2. **Bayesian A/B Testing**
   - Posterior probability that the variant is better
   - Estimation of expected lift and credible intervals

3. **Power Analysis**
   - Current power based on observed effect size
   - Sample size planning for future experiments

4. **Business Impact Evaluation**
   - Revenue per user calculations
   - Projected annual revenue difference
   - Recommendation logic based on uplift and confidence

5. **Comprehensive Summary**
   - Key insights and limitations
   - Business decision logic
   - Next-step guidance for implementation

## Technologies Used

- Python
- Pandas, NumPy
- SciPy, statsmodels
- Matplotlib, Seaborn
- Custom functions for Bayesian simulation and bootstrapping

## How to Use

1. Clone the repository.
2. Run the Jupyter Notebook `ab_test_analysis.ipynb` step-by-step.
3. Review each section (classical stats, Bayesian inference, power analysis, business impact).
4. Use the final summary as a decision-support tool.

## File Structure

- `ab_test_analysis.ipynb` – Main notebook with full analysis pipeline
- `README.md` – This file
- `data/` – Placeholder for A/B test dataset (synthetic or real)

## Use Cases

This project is designed for:

- Product managers evaluating new features
- Data scientists building experimentation pipelines
- Analysts communicating testing outcomes to stakeholders
- Business leaders making go/no-go decisions

## License

This project is open for educational and demonstration purposes. Contact the author if you wish to adapt it for production environments.
