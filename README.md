# 📊 Projeto Shapash – Análise de Churn

Projeto desenvolvido para explorar as funcionalidades da biblioteca **Shapash**, utilizando um conjunto de dados de churn de clientes de telecomunicações.

---

## 🎯 Objetivo

Explorar e demonstrar os principais recursos da biblioteca **Shapash**, focada na explicabilidade de modelos de Machine Learning, aplicando-a ao dataset **Telco Customer Churn**.

O projeto inclui:

- Treinamento de modelo preditivo
- Análise de explicabilidade
- Geração de relatório interativo
- Exportação de objeto explicador

---

## 📂 Estrutura do Projeto
📦 projeto-shapash
│
├── 📁 data
│   └── Telco-Customer-Churn.csv
│
├── 📁 utils
│   └── project_info.yml
│
├── report.html
├── shapash.ipynb
└── xpl.pkl


### 📁 `data/`
Contém o dataset:

- **Telco-Customer-Churn.csv** → Base de dados utilizada para treinamento e análise do modelo.

### 📁 `utils/`
- **project_info.yml** → Arquivo com informações e configurações do projeto.

### 📓 `shapash.ipynb`
Notebook principal contendo:

- Importação e tratamento dos dados
- Treinamento do modelo
- Criação do objeto explicador do Shapash
- Geração das visualizações interativas

### 📄 `report.html`
Relatório interativo exportado a partir do Shapash contendo:

- Explicações globais
- Explicações locais
- Análise de importância de variáveis
- Exploração individual de predições

### 📦 `xpl.pkl`
Arquivo serializado contendo o objeto explicador do Shapash, permitindo:

- Reutilização do modelo e explicações
- Deploy posterior
- Recarregamento sem necessidade de reprocessar tudo

---

## 🚀 Tecnologias Utilizadas

- Python 3.x
- Shapash
- Pandas
- Scikit-learn
- Jupyter Notebook

## 🧠 Sobre Shapash

A biblioteca **Shapash** é voltada para explicabilidade de modelos de Machine Learning, permitindo:

- Visualização da importância global de variáveis
- Explicação individual de predições
- Interface web interativa
- Exportação de relatórios

---

## 📌 Resultados Esperados

- Melhor entendimento do comportamento do modelo
- Identificação das variáveis mais relevantes para churn
- Transparência e interpretabilidade nas decisões do modelo
