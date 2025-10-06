# Análise de Preços de Carros Usados 🚗📊

## 📋 Descrição do Projeto
Análise estatística completa de preços de carros usados utilizando R. 
Este projeto explora distribuições de probabilidade, correlações e os principais fatores que influenciam o valor de veículos no mercado de seminovos.

## 🏗️ Estrutura do Repositório
```bash
analise-precos-carros/
│
├── 📁 dados/
│   ├── 📁 brutos/
│   │   └── dataset_sem_owner.csv
│   └── 📁 processados/
│       └── dados_limpos.csv
│
├── 📁 scripts/
│   ├── 📄 01_limpeza_dados.R
│   ├── 📄 02_analise_descritiva.R
│   ├── 📄 03_testes_estatisticos.R
│   └── 📄 04_visualizacoes.R
│
├── 📁 analises/
│   └── 📄 analise_completa.R
│
├── 📁 resultados/
│   ├── 📁 graficos/
│   └── 📁 tabelas/
│
└── 📄 README.md
```
## 🚀 Como Executar o Projeto

### 📦 Pré-requisitos
```r
# Instalar pacotes necessários
install.packages(c("fitdistrplus", "ggplot2", "dplyr", "knitr", "readr"))
```
## 🔄 Ordem de Execução
``` 
# 1. Limpeza e preparação dos dados
source("scripts/01_limpeza_dados.R")

# 2. Análise descritiva e exploratória
source("scripts/02_analise_descritiva.R")

# 3. Testes estatísticos e modelos
source("scripts/03_testes_estatisticos.R")

# 4. Geração de visualizações
source("scripts/04_visualizacoes.R")
```
## 📊 Principais Resultados

### 🔍 Descobertas Significativas

    📈 Correlação Preço Atual vs Preço de Venda: 0.87 (Forte correlação positiva)

    📊 Distribuição Mais Ajustada: Gamma (para variáveis de preço)

    🎯 Fator Mais Influente: Ano do veículo

    ⚙️ Transmissão Mais Valorizada: Automática

    ⛽ Combustível com Maior Valorização: Diesel

### 📉 Insights do Mercado

    Veículos a diesel mantêm melhor valorização

    Carros automáticos possuem premium de preço

    Quilometragem impacta significativamente o preço

    Concessionárias tendem a vender por valores mais altos

## 🧪 Métodos Estatísticos Utilizados

### 📐 Análise Descritiva

    Estatísticas resumo (média, mediana, desvio padrão)

    Tabelas de frequência e percentuais

    Análise de distribuições

### 📊 Testes Estatísticos

    Ajuste de distribuições (Normal, Gamma)

    Testes de hipótese (ANOVA, teste t)

    Análise de correlação (Pearson)

### 🎨 Visualização de Dados

    Histogramas com curvas de densidade

    Boxplots por categoria

    Gráficos de dispersão

## 👥 Desenvolvido em Parceria

### 🤝 Projeto Colaborativo
Esta análise estatística foi desenvolvida em parceria com [[@arthurmc95](https://github.com/arthurmc95)].

### 🎯 Divisão de Responsabilidades:

    [Eduardo Cordeiro]: Modelagem estatística, ajuste de distribuições, testes de hipótese

    [Arthur Martins]: Visualização de dados, análise de correlação, documentação

## 👨‍💻 Autor

Eduardo Miguel Ribeiro Cordeiro

📧 edumiguelcordeiro@gmail.com

🔗 https://github.com/eduardomrcordeiro

## 📄 Licença

Este projeto é destinado para fins educacionais e acadêmicos.
