# Algorithmic Marketing & A/B Testing Portfolio

Welcome to the data science section of my portfolio. This space is dedicated to algorithmic marketing frameworks, quantitative A/B testing methodologies, and advanced statistical validation models designed to optimize digital ad spend and measure true brand attribution.

---

## Project: YouTube Brand Lift Survey (BLS) & Statistical Significance Validation
**File:** `Algorithmic_Marketing .pdf` (Quantitative Case Analysis)

A comprehensive statistical audit evaluating consumer brand awareness lift following a targeted YouTube advertising campaign. The analysis segments audience data by age demographics to isolate exact variance factors and prevent skewed marketing budget allocations.

### Core Data Science & Marketing Insights
* **Hypothesis Testing & Z-Score Formula:** Conducted two-tailed Z-tests to validate whether observed brand awareness lifts were statistically significant or driven by random sampling noise. Leveraged the standardized error variance equation:
  $$z = \frac{p_{T} - p_{C}}{\sqrt{p(1-p)(\frac{1}{n_{T}} + \frac{1}{n_{C}})}}$$
* **Demographic Segmentation Matrix:** Dissected the total experimental volume ($N = 4,000$ respondents) into specialized test groups to evaluate localized lifts:
  * **Core Cohort (18-34 years):** Achieved an absolute **+4% Awareness Lift** ($P_{Exposed} = 42\%$, $P_{Control} = 38\%$) with a calculated $Z$-score of **$2.8$**. Since $Z > 1.96$, the uplift is statistically significant at a 95% confidence level.
  * **Mature Cohort (35-54 years):** Achieved a **+5% Awareness Lift** ($P_{Exposed} = 46\%$, $P_{Control} = 41\%$) but resulted in a $Z$-score of **$1.3$**. This confirms the lift is *not* statistically significant and could be due to random variation.
* **Financial Lift & iROAS Modeling:** Extrapolated the verified conversion lifts to evaluate macro business impacts—mapping out a simulated **+€10,000 Sales Uplift** and establishing an Incremental Return on Ad Spend (**iROAS**) metric of **2.0**.
* **Data-Driven Budget Allocation:** Formulated executive recommendations to shift capital deployment away from unverified high-variance demographics and concentrate incremental ad spend entirely on the high-performing 18-34 cohort to maximize long-term brand equity.

### Key Competencies Demonstrated
* Quantitative A/B Testing Strategy & Brand Lift Survey (BLS) Architecture
* Statistical Significance Validation (Z-tests, P-Values, Variance Tracking)
* Audience Segmentation Modelling & Incremental ROAS (iROAS) Optimization
