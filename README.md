**[EN]**

# New York Airbnb Exploratory Data Analysis
This was a guided project and its goal is to perform an Exploratory Data Analysis (EDA) on a New York City Airbnb dataset. The primary objective is to understand the pricing dynamics, room availability, and geographical distribution of listings across different 
neighborhood groups. The analysis process involves loading the data from a CSV file, cleaning the dataset (handling missing values, removing duplicates, casting data types), and conducting a deep dive into the variables. Key steps include outlier 
detection and removal for price normalization, feature engineering, and creating visualizations using Seaborn and Matplotlib to uncover correlations between location, reviews, and pricing.

# Data
The data source is a file named `datasets.csv`. The raw data represents Airbnb listings with the following key attributes:

**id & host_id**: Unique identifiers for listings and hosts.

**neighbourhood_group & neighbourhood**: Location details.

**latitude & longitude**: Geolocation coordinates.

**room_type**: Classification of the listing (Entire home/apt, Private room, etc.).

**price**: Nightly rental cost.

**minimum_nights & availability_365**: Booking constraints and availability throughout the year.

**number_of_reviews & reviews_per_month**: Popularity metrics.

## Key Engineered Features:
`price_per_bed`: Calculated to understand the cost efficiency per sleeping capacity.

`outlier_removed_price`: A subset of data where prices > $1500 were removed to normalize the distribution for better visualization.

`clean_data`: A dataset processed to remove null values and duplicate entries, ensuring data integrity.

# Personal Contact Details
**Bruno P. Galindo** [brunopgalindo@hotmail.com](mailto:brunopgalindo@hotmail.com) -- Contact for inquiries regarding data.

# Getting Started
For this analysis project, the workflow is scripted in Python. To replicate the analysis:

1) Ensure the `datasets.csv` file is in the working directory.
2) Run the data cleaning scripts to handle nulls and duplicates.
3) Execute the visualization cells to generate the heatmaps, scatterplots, and histograms.

# Requirements
To run this project, you will need a Python 3 environment with the following libraries installed:

**Step 1: Open the Python 3 environment of your choice**

**Step 2: Install the necessary libraries**
```
pip install pandas numpy matplotlib seaborn
```

**Step 3: Load the scripts and run them all**

# Authors
* Bruno P. Galindo - Personal Project - https://www.linkedin.com/in/brunopgalindo/

# Project Motivation
* The intention of this guided project is to study and understand listing analysis and develop critical thinking skills regarding the cleaning and interpretation of real-world accommodation data.
* This is a public dataset structure and the only purpose of it is to be used for study. None of the data is sensitive in any way.
* Inspiration: Analyzing urban rental markets and pricing strategies in high-demand tourist destinations.
---

# **[PT/BR]**

# Análise Exploratória de Dados do Airbnb de Nova York
Este foi um projeto guiado e seu objetivo é realizar uma Análise Exploratória de Dados (EDA) em um conjunto de dados do Airbnb de Nova York. O objetivo principal é entender a dinâmica de preços, a disponibilidade de quartos e a distribuição geográfica dos anúncios
em diferentes grupos de bairros. O processo de análise envolve o carregamento dos dados de um arquivo CSV, limpeza do conjunto de dados (tratamento de valores ausentes, remoção de duplicatas, conversão de tipos de dados) e a condução de um estudo aprofundado das 
variáveis. As principais etapas incluem detecção e remoção de outliers para normalização de preços, engenharia de recursos e criação de visualizações usando Seaborn e Matplotlib para descobrir correlações entre localização, avaliações e preços.

# Dados
A fonte de dados é um arquivo chamado `datasets.csv`. Os dados brutos representam anúncios do Airbnb com os seguintes atributos principais:

**id & host_id**: Identificadores únicos para anúncios e anfitriões.

**neighbourhood_group & neighbourhood**: Detalhes de localização.

**latitude & longitude**: Coordenadas de geolocalização.

**room_type**: Classificação do anúncio (Casa/apto inteiro, Quarto privado, etc.).

**price**: Custo do aluguel por noite.

**minimum_nights & availability_365**: Restrições de reserva e disponibilidade ao longo do ano.

**number_of_reviews & reviews_per_month**: Métricas de popularidade.

## Variáveis Chaves Calculadas:

`price_per_bed`: Calculado para entender a eficiência de custo por capacidade de acomodação.

`outlier_removed_price`: Um subconjunto de dados onde preços > $1500 foram removidos para normalizar a distribuição para melhor visualização.

`clean_data`: Um conjunto de dados processado para remover valores nulos e entradas duplicadas, garantindo a integridade dos dados.

# Dados Pessoais para Contato
* **Bruno P. Galindo** [brunopgalindo@hotmail.com](mailto:brunopgalindo@hotmail.com) -- Contato para perguntas relacionadas aos dados.

# Começando
Para este projeto de análise, o fluxo de trabalho é escrito em Python. Para replicar a análise:
1) Certifique-se de que o arquivo `datasets.csv` esteja no diretório de trabalho.
2) Execute os scripts de limpeza de dados para lidar com nulos e duplicatas.
3) Execute as células de visualização para gerar os mapas de calor, gráficos de dispersão e histogramas.

# Requisitos
Para executar este projeto, você precisará de um ambiente Python 3 com as seguintes bibliotecas instaladas:

**Passo 1: Abra o ambiente Python 3 de sua escolha**

**Passo 2: Instale as bibliotecas necessárias**
```
pip install pandas numpy matplotlib seaborn
```

**Passo 3: Carregue os scripts e execute todos eles**

# Autores
* **Bruno P. Galindo - Projeto Pessoal - https://www.linkedin.com/in/brunopgalindo/**

# Motivação do Projeto
* A intenção deste projeto guiado é estudar e entender a análise de listagens e desenvolver habilidades de pensamento crítico em relação à limpeza e interpretação de dados de acomodação do mundo real.
* Esta é uma estrutura de conjunto de dados pública e o único objetivo é ser usada para estudo. Nenhum dado é sensível de forma alguma.
* Inspiração: Analisar mercados de aluguel urbano e estratégias de preços em destinos turísticos de alta demanda.









































