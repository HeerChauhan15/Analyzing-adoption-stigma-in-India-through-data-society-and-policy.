# Societal Perception and Stigma Around Adoption in India

## 📘 Project Overview
This research project presents a comprehensive socio-analytical study of adoption in India, focusing on societal stigma, gender bias, infertility-related influences, and awareness of legal frameworks. Despite progressive adoption laws, adoption continues to be constrained by cultural norms emphasizing biological lineage, caste, and social legitimacy.

The study applies data analytics, statistical methods, and machine learning models to examine how these factors shape public attitudes toward adoption, particularly girl child adoption and single-parent adoption.

---

## 🎯 Research Objectives
This study was conducted with the following objectives:

1. To examine how infertility caused by PCOD/PCOS influences the timing and willingness of couples to adopt a child.  
2. To analyze how fear of social judgment affects couples considering adoption.  
3. To assess the impact of gender preference and pre-birth sex determination on adoption decisions, particularly when choosing between a girl or a boy.  
4. To propose practical solutions that can position adoption as a respected and accepted family choice in India.  
5. To develop awareness strategies that integrate reproductive health education with positive attitudes toward adoption.  
6. To investigate how social stigma, false beliefs, and lack of accurate information discourage adoption.  
7. To recommend collaborative approaches involving NGOs, healthcare professionals, and adoption agencies to promote unbiased adoption practices.  
8. To study the influence of the ban on sex determination on gender preference patterns in India.  

---
## 🧪 Research Methodology

### 🔹 Study Design
A **mixed-method research design** combining quantitative statistical analysis with qualitative thematic interpretation.

### 🔹 Data Collection
- Primary data collected via structured Google Form surveys  
- Respondents from diverse age groups, genders, and geographic regions  
- Survey data exported as CSV files for analysis  

### 🔹 Quantitative Techniques
- Descriptive Statistics  
- Chi-Square Test of Independence  
- ANOVA  
- Correlation Analysis  
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest  
- XGBoost  
- CatBoost  

### 🔹 Qualitative Techniques
- Thematic analysis of open-ended survey responses  
- Focus on stigma, gender norms, infertility narratives, and social pressure  

### 🔹 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, XGBoost, CatBoost)  
- Excel (Exploratory visualization)  
- SPSS (Statistical validation)  

---

## 📈 Results & Models

This section summarizes the statistical findings and predictive machine learning models used to analyze adoption attitudes in India.

### 📊 Statistical Findings
- **Chi-Square Test** revealed a statistically significant association between gender preference and willingness to adopt a girl child (p < 0.05), confirming the influence of gender bias.
- **ANOVA** results showed no significant difference in mean adoption willingness across gender-preference groups, indicating that attitude distribution is more informative than average values.
- **Correlation Analysis** demonstrated that social stigma and residence type (urban vs rural) have stronger associations with adoption attitudes than regional location alone.

---

### 🤖 Machine Learning Models Applied

Multiple supervised learning models were implemented to predict adoption attitudes and willingness:

#### 1. Logistic Regression
- Baseline, interpretable model  
- Achieved ~93% accuracy in multi-class adoption attitude prediction  
- Identified stigma, gender preference, and region as significant predictors  

#### 2. Decision Tree Classifier
- Used for rule-based interpretability and regional analysis  
- Highlighted **social stigma as the primary splitting variable**, particularly in northern regions  
- Demonstrated that lower stigma strongly predicts higher adoption willingness  

#### 3. Random Forest
- Best-performing model for PCOS-related adoption willingness  
- Accuracy: ~79%, AUC: ~0.84  
- Captured nonlinear interactions among infertility, awareness, income, and age  

#### 4. XGBoost
- High predictive accuracy (~93%)  
- Effectively modeled complex feature interactions  
- Ranked stigma and legal awareness as the most influential predictors  

#### 5. CatBoost
- Accuracy: ~91%  
- Efficient handling of categorical survey data with minimal preprocessing  
- Delivered balanced class-wise performance and reliable feature importance  

---

### 🔍 Feature Importance Insights
- **Social stigma** emerged as the strongest determinant of adoption attitudes  
- **Awareness of adoption laws and the PCPNDT Act** significantly increased openness to adoption  
- **Infertility (PCOS)** increased willingness to adopt but did not override social pressure  
- Demographic variables (age, education, years married) played secondary roles  

---
### 📌 Model Comparison Overview

| Model               | Key Strength                                | Limitation |
|--------------------|----------------------------------------------|------------|
| Logistic Regression | High interpretability, strong baseline       | Linear assumptions |
| Decision Tree       | Clear rule-based insights                    | Overfitting risk |
| Random Forest       | Best generalization for infertility analysis | Reduced interpretability |
| XGBoost             | High accuracy, captures complex interactions| Requires tuning |
| CatBoost            | Ideal for categorical data                  | Slightly slower |

---

### 🧠 Key Takeaway
Adoption attitudes in India are driven primarily by **social stigma and awareness**, rather than demographic factors alone. The combined statistical and machine learning analysis confirms that reducing stigma and improving legal and health-related awareness can significantly increase acceptance of adoption, especially for girl children and non-traditional families.

---

## ✅ Conclusion (With Respect to Research Objectives)

The study demonstrates that infertility caused by PCOD/PCOS significantly increases openness toward adoption; however, the decision is often delayed due to emotional stress and fear of societal judgment. This highlights the need for early counseling that presents adoption as a positive and planned choice rather than a last resort.

Findings reveal that social judgment remains one of the strongest barriers to adoption. Couples often hesitate due to concerns about family acceptance, community opinions, and cultural expectations related to biological lineage. These social pressures outweigh legal or procedural challenges.

Gender preference continues to influence adoption decisions, with a clear bias toward male children in certain regions. However, the ban on sex determination has indirectly reduced overt gender selection, leading to gradual shifts in attitudes and increased acceptance of girl child adoption among informed and urban populations.

The research confirms that stigma, myths, and misinformation significantly discourage adoption. Lack of accurate knowledge about adoption laws, processes, and post-adoption realities fuels fear and hesitation among prospective parents.

To normalize adoption as a respected family choice, the study recommends integrating reproductive health education with adoption awareness. Counseling for PCOD/PCOS patients should include adoption as a valid and fulfilling pathway to parenthood.

Collaboration between NGOs, doctors, and adoption agencies is essential to address bias and misinformation. Healthcare professionals can play a crucial role by providing unbiased guidance, while NGOs and agencies can support awareness campaigns and simplify adoption procedures.

Overall, the study concludes that adoption acceptance in India depends primarily on reducing social stigma, improving awareness, and aligning health, legal, and social systems to support inclusive and informed adoption practices.

---

## 🌐 System Design Case Study: Ever Belong Adoption Platform
The project includes a system documentation case study of **Ever Belong**, a conceptual adoption services web application designed to demonstrate how digital systems can enhance transparency, trust, and accessibility in adoption workflows.

### Core Features
- Multi-step digital adoption application process  
- Family–child matching logic  
- Administrative dashboard for application review  
- Post-adoption support and resource integration  

This case study highlights the role of **user-centered system design** in improving efficiency and trust in adoption services.

---

## ⚠️ Limitations
- Limited sample size relative to the national population  
- Self-reported data subject to response bias  
- Online-only data collection excludes digitally marginalized groups  
- Cross-sectional design limits longitudinal inference  

---

## 👩‍🎓 Author
**Heer Chauhan**  
T.Y. B.Sc. Data Science & Business Analytics  
HSNC University, Mumbai  

---

## 🏷️ Keywords
Adoption Analytics · Social Stigma · Gender Bias · PCOS · Machine Learning · Public Perception · India
[Heer_blackbook.pdf](https://github.com/user-attachments/files/24414732/Heer_blackbook.pdf)
