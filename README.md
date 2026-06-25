# DVC Student Reading Habits Statistical Analysis

An inferential statistical study investigating the differences between male and female DVC students regarding their weekly leisure reading hours and genre preferences.

---

##  Project Overview
* **Author:** Jinyoung Shin
* **Course:** Stat C1000 (Instructor: Willet Peter)
* **Date:** May 18, 2026
* **Tool Used:** **StatCrunch** (Data Cleaning, Descriptive & Inferential Statistics)

---

##  Key Methodology & Dataset
* **Sample Size:** 68 independent anonymous responses (33 Female, 35 Male) collected across multiple campus zones (cafeteria, walkways, library).
* **Descriptive Analysis:** Structured data into a frequency distribution table and analyzed skewness using histograms and 5-number summaries.
* **Genre Preferences:** Revealed that *Romance* (33.33%) was dominant among females, while *Sci-Fi/Fantasy* (22.86%) was the top choice for males.

---

##  Summary Statistics & Core Findings

| Metric | Female Sample | Male Sample |
| :--- | :---: | :---: |
| **Sample Mean ($\bar{x}$)** | 3.193 hours | 1.895 hours |
| **Standard Deviation ($s$)** | 2.300 hours | 1.906 hours |
| **5-Number Summary** | (0, 1.45, 3.0, 4.1, 9.0) | (0, 0.5, 1.3, 3.0, 7.4) |

### 1. 95% Confidence Interval
* **Interval:** `[0.271, 2.325]` hours for $\mu_1 - \mu_2$.
* **Conclusion:** Since the interval includes only positive numbers and excludes zero, it statistically demonstrates that female students read more on average.

### 2. Hypothesis Testing
* **Null Hypothesis ($H_0$):** $\mu_1 = \mu_2$
* **Alternative Hypothesis ($H_a$):** $\mu_1 > \mu_2$
* **P-value:** `0.007` (Reject $H_0$ at $\alpha = 0.05$)
* **Final Result:** There is sufficient evidence to support the claim that female DVC students spend significantly more time reading for pleasure than male students. The 1.30-hour sample gap is statistically meaningful and not due to random chance.
