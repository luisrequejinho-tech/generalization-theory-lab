# Generalization Theory, Illustrated

A hands-on study project covering **PAC learning theory** and **Elements of Statistical Learning** (Hastie, Tibshirani & Friedman), Chapter 7 — Model Assessment and Selection (through Section 7.6, Effective Number of Parameters).

Every concept is simulated with real (synthetic) data rather than just stated abstractly — a full 200,000-student "population" is generated so true/population quantities (normally impossible to know in real life) can be computed directly and compared against what the theory predicts from a small sample.

## View it

- **Notebook (renders natively on GitHub):** [generalization_theory.ipynb](./generalization_theory.ipynb)
- **Standalone HTML version (no Jupyter required):** [view rendered HTML](https://htmlpreview.github.io/?https://github.com/luisrequejinho-tech/generalization-theory-lab/blob/main/generalization_theory.html)

## What's inside

1. Empirical risk vs. true risk, and ERM
2. Hoeffding's inequality (concentration for one function)
3. The union bound (finite function classes)
4. VC dimension and shattering (infinite function classes)
5. The sample complexity formula
6. Bias-variance decomposition (ESL Figure 7.3 style, regression + classification)
7. Training error, optimism, and in-sample error (ESL Sections 7.4–7.5)
8. Cp and AIC as model-selection criteria (ESL Figure 7.4 style, Section 7.6)

**Running example:** predicting a student's exam score (and separately, pass/fail) from hours studied.

## Running it yourself

\`\`\`bash
pip install numpy matplotlib scipy scikit-learn jupyter nbformat
jupyter notebook generalization_theory.ipynb
\`\`\`

## Background

Based on:
- *The Elements of Statistical Learning* (2nd ed.), Chapter 7
- Daniel E. Acuna's "Empirical Risk vs. Risk — Generalization Theory" lecture (CU Boulder)
- A follow-up lecture on Sample Complexity and PAC Learning Theory
