# Projeto ETL - Santander Dev Week 2023

Este projeto foi desenvolvido como parte do desafio da **Santander Dev Week 2023**, com foco em **Ciência de Dados e Python**.  
O objetivo é demonstrar o fluxo **ETL (Extração, Transformação e Carregamento)**, utilizando dados fictícios ou arquivos CSV e aplicando IA Generativa para criar mensagens personalizadas de marketing.

---

## 🚀 Objetivo
Simular um cientista de dados no Santander que precisa envolver clientes de maneira personalizada, criando mensagens sobre a importância dos investimentos.

---

## 📂 Estrutura do Projeto

etl-sdw2023/
│
├── data/
│   └── SDW2023.csv          # arquivo com IDs ou dados fictícios
│
├── src/
│   └── etl.py               # script principal em Python
│
├── notebooks/
│   └── etl.ipynb            # versão em Jupyter Notebook
│
└── README.md                # explicação do projeto

## ⚙️ Tecnologias Utilizadas
- **Python 3.10+**
- **Pandas** (manipulação de dados)
- **OpenAI API** (geração de mensagens com IA)
- **Requests** (requisições HTTP, caso queira simular API)
- **JSON/CSV** (armazenamento local)

---

## 🔄 Fluxo ETL

1. **Extract (Extração)**  
   - Leitura de dados fictícios diretamente no código **OU** via arquivo CSV.

2. **Transform (Transformação)**  
   - Geração de mensagens personalizadas usando IA (OpenAI GPT-4).

3. **Load (Carregamento)**  
   - Salvamento das mensagens em arquivos locais (`usuarios_com_news.json` ou `usuarios_com_news.csv`).

---

## ▶️ Como Executar

### 1. Clone o repositório
```bash
git clone https://github.com/seuusuario/etl-sdw2023.git
cd etl-sdw2023
