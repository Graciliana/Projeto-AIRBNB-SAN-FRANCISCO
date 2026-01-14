

# 🏡 Airbnb Data Analysis — San Francisco

## 📌 Visão Geral

Este projeto tem como objetivo realizar uma **análise exploratória e analítica dos dados de locações do Airbnb** na cidade de **San Francisco, Califórnia (EUA)**, utilizando dados públicos disponibilizados pelo portal **Inside Airbnb**.

O estudo segue uma abordagem estruturada de **ETL (Extract, Transform, Load)**, boas práticas de **governança de dados**, organização modular em notebooks e foco em **qualidade, rastreabilidade e reprodutibilidade** dos dados.

---

## 🎯 Objetivos do Projeto

* Analisar o mercado de locações do Airbnb em San Francisco
* Compreender padrões de preços, tipos de imóveis e localização
* Avaliar a qualidade e estrutura dos dados públicos do Airbnb
* Construir uma base de dados tratada para análises futuras e modelos analíticos
* Aplicar boas práticas de **ETL, versionamento e organização de projetos de dados**

---

## 🌍 Sobre San Francisco

San Francisco é uma das cidades mais importantes dos Estados Unidos, conhecida por seu papel central em inovação, tecnologia e turismo. Localizada na Califórnia, a cidade abriga polos como o **Vale do Silício**, além de pontos turísticos icônicos como a **Golden Gate Bridge**, **Alcatraz** e bairros culturais diversos.

Devido à alta demanda turística e ao custo elevado de moradia, o mercado de locações de curto prazo é altamente relevante, tornando a cidade um excelente estudo de caso para análise de dados do Airbnb.

---

## 📊 Fonte dos Dados

Os dados utilizados neste projeto foram obtidos a partir do portal **Inside Airbnb**, uma iniciativa que disponibiliza dados públicos de locações para fins de pesquisa e transparência.

* Fonte: Inside Airbnb
* Cidade analisada: San Francisco, CA
* Formato: CSV e CSV compactado (`.csv.gz`)
* Dados públicos e confiáveis

---

## 🧪 Metodologia (ETL)

O projeto segue a metodologia **ETL**, separada em notebooks independentes:

### 🔹 Extract (Extração)

* Leitura direta dos arquivos brutos (`raw`)
* Preservação da estrutura original dos dados
* Garantia de rastreabilidade e integridade

### 🔹 Transform (Transformação)

* Tratamento de valores ausentes
* Padronização de tipos de dados
* Limpeza de inconsistências
* Criação de variáveis relevantes

### 🔹 Load (Carga)

* Preparação de datasets prontos para análise
* Estruturação para EDA, visualizações e modelos futuros

---

## 📁 Estrutura do Projeto

```text
airbnb-san-francisco-analysis/
│
├── data/
│   ├── raw/              # Dados brutos (sem alterações)
│   ├── processed/        # Dados tratados
│
├── notebooks/
│   ├── 01_extract.ipynb  # Extração e inspeção inicial dos dados
│   ├── 02_transform.ipynb# Limpeza e transformação dos datasets
│   ├── 03_eda.ipynb      # Análise exploratória dos dados
│
├── images/               # Imagens e gráficos utilizados
│
├── README.md
└── requirements.txt
```

---

## 📚 Datasets Utilizados

* **listings.csv.gz** → Informações gerais dos anúncios
* **calendar.csv.gz** → Disponibilidade e preços por data
* **reviews.csv.gz** → Avaliações dos hóspedes
* **neighbourhoods.csv / geojson** → Dados geográficos dos bairros

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook
* Git & GitHub

---

## 🔄 Controle de Versão

O projeto utiliza o padrão **Conventional Commits**, garantindo clareza e rastreabilidade no versionamento.

Exemplo:

```text
data(extract): add raw data ingestion from Inside Airbnb
data(transform): clean and standardize Airbnb datasets
feat(eda): perform exploratory data analysis
```

---

## 🚀 Próximos Passos

* Análise exploratória avançada (EDA)
* Visualizações geográficas
* Modelagem preditiva de preços
* Criação de pipeline automatizado
* Dashboard interativo (Streamlit)

---

## 👩‍💻 Autora

**Graciliana Kascher**
🔗 [LinkedIn](https://www.linkedin.com/in/gracilianakascher/)
💻 [GitHub](https://github.com/graciliana)

---

## 📌 Observação

Este projeto tem caráter **educacional e analítico**, utilizando dados públicos para fins de estudo em Ciência de Dados e Engenharia de Dados.

---

Se quiser, no próximo passo posso:
✔️ Ajustar o README para **inglês (EN)**
✔️ Adaptar para **vaga específica (BI, Data Scientist, Data Analyst)**
✔️ Criar um **README resumido para recrutadores**
✔️ Padronizar `requirements.txt`

É só me dizer 🚀
