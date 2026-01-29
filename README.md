<p align="center">
  <img src="app/assets/images/team_framework_logo_alpha.png" alt="Team Framework logo" width="520">
</p>

<h1 align="center"><strong>Data driven house price analysis and prediction</strong></h1>

<p align="center">
  <img src="app/assets/images/inflation.gif" alt="House price inflation animation" width="520">
</p>

<p align="center">
  <em>Visual metaphor for house price inflation and market dynamics</em>
</p>

A data analytics and AI project exploring residential house prices using Python, machine learning, and an interactive dashboard.

## Table of Contents

- [Client Brief](#client-brief)
  - [Client Needs](#client-needs)
- [Project Aim](#project-aim)
- [Hackathon Delivery Model](#hackathon-delivery-model)
- [Team Structure (Fixed for All 3 Days)](#team-structure-fixed-for-all-3-days)
  - [Project Lead / Product Owner (Person A – Lead)](#1-project-lead--product-owner-person-a--lead)
  - [Data & Modelling Engineer (Person B)](#2-data--modelling-engineer-person-b)
  - [Dashboard & UX Engineer (Person C)](#3-dashboard--ux-engineer-person-c)
- [Day-by-Day Breakdown (With Explicit Deliverables)](#day-by-day-breakdown-with-explicit-deliverables)
  - [DAY 1 — Foundations & Direction (Critical)](#day-1--foundations--direction-critical)
  - [DAY 2 — Analysis, AI Integration & Insight Generation](#day-2--analysis-ai-integration--insight-generation)
  - [DAY 3 — Polish, Evidence & Submission Readiness](#day-3--polish-evidence--submission-readiness)
- [Accountability Matrix (Condensed)](#accountability-matrix-condensed)
- [Key Hackathon Rule](#key-hackathon-rule)
- [Purpose](#purpose)
- [Business Case](#business-case)
- [Target Audience](#target-audience)
- [Project Hypotheses](#project-hypotheses)
- [Project Learnings & Problem Log](#project-learnings--problem-log)
- [Project Plan (LO10)](#project-plan-lo10)
- [Exploratory Data Analysis](#exploratory-data-analysis-summary)
- [Feature Engineering](#feature-engineering) 
- [Predictive Modelling](#predictive-modelling)
- [Model Performance and Results](#Model-Performance-and-Results)
- [Hypotheses Conclusions](#Hypotheses-Conclusions)
- [Limitations](#Limitations)
- [Future Development](#future-development)
- [Credits](#Credits)

- [Output](#output)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Predictive Modelling](#predictive-modelling)
- [Future Development](#future-development)
- [Data](#data)
- [Collaborators](#collaborators)
- [Team Members & Contributions](#team-members--contributions)
- [Credits](#credits)

## Client Brief

The client is a **property analytics stakeholder** operating within the residential housing market who requires a **data-driven decision-support tool** to better understand the factors influencing house prices and to improve price estimation accuracy.

Currently, property valuation decisions rely heavily on manual appraisal, market intuition, or limited historical comparisons. These approaches can be inconsistent, slow to adapt to market changes, and prone to bias. The client requires a **transparent, explainable, and interactive analytics solution** that transforms historical housing data into actionable insights.

### Client Needs

- Understand which property features most strongly influence sale prices  
- Explore patterns, trends, and anomalies within historical housing data  
- Access predictive price estimates based on comparable property characteristics  
- Communicate insights clearly to both technical analysts and non-technical decision-makers  

The solution must adhere to **ethical data practices**, use **publicly available and anonymised data**, and be delivered through an **accessible web-based dashboard** that supports exploration, interpretation, and future extension.

---

## Project Aim

The aim of this project is to design and deliver a **Data Analytics Web Application** that applies **statistical analysis, machine learning, and data visualisation techniques** to analyse and predict residential property sale prices.

Using Python-based data analytics tools and a Streamlit user interface, the project will:

- Perform exploratory data analysis (EDA) to identify key drivers of house prices  
- Apply statistical methods to summarise, compare, and interpret housing features  
- Develop and evaluate predictive models to estimate property sale values  
- Present insights through interactive visualisations and narratives tailored to different audiences  
- Demonstrate responsible data handling, including data cleaning, transformation, and documentation  
- Integrate generative AI tools to support ideation, analysis, and data storytelling  

The final outcome is a **publishable, professional-grade dashboard** that supports informed decision-making in the housing domain while clearly evidencing all required learning outcomes (LO1–LO11) of the **Data Analytics with Artificial Intelligence Bootcamp**.

---

## Hackathon Delivery Model

This project follows a **3-person, 3-day hackathon**, with one designated lead. Roles and responsibilities are explicitly mapped to the **Data Analytics with AI Bootcamp Learning Outcomes (LO1–LO11)** to maximise assessment coverage, avoid duplication, and mitigate assessment risk.

---

## Team Structure (For All 3 Days)

### 1. Project Lead / Product Owner (Person A – Lead)

**Primary accountability:** Coherence, assessment coverage, business rationale, and final submission quality.  
This role orchestrates delivery and provides final sign-off.

**Primary Learning Outcomes Owned:**  
- LO3, LO7, LO8, LO9, LO10, LO11 (final sign-off on all LOs)

---

### 2. Data & Modelling Engineer (Person B)

**Primary accountability:** Data integrity, analysis correctness, modelling, and statistics.

**Primary Learning Outcomes Owned:**  
- LO1, LO2, LO3, LO5

---

### 3. Dashboard & UX Engineer (Person C)

**Primary accountability:** Streamlit application, visualisations, UX, accessibility, and storytelling.

**Primary Learning Outcomes Owned:**  
- LO2, LO4, LO8

---

## Day-by-Day Breakdown (With Explicit Deliverables)

### DAY 1 — Foundations & Direction (Critical)

**Goal:** Lock scope, dataset, structure, and eliminate ambiguity early.

#### Project Lead (Person A)

**Responsibilities**
- Finalise project idea aligned to a real-world user need  
- Define target audience and business problem  
- Select and approve a public, anonymised, assessable dataset  
- Create GitHub repository structure:

- Draft README skeleton:
- Purpose  
- Business Case  
- Target Audience  
- Hypotheses (mandatory)  
- Project Plan (LO10)

**Learning Outcomes Covered**
- LO3 – Problem framing  
- LO7 – Project organisation  
- LO9 – Domain relevance  
- LO10 – Planning  

---

#### Data & Modelling Engineer (Person B)

**Responsibilities**
- Load dataset into Jupyter Notebook  
- Perform:
- Initial EDA  
- Missing value analysis  
- Feature overview  
- Implement core statistics:
- Mean, median, variance, standard deviation  
- Probability and distributions  
- Save cleaned dataset to `/data/processed/`

**Deliverables**
- `01_eda_and_statistics.ipynb`  
- Cleaned CSV with documented pipeline  

**Learning Outcomes Covered**
- LO1 – Statistics & probability  
- LO2 – Python data manipulation  
- LO5 – Data management  

---

#### Dashboard & UX Engineer (Person C)

**Responsibilities**
- Scaffold Streamlit app:
- Navigation  
- Page layout  
- Placeholder visuals  
- Identify at least four plot types (e.g. bar, line, box, scatter, map)  
- Implement basic accessibility:
- Labels  
- Tooltips  
- Clear information hierarchy  

**Deliverables**
- Running Streamlit app with dummy data  
- Documented UI/wireframe decisions  

**Learning Outcomes Covered**
- LO8 – Communication  
- UX & accessibility requirements  

---

### DAY 2 — Analysis, AI Integration & Insight Generation

**Goal:** Produce assessable analytics and intelligence.

#### Project Lead (Person A)

**Responsibilities**
- Write methodology narrative:
- Why these methods?  
- Why these visuals?  
- Draft Ethics & Governance section:
- Bias  
- Privacy  
- GDPR considerations  
- Ensure AI usage is explicitly documented  

**Learning Outcomes Covered**
- LO6 – Ethics  
- LO7 – Methodology  
- LO11 – Reflection on tools  

---

#### Data & Modelling Engineer (Person B)

**Responsibilities**
- Implement at least one model:
- Regression / classification / clustering  
- Evaluate model:
- Metrics  
- Limitations  
- Alternatives  
- Explicitly document AI assistant usage (e.g. Copilot, ChatGPT)  
- Save results for dashboard integration  

**Deliverables**
- `02_modelling.ipynb`  
- Metrics table  
- Commentary markdown cells  

**Learning Outcomes Covered**
- LO2 – Advanced analysis  
- LO3 – Problem solving  
- LO4 – AI-enhanced analysis  

---

#### Dashboard & UX Engineer (Person C)

**Responsibilities**
- Replace placeholders with real data  
- Integrate:
- Interactive filters  
- Hover tooltips  
- Clear narrative flow  
- Add clearly labelled AI-generated insight summary  

**Deliverables**
- Polished Streamlit dashboard  
- At least four meaningful plot types  

**Learning Outcomes Covered**
- LO4 – AI storytelling  
- LO8 – Visual communication  

---

### DAY 3 — Polish, Evidence & Submission Readiness

**Goal:** Remove assessor doubts.

#### Project Lead (Person A)

**Responsibilities**
- Finalise README:
- Hypotheses validation  
- Limitations  
- Future roadmap  
- Maintenance & updates (LO10)  
- Verify all learning outcomes are explicitly evidenced  
- Review git history:
- Small, logical commits  
- Clear messages  

**Learning Outcomes Covered**
- LO8 – Documentation  
- LO10 – Lifecycle planning  
- LO11 – Continuous learning  

---

#### Data & Modelling Engineer (Person B)

**Responsibilities**
- Final code clean-up:
- Docstrings  
- Comments  
- Reproducibility  
- Validate statistical outputs  
- Ensure notebooks run end-to-end  

**Learning Outcomes Covered**
- LO1–LO5 robustness  

---

#### Dashboard & UX Engineer (Person C)

**Responsibilities**
- Final UX pass:
- Accessibility  
- Consistency  
- Error handling  
- Ensure the dashboard communicates insights independently  

**Learning Outcomes Covered**
- LO8 – Non-technical communication  
- UX compliance  

---

## Accountability Matrix (Condensed)

| Learning Outcome | Owner |
|---|---|
| LO1 – Statistics | Person B |
| LO2 – Python & Tools | Person B / Person C |
| LO3 – Problem Analysis | Person A / Person B |
| LO4 – AI Usage | Person B / Person C |
| LO5 – Data Management | Person B |
| LO6 – Ethics | Person A |
| LO7 – Research Design | Person A |
| LO8 – Communication | Person C |
| LO9 – Domain Context | Person A |
| LO10 – Planning | Person A |
| LO11 – Reflection & Adaptation | All (compiled by Person A) |

---

## Key Hackathon Rule

**No one “helps” casually.**  
Each task has **one clear owner**. Others may review but not rewrite. This protects against:

- Plagiarism concerns  
- Git history ambiguity  
- Assessment gaps  

## Purpose

The purpose of this project is to develop a **data-driven analytics application** that helps stakeholders understand and predict residential house prices. By combining statistical analysis, machine learning, and interactive visualisation, the project aims to transform historical housing data into **clear, actionable insights**.

The application is designed to support both **technical and non-technical users** by providing:
- Transparent analysis of the factors influencing house prices  
- Explainable predictive models  
- An intuitive Streamlit dashboard for exploration and decision support  

---

## Business Case

Accurate house price estimation is critical for stakeholders operating in the residential property market. Traditional valuation methods often rely on manual appraisal, market intuition, or limited comparable sales, which can be subjective and inconsistent.

This project addresses the business need for a **reliable, scalable, and explainable pricing support tool** by:
- Identifying the most influential property features affecting sale prices  
- Highlighting trends, patterns, and anomalies in historical housing data  
- Providing predictive price estimates based on comparable property characteristics  

By adopting a data analytics and AI-driven approach, the project demonstrates how organisations can improve pricing accuracy, reduce risk, and support evidence-based decision-making in the housing market.

---

## Target Audience

The primary target audience for this project includes:

- **Property analysts and valuation professionals** seeking data-supported insights to complement traditional appraisal methods  
- **Real estate professionals and decision-makers** who require interpretable insights into pricing drivers and market trends  

The secondary target audience includes:

- **Non-technical stakeholders** interested in understanding housing market dynamics through clear visualisations and summaries  
- **Students and data analysts** exploring applied data analytics and machine learning in a real-world context  

---

## Project Hypotheses

The following hypotheses guide the analytical approach of this project and are evaluated using exploratory data analysis and predictive modelling:

1. **Property size and quality features** (e.g. living area, number of rooms, overall quality) have a significant positive impact on house sale prices.  
2. **Location-related features** contribute substantially to price variation across properties.  
3. **Newer properties** or properties with recent renovations tend to achieve higher sale prices than older properties.  
4. **Machine learning models** can predict house prices with greater accuracy than simple baseline statistical methods when trained on cleaned and engineered features.

Each hypothesis is tested and validated through data exploration, statistical analysis, and model evaluation within the Jupyter notebooks and reflected in the dashboard insights.

---
## Project Learnings & Problem Log

This section records key challenges encountered during development, how they were resolved, and lessons learned.  
It is intended as a shared reference for collaborators and future maintainers.

| Date       | Area    | Problem                                | Resolution        | What We Learned                     | Screenshot |
|------------|---------|----------------------------------------|-------------------|-------------------------------------|------------|
| 2026-01-28 | Process | No central place to record problems    | Added log section | Capture issues early saves time     | [![Problem log][pl-log]] |
| YYYY-MM-DD |         |                                        |                   |                                     |            |

[pl-log]: app/assets/images/project_learnings_problem_log.png



## Project Plan (LO10)

This project follows a structured, time-bound development plan aligned with best practices in data analytics and the learning outcomes of the Data Analytics with Artificial Intelligence Bootcamp.

### Phase 1: Data Collection and Preparation
- Source publicly available, anonymised housing data  
- Load and inspect the dataset using Pandas  
- Clean and preprocess data (handle missing values, outliers, and skewness)  
- Store cleaned data in a structured project directory  

### Phase 2: Exploratory Data Analysis and Statistics
- Perform exploratory data analysis (EDA) to identify trends and relationships  
- Apply statistical techniques to summarise and interpret key features  
- Visualise distributions and correlations to support hypothesis testing  

### Phase 3: Modelling and Evaluation
- Build at least one predictive model using machine learning techniques  
- Evaluate model performance using appropriate metrics  
- Compare results with baseline approaches and discuss limitations  

### Phase 4: Dashboard Development
- Design and implement an interactive Streamlit dashboard  
- Integrate visualisations, filters, and narrative explanations  
- Ensure accessibility, clarity, and usability for the target audience  

### Phase 5: Review, Reflection, and Future Planning
- Validate project hypotheses based on analytical findings  
- Reflect on challenges, limitations, and ethical considerations  
- Outline future improvements, maintenance, and potential extensions  

This structured plan ensures the project is **maintainable, extensible, and aligned with real-world analytics workflows**, clearly demonstrating Learning Outcome 10 (LO10).
### Streamlit App – Summary

The Streamlit application provides an interactive exploratory interface to analyse the drivers of house sale prices, with dynamic filtering by build year, living area, overall quality, and neighbourhood.
Visualisations demonstrate that property size and build quality are the strongest drivers of sale price, showing clear positive relationships between living area, overall quality, and price levels.
Correlation-based driver analysis highlights that size-related features dominate price variation, while location and age-related variables contribute additional but secondary explanatory power.
An AI-assisted insight summary is included to support data storytelling, clearly labelled as correlation-based and intended to complement, not replace, statistical model interpretation.

## Reflection & Future Development

### Key Learnings
- Early establishment of documentation structures (e.g. problem logs) improves collaboration and reduces rework.
- Summarising EDA findings in plain language improves accessibility for mixed audiences.
- Iterative refinement of the README clarified project scope and decision-making rationale.

### Limitations
- Model performance is constrained by the size and scope of the available dataset.
- Predictions are sensitive to temporal market changes and feature availability.
- Results should be interpreted as indicative trends rather than precise valuations.

### Future Development
- Incorporate additional external datasets (e.g. economic indicators, interest rates).
- Explore more advanced models and hyperparameter tuning.
- Extend the dashboard with scenario-based forecasting and user-driven inputs.
  ## 📊 Power BI Dashboard

The dashboard below provides a high-level overview of key factors influencing house prices.

It combines:
- The relationship between living area and sale price
- The impact of overall build quality on price
- Price trends across construction periods
- Distribution of houses by build quality

![Power BI Dashboard](docs/dashboard.png)


## Exploratory Data Analysis Summary 

In Notebook 01, the dataset was explored using descriptive statistics and visual analysis to understand the distribution, spread, and relationships of key housing features. The analysis focused on sale price, living space, build quality, location indicators, and age-related variables. Summary statistics and distribution plots highlighted strong right-skewness in sale prices, wide variation in property size and quality, and meaningful differences linked to location and construction period. Relationship analysis showed that living area, overall quality, and neighbourhood factors are the most influential drivers of sale price, while property age contributes additional context but does not act as a standalone predictor. These findings provide a statistically grounded basis for feature selection, hypothesis testing, and predictive modelling in subsequent notebooks.

At the close of EDA, the following hypotheses have been validated as true:
1. **Property size and quality features** (e.g. living area, number of rooms, overall quality) have a significant positive impact on house sale prices.  
2. **Location-related features** contribute substantially to price variation across properties.  
3. **Newer properties** or properties with recent renovations tend to achieve higher sale prices than older properties.


### Feature Engineering
In Notebook 2, light feature engineering is completed.
1. Target variable has a strong right skew. Requirement is to apply a log transformation to improve linear model performance by reducing influence of extreme high-price properties.
2. Engineer HouseAge, RemodAge and TotalArea
3. One-hot encode Neighbourhood feature with categoricals


## Predictive Modelling
A supervised regression approach was used to predict residential property sale prices based on structural, quality, and location-related features.
Prior to modelling, the dataset was cleaned and prepared through feature selection, handling of missing values, and encoding of categorical variables. Sale price was log-transformed to reduce skewness and stabilise variance, improving model performance and interpretability.
Several linear models were evaluated, with Ridge Regression selected as the final model due to its ability to manage multicollinearity between correlated housing features such as living area, quality, and neighbourhood indicators. Regularisation strength was tuned using cross-validation to balance bias and variance.
Model performance was assessed using k-fold cross-validation to ensure results were robust and not dependent on a single train–test split.


## Model Performance and Results
The final Ridge Regression model demonstrates strong and stable predictive performance:

1. R² ≈ 0.87, indicating that the model explains approximately 87% of the variation in sale prices
2. Consistent RMSE across folds, showing low variability in prediction error
3. Low standard deviation of cross-validated scores, suggesting good generalisation across the dataset

Cross-validation results confirm that the model performs reliably across different subsets of the data, rather than being driven by a small number of high- or low-priced properties.
Feature importance analysis shows that living area, overall quality, and location-related features are the strongest contributors to predicted sale price, aligning closely with insights identified during exploratory analysis.

## Conclusion
Overall, the prediction model provides a robust and interpretable baseline for house price estimation. The strong cross-validated performance confirms that core structural and quality features are highly effective predictors of sale price, supporting the validity of earlier exploratory findings and meeting the project’s predictive modelling objectives.


## Hypotheses Conclusions

**Hypothesis 1: Property size and quality features have a significant positive impact on house sale prices.**  
**Supported (strongly).**  
The Ridge Regression results show that overall build quality and living area are the most influential predictors of sale price, with the largest positive coefficients in the model. Cross-validation confirms that these effects are stable across data splits, indicating that size and quality consistently drive price variation. This strongly supports the hypothesis that larger, higher-quality properties achieve higher sale prices.

**Hypothesis 2: Location-related features contribute substantially to price variation across properties.**  
**Partially supported.**  
Neighbourhood effects are clearly present in the model, with several location dummy variables showing consistent positive or negative coefficients. However, their individual influence is smaller than that of size and quality features. Cross-validation confirms that these location effects are stable, suggesting genuine spatial influence, but the results indicate that location acts as a moderating factor rather than a primary driver of price.

**Hypothesis 3: Newer properties or properties with recent renovations tend to achieve higher sale prices than older properties.**  
**Supported (moderately).**  
Year built and year of last renovation both show positive relationships with sale price, indicating that newer and more recently renovated properties tend to sell for more. These effects are consistent but smaller in magnitude than size and quality. This suggests that age-related features contribute to price variation, but do not dominate once core property characteristics are taken into account.

**Hypothesis 4: Machine learning models can predict house prices with greater accuracy than simple baseline statistical methods when trained on cleaned and engineered features.**  
**Supported within scope.**  
The Ridge Regression model achieves strong predictive performance (cross-validated R² ≈ 0.87) with low variation across folds, indicating robust generalisation. While a direct baseline model comparison was not implemented, the stability and explanatory power of the regularised model demonstrate that machine learning techniques applied to cleaned and engineered features can provide accurate and reliable price predictions beyond simple descriptive or unregularised approaches.


## Limitations
- The model is trained on historical sales data from a single housing market, which may limit its generalisability to other regions or time periods.
- While Ridge Regression manages multicollinearity effectively, it assumes linear relationships and may not fully capture more complex interactions between features.
- Sale price was modelled at the property level only; broader economic factors such as interest rates or market cycles were not included.
- Outliers were removed to improve model stability, which may reduce accuracy for extreme high-value properties.

- Publish the project.
- Add presentation.

## Data
- https://www.kaggle.com/datasets/chandramoulinaidu/house-price-prediction-cleaned-dataset

## Collaborators

## Future Developments
- Explore non-linear models (e.g. Random Forest or Gradient Boosting) to capture more complex feature interactions.
- Incorporate temporal or economic variables to account for market trends and external influences on pricing.
- Extend the approach to other geographic regions to test model transferability.
- Use spatial features or neighbourhood-level aggregation to further improve location sensitivity.
- Compare model performance with and without outlier treatment to assess impact on high-end price predictions.
This project was developed collaboratively during a time-boxed hackathon.  
Each contributor owned clearly defined responsibilities to ensure accountability, clarity, and full learning-outcome coverage.

### Team Members & Contributions

| Name | Role | Primary Contributions | LinkedIn |
|-----|------|----------------------|----------|
| **Thomas Overment (Person A)** | Project Lead | Project framing, business case, README structure, ethics & governance, learning-outcome mapping, coordination | [LinkedIn](https://www.linkedin.com/in/thomas-overment-12a504304/) |
| **Hellen (Person B)** | Data & Modelling Engineer | Data cleaning, exploratory data analysis, statistical analysis, feature engineering, model development and evaluation | [LinkedIn](#) |
| **Valleriia (Person C)** | Dashboard & UX Engineer | Streamlit application, interactive visualisations, UX design, accessibility, narrative flow | [LinkedIn](#) |

## Credits
- https://deevid.ai/
- kdenlive
- ChatGPT (project management support)
- VS Code Copilot (Code writing and code error support)
- SciKit learn official documentation (model development support)

- deevid.ai
- gimp
- kdenlive
- Vertex ai
- Chat GPT
