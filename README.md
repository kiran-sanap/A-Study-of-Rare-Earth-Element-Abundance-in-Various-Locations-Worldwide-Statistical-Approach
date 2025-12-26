# A-Study-of-Rare-Earth-Element-Abundance-in-Various-Locations-Worldwide-Statistical-Approach
Problem Statement:

Rare Earth Elements (REEs) are critical for clean energy technologies, electronics, and strategic industries. Despite their importance, REE distributions vary significantly across geological settings and rock types. Traditional univariate analysis often fails to capture the complex, multivariate nature of REE geochemistry. This project addresses the need for a robust statistical framework to analyze REE abundance, variation, and relationships across multiple global locations.


Objectives:

a. To study the abundance and distribution of REEs across different geological locations and rock types

b. To identify geochemical patterns among Light and Heavy Rare Earth Elements (LREEs & HREEs)

c. To apply multivariate statistical techniques for classification and interpretation

d. To determine key elements influencing REE enrichment using regularized regression models

e. To assess statistically significant differences between rock groups using ANOVA and high-dimensional tests


Tools & Technologies:

Programming & Analysis: Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy

Statistical Techniques: Descriptive statistics, Skewness & kurtosis analysis, Missing value imputation (Median), Log transformation, Hierarchical & K-Means clustering, Cluster profiling & heatmaps, Elastic Net regression, ANOVA & High-Dimensional Hotelling’s T²


Data Source:

The study uses published geochemical datasets from internationally recognized research sources:

a. Bayan Obo, China – World’s largest REE deposit

b. Belaya Zima, Russia – Multi-phase carbonatite complex

c. Fen Complex, Norway – Carbonatite and hydrothermal alteration system

Primary references include peer-reviewed journal articles on REE-rich carbonatite complexes.


Methodology / Workflow:

a. Data Collection & Understanding: Compiled REE concentration data across multiple rock types and locations

b. Data Preprocessing: Identified missing values and applied median imputation, Assessed non-normality using skewness and kurtosis, Applied log transformation to stabilize variance

c. Exploratory Data Analysis: Summary statistics and distribution analysis, Heatmaps to visualize enrichment and depletion trends

d. Clustering Analysis: Hierarchical and K-Means clustering to group samples and elements, Clear separation observed between LREE-rich and HREE-poor patterns

e. Cluster Profiling: Interpretation of enriched, moderate, and depleted REE clusters

f. Regression Modeling: Applied Elastic Net regression to handle multicollinearity, Identified key predictors controlling La and Ce enrichment

g. Statistical Testing: Used ANOVA and high-dimensional tests to confirm significant group differences where classical ANOVA fails (p > n cases)


Key Insights:

- Carbonatites show strong LREE enrichment, confirming them as primary REE sources

- Fenites and altered rocks display lower and more variable REE concentrations

- La and Ce emerge as the most reliable indicators of REE enrichment

- Mid-REEs (Pr, Nd, Sm, Gd, Dy) play a dominant role in controlling REE patterns

- Weak Eu and HREE influence suggests low-pressure magmatic environments with limited garnet or plagioclase control

- Clustering consistently separates enriched, moderate, and depleted REE populations across regions


Conclusion:

This study demonstrates clear geochemical differentiation of REE systems across global carbonatite complexes. Bayan Obo shows the strongest separation between carbonatites and fenites, confirming a two-stage magmatic–hydrothermal evolution. Belaya Zima exhibits the highest heterogeneity with extreme variability, reflecting complex multi-phase magmatism, while the Fen Complex displays the most coherent magmatic signature with smooth LREE enrichment and strong multivariate model performance.

Across all regions, La and Ce consistently emerge as the most reliable REE indicators, supported by clustering, heatmaps, and Elastic Net regression. REE enrichment is dominated by LREE–MREE control, with weak and inconsistent HREE contributions, indicating low-pressure melting, amphibole involvement, and limited garnet retention. These findings highlight region-specific enrichment mechanisms and reinforce the relevance of REEs in strategic applications such as EV batteries, permanent magnets, clean energy, optics, and advanced materials.


Author: Kiran Sanap
