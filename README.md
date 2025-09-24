# Used Car Pricing Analysis 🚗📊
Projeto feito em parceria com: @Arthurmc95

## Descrição do Projeto
Análise estatística completa de preços de carros usados utilizando R. 
O projeto explora distribuições de probabilidade, correlações e fatores que influenciam o preço de veículos.

## 📁 Estrutura do Repositório

used-car-pricing-analysis/
│
├── data/ # Datasets
│ └── raw/ # Dados brutos
│ └── dataset_sem_owner.csv
│
├── scripts/ # Códigos R organizados
│ ├── 01_data_cleaning.R
│ ├── 02_descriptive_analysis.R
│ ├── 03_statistical_tests.R
│ └── 04_visualizations.R
│
├── analysis/ # Análises completas
│ └── main_analysis.R
│
└── outputs/ # Resultados (gerados automaticamente)
├── figures/
└── tables/
text


## 🚀 Como Executar o Projeto

### Pré-requisitos
```r
# Instalar pacotes necessários
install.packages(c("fitdistrplus", "readr", "dplyr", "knitr"))

Execução em Ordem
r

# 1. Limpeza de dados
source("scripts/01_data_cleaning.R")

# 2. Análise descritiva
source("scripts/02_descriptive_analysis.R")

# 3. Testes estatísticos
source("scripts/03_statistical_tests.R")

# 4. Visualizações
source("scripts/04_visualizations.R")

📊 Principais Resultados

    Correlação Preço Atual vs Venda: 0.87

    Distribuição mais adequada: Gamma

    Fator mais influente: Preço atual do veículo

    Transmissão mais valorizada: Automática

🔍 Métodos Estatísticos Utilizados

    Ajuste de distribuições (Normal e Gamma)

    Análise de correlação

    Visualização de dados

👨‍💻 Autor

Eduardo Miguel Ribeiro Cordeiro - edumiguelcordeiro@gmail.com

📄 Licença

Este projeto é para fins educacionais.
