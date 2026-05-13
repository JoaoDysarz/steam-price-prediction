# steam-price-prediction

Este repositório contém o projeto de Inteligência Artificial e Ciência de Dados desenvolvido pelo **Grupo 05**. O objetivo central é analisar o ecossistema de jogos da plataforma Steam e construir um modelo preditivo capaz de estimar o preço de prateleira de um jogo com base em suas características técnicas e de mercado.

## Equipe (Grupo 05)
* João Vitor Candido
* João Vitor Dysarz
* João Vitor Haas
* Nathan Daniel Breier
* Vitor Hugo Dallanol

---

## Definição do Problema
**Pergunta de Negócio:** *Qual o preço justo de um jogo baseado nas suas características (no lançamento)?*

No mercado de desenvolvimento de software, precificar um produto digital é um desafio. O nosso modelo visa ajudar estúdios independentes e publicadoras a encontrarem o "ponto ótimo" de preço, evitando barreiras de entrada financeiras (preço muito alto) ou desvalorização do produto (preço muito baixo).

**Tipo de Problema de Machine Learning:**
* Regressão Linear (Supervisionado)

---

## 📂 Base de Dados (Dataset)
* **Nome:** Steam Dataset for Recommendation & Prediction
* **Fonte:** [Kaggle](https://www.kaggle.com/datasets/patelris/steam-top-1495-games-dataset)
* **Variável Alvo (Target):** `price_usd` (Preço Base em Dólares)

---

## 🏗️ Estrutura do Repositório
O projeto será dividido em Sprints quinzenais

```text
📦 steam-price-prediction
 ┣ 📂 data                    # Diretório principal de dados
 ┃ ┣ 📂 sprint_01             # Dados brutos e tratados da Sprint 1
 ┃ ┃ ┗ 📜 steam_top_games_2026.csv
 ┃ ┣ 📂 sprint_02             # Dados para feature engineering e modelagem
 ┃ ┣ 📂 sprint_03
 ┃ ┗ 📂 sprint_04
 ┣ 📂 notebooks               # Códigos fonte em Jupyter Notebook
 ┃ ┗ 📜 Projeto_Grupo_05_Sprint_01.ipynb
 ┗ 📜 README.md               # Documentação principal
