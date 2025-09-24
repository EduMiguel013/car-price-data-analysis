# Used Car Pricing Analysis 🚗📊

## Descrição do Projeto
Análise estatística completa de preços de carros usados utilizando R. 
O projeto explora distribuições de probabilidade, correlações e fatores que influenciam o preço de veículos.

## 📁 Estrutura do Repositório
text

used-car-pricing-analysis/
│
├── data/                 # Datasets
│   └── raw/             # Raw data
│       └── dataset_sem_owner.csv
│
├── scripts/             # Organized R scripts
│   ├── 01_data_cleaning.R
│   ├── 02_descriptive_analysis.R
│   ├── 03_statistical_tests.R
│   └── 04_visualizations.R
│
├── analysis/            # Complete analyses
│   └── main_analysis.R
│
└── outputs/            # Results (automatically generated)
    ├── figures/
    └── tables/

🚀 How to Run the Project
Prerequisites
r

# Install required packages
install.packages(c("fitdistrplus", "readr", "dplyr", "knitr"))

Execution Order
r

# 1. Data cleaning
source("scripts/01_data_cleaning.R")

# 2. Descriptive analysis
source("scripts/02_descriptive_analysis.R")

# 3. Statistical tests
source("scripts/03_statistical_tests.R")

# 4. Visualizations
source("scripts/04_visualizations.R")

📊 Main Results

    Current Price vs Selling Price Correlation: 0.87

    Most Suitable Distribution: Gamma

    Most Influential Factor: Present Price

    Most Valued Transmission: Automatic

🔍 Statistical Methods Used

    Distribution fitting (Normal, Gamma)

    Correlation analysis

    Data visualization

👥 Collaborative Project

This statistical analysis of used car prices was developed in partnership with [https://github.com/arthurmc95].

Team Contributions:

    [Eduardo Miguel]: Statistical modeling, distribution fitting, hypothesis testing

    [Arthur Martins]: Data visualization, correlation analysis, project documentation

👨‍💻 Author

Eduardo Miguel - edumiguelcordeiro@gmail.com
📄 License

This project is for educational purposes.
