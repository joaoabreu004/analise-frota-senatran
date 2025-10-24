# Projeto: Análise Preditiva e Segmentação da Frota Brasileira de Veículos 🚗


### 🎯 Visão Geral do Projeto
Este projeto de Data Science realiza uma análise abrangente da frota de veículos do Brasil, utilizando dados públicos do SENATRAN. O objetivo é aplicar as três principais técnicas de Machine Learning — Regressão, Classificação e Clusterização — para extrair insights valiosos, prever tendências futuras e segmentar o perfil de motorização dos municípios brasileiros.

### 🛠️ Tecnologias e Ferramentas Utilizadas 

| Categoria | Ferramenta | Uso no Projeto |
| :--- | :--- | :--- |
| Linguagem | 🐍 Python | Programação principal, ETL e Modelagem de Machine Learning. |
| ETL/BD | 💾 SQL | Carregamento, transformação e consultas complexas dos dados. |
| Visualização | 📈 Pandas/Matplotlib/Seaborn | Análise Exploratória de Dados (EDA). |
| Dashboard | 🗺️ Looker Studio (ou Tableau/PowerBI) | Criação do painel interativo de resultados. |
| Controle | 🐙 GitHub | Versionamento de código e colaboração. |

### 📂 Estrutura do Repositório

```bash
analise-frota-senatran/
├── data/                    # Dados brutos (planilhas do gov.br)
├── notebooks/               # Jupyter Notebooks com o código do projeto
│   ├── 1_limpeza_e_etl.ipynb
│   ├── 2_analise_exploratoria.ipynb
│   ├── 3_modelagem_ml.ipynb  # Contém Regressão, Classificação e Clusterização
├── sql/                     # Scripts SQL de criação de tabelas e consultas de agregação
├── src/                     # Módulos Python auxiliares (funções de limpeza, etc.)
├── results/                 # Exportações finais (ex: CSV com as colunas de Cluster e Previsão)
├── README.md                # Este arquivo
├── .gitignore               # Ignora arquivos grandes, senhas, e ambientes virtuais
└── requirements.txt         # Dependências do Python
```

### 🤝 Contato

Feito por João Vitor de Abreu Sousa.

📧 Contato: jvabreusousa12@

