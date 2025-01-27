# Strategic-Aid-Allocation-A-Data-Driven-Approach-to-Maximize-Impact

## Project Overview

This project aims to optimize the allocation of $10 million in humanitarian aid by identifying the most vulnerable countries through advanced data analytics. Utilizing clustering algorithms, exploratory data analysis (EDA), and predictive modeling, we provide actionable insights to enhance poverty alleviation and community development efforts.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
  - [1. Exploratory Data Analysis (EDA)](#1-exploratory-data-analysis-eda)
  - [2. Hypothesis Testing](#2-hypothesis-testing)
  - [3. Feature Engineering](#3-feature-engineering)
  - [4. Clustering and Modeling](#4-clustering-and-modeling)
  - [5. Deployment](#5-deployment)
- [Key Insights and Recommendations](#key-insights-and-recommendations)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)
- [Acknowledgments](#acknowledgments)

## Dataset Description

The analysis is based on a dataset encompassing the following key features for various countries:

- **Country**: Name of the country.
- **Child Mortality**: Deaths of children under 5 years per 1,000 live births.
- **Exports**: Exports as a percentage of GDP.
- **Health**: Health spending as a percentage of GDP.
- **Imports**: Imports as a percentage of GDP.
- **Income**: Net income per person.
- **Inflation**: Annual inflation rate.
- **Life Expectancy**: Average number of years a newborn is expected to live.
- **Fertility Rate**: Average number of children born per woman.
- **GDP per Capita**: Gross Domestic Product per person.

## Methodology

### 1. Exploratory Data Analysis (EDA)

- **Univariate Analysis**: Assessed individual feature distributions to understand data characteristics and identify anomalies.
- **Bivariate Analysis**: Explored relationships between pairs of variables to uncover significant correlations.
- **Outlier Detection and Treatment**: Applied techniques such as Winsorization to manage outliers and ensure data robustness.

### 2. Hypothesis Testing

- **Hypothesis 1**: Investigated whether increased health spending correlates with higher life expectancy.
- **Hypothesis 2**: Examined the association between higher income levels and reduced child mortality rates.

### 3. Feature Engineering

- **Import-Export Ratio**: Created to assess economic reliance.
- **Log Transformation of GDP**: Applied to normalize GDP per capita data.
- **Regional Encoding**: Grouped countries into regions (e.g., South Asia, Africa) to enhance clustering accuracy.

### 4. Clustering and Modeling

- **Clustering Techniques**: Employed K-Means, Hierarchical Clustering, and DBSCAN to group countries based on socio-economic profiles.
- **Dimensionality Reduction**: Utilized Principal Component Analysis (PCA) for effective data visualization and interpretation.

### 5. Deployment

- **Model Deployment**: Exported the K-Means model using Pickle for seamless integration into interactive dashboards.
- **Interactive Dashboard**: Developed using Python and hosted on Google Colab to visualize country clusters, correlations, and key metrics.

## Key Insights and Recommendations

1. **Invest in Healthcare**: Allocate funds to immunization programs and maternal healthcare to reduce child mortality rates.
2. **Strengthen Local Health Systems**: Partner with local organizations to supply medical resources and train healthcare workers.
3. **Address Economic Disparities**: Invest in education and vocational training to elevate income levels and alleviate poverty.
4. **Promote Food Security**: Support sustainable agriculture and nutritional education to combat malnutrition.
5. **Implement Long-Term Development Projects**: Focus on initiatives such as clean water access, renewable energy, and education to tackle the root causes of poverty.

## Getting Started

### Social links:
1. Medium Blog post- https://medium.com/@parthpatel5340/strategic-aid-allocation-a-data-driven-approach-to-maximize-impact-c319f6e3b860
2. Tableau dashboard- https://public.tableau.com/views/StrategicAidAllocationDashboard/Dasboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
3. Google Collab link- https://colab.research.google.com/drive/1kkM-f--hpP7kAOtM_cCIZhwID1CuFz1W?usp=sharing
