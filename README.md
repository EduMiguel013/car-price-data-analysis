Análise Estatística de Carros Usados

Este projeto realiza uma análise estatística completa de preços de carros usados utilizando a linguagem R. Desenvolvido em parceria com Arthur Martins, o estudo explora distribuições de probabilidade, correlações e os principais fatores que influenciam o preço de veículos no mercado de usados.
📊 Sobre o Projeto

O projeto utiliza técnicas de análise estatística e aprendizado de máquina para investigar:

    Distribuições de probabilidade dos preços de venda

    Correlações entre variáveis do dataset

    Fatores que mais impactam o valor dos veículos

    Análise descritiva completa dos dados

🛠 Tecnologias Utilizadas

    R - Linguagem de programação estatística

    readr - Leitura de dados

    dplyr - Manipulação de dados

    knitr - Relatórios dinâmicos

    fitdistrplus - Ajuste de distribuições de probabilidade

📁 Estrutura do Projeto
text

Carros_usados_Teoria_do_Apren_Estatístico.ipynb
├── Carregamento e exploração inicial dos dados
├── Análise descritiva e estatísticas sumárias
├── Transformação e preparação dos dados
├── Cálculo de medidas de tendência central
├── Análise de frequências relativas
├── Ajuste de distribuições de probabilidade
└── Visualizações e interpretações estatísticas

📈 Principais Análises
Dados Exploratórios

    Estatísticas descritivas completas

    Análise de valores missing e outliers

    Distribuição das variáveis categóricas e numéricas

Análise de Preços

    Média, mediana e moda dos preços de venda

    Distribuição gamma para Selling_Price e Present_Price

    Distribuição normal para Kms_Driven

Fatores Influentes

    Correlação entre preço atual e preço de venda

    Impacto do tipo de combustível, ano e transmissão

    Análise de quilometragem vs. valor do veículo

🚀 Como Executar

    Clone o repositório:

bash

git clone https://github.com/seu-usuario/analise-carros-usados.git

    Abra o arquivo Carros_usados_Teoria_do_Apren_Estatístico.ipynb no RStudio

    Instale as dependências necessárias:

r

install.packages(c("readr", "dplyr", "knitr", "fitdistrplus"))

    Execute as células sequencialmente para reproduzir a análise

📋 Dataset

O projeto utiliza o dataset dataset_sem_owner.csv contendo informações sobre carros usados, incluindo:

    Car_Name: Nome do veículo

    Year: Ano de fabricação

    Selling_Price: Preço de venda (em Lakhs de Rúpias Indianas)

    Present_Price: Preço atual de mercado

    Kms_Driven: Quilometragem

    Fuel_Type: Tipo de combustível

    Seller_Type: Tipo de vendedor

    Transmission: Tipo de transmissão

👥 Autores

    Seu Nome - Seu GitHub

    Arthur Martins - GitHub

📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
