<!-- # Project: Data analysis of the movies and tv shows Netflix

This project reads, processes, categorizes, normalizes, groups, and analyzes movies and TV shows from Netflix's streaming service.

## Datasets
The data of this project was downloaded using the [https://www.kaggle.com/datasets/shivamb/netflix-shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) dataset from kaggle.

## Tools
- Python
- Pandas
- NumPy
- SQLite (optional)
- Seaborn / Matplotlib

## Goals
- Demonstrate data cleaning and manipulation in a real project
- Produce views and insights with public data

## How to run
```bash
pip install -r requirements.txt
python src/processamento.py
 -->

# Análise de Dados de Títulos da Netflix 🎬

Este projeto tem como objetivo explorar e visualizar dados da plataforma Netflix. Utilizando Python e bibliotecas como `pandas`, `seaborn` e `matplotlib`, foram obtidos insights relevantes sobre os tipos de conteúdos, classificações etárias, distribuição temporal e durações.

## 📊 Visão Geral da Análise

- **Fonte dos Dados**: Conjunto disponibilizado pelo usuário "shivamb" no Kaggle.
- **Ferramentas Utilizadas**: Pandas, Seaborn, Matplotlib, Scipy, Powerlaw.
- **Total de Títulos Analisados**: Aproximadamente 8.800 entre filmes e séries.

## 📌 Principais Resultados

### 1. Distribuição por Tipo
- Maioria dos títulos são **filmes (69%)**, seguidos por **séries (31%)**.
- Gráfico de barras mostra claramente o predomínio dos filmes.

### 2. Lançamentos por Ano
- Crescimento significativo entre 2016 e 2020, com pico em 2018.
- Queda visível em 2021, possivelmente impactada por fatores externos (ex: pandemia).

### 3. Classificações Etárias
- As classificações **"TV-MA"** e **"TV-14"** dominam o catálogo.
- Algumas entradas incorretas foram detectadas (ex: "66 min", "84 min") e removidas.

### 4. Duração Média dos Filmes
- Duração média: **aproximadamente 100 minutos**.
- Histograma mostra distribuição concentrada entre 80 e 120 minutos.

### 5. Séries e Número de Temporadas
- Séries possuem em média **1,76 temporadas**.
- Gráfico log-log sugere uma distribuição semelhante a uma lei de potência.
- Estimativas com ajuste de Power Law revelam `alpha ≈ 5.17` e `xmin = 8`.

## ⚠️ Valores Faltantes
- Dados ausentes em colunas como `director`, `cast` e `country`.
- Estratégias de imputação ou filtragem são recomendadas dependendo do uso futuro.

## 📈 Conclusão
A análise fornece um panorama eficaz do catálogo da Netflix até o momento da coleta. O pipeline pode ser expandido para prever tendências, classificar conteúdo ou até integrar dados de engajamento de usuários.

---

Desenvolvido por Brenddon Oliveira.

