# 📊 Análise dos Top Hits do Spotify (2000–2019)

Este projeto apresenta uma análise exploratória dos dados de músicas mais tocadas no Spotify entre os anos de 2000 e 2019, com base no dataset disponível no Kaggle: [Top Hits Spotify from 2000-2019](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019). A análise foi desenvolvida em Python utilizando bibliotecas como `pandas`, `matplotlib` e `seaborn`, e está pronta para ser executada no **Google Colab**.

---

## ✅ Objetivos

* Analisar características gerais das músicas mais populares.
* Identificar os gêneros e artistas mais presentes no Top 50.
* Visualizar a popularidade ao longo do tempo.
* Explorar relações entre atributos musicais (dançabilidade, energia, etc).

---

## 📂 Estrutura do Projeto

```
📁 spotify-top-hits-analysis/
├── spotify_dashboard_upload_manual.ipynb  ← Notebook com a análise
└── README.md                              ← Este arquivo
```

---

## 🚀 Como Executar

1. Acesse o notebook no [Google Colab](https://colab.research.google.com/).
2. Faça o **upload manual** do arquivo `top50.csv` quando solicitado.
   Você pode obter esse arquivo extraindo o `.zip` do Kaggle:
   [https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019)
3. Execute todas as células do notebook.

> **Atenção:** o dataset **não está incluído neste repositório** por conta das diretrizes de uso do Kaggle.

---

## 📈 Visualizações Incluídas

* **Gêneros mais populares** (`countplot`)
* **Distribuição de músicas por ano** (`histograma`)
* **Artistas com mais músicas no Top 50** (`barplot`)
* **Artistas mais populares (média da popularidade)** (`barplot`)
* **Mapa de calor de correlação entre atributos musicais** (`heatmap`)

---

## 🛠 Bibliotecas Utilizadas

* `pandas`
* `matplotlib`
* `seaborn`

---

## 💡 Observações

* O nome das colunas do CSV é padronizado automaticamente para minúsculas e sem espaços, evitando erros comuns como `KeyError`.
* O projeto pode ser facilmente expandido com mais visualizações, como:

  * Dançabilidade por gênero
  * Evolução da energia média ao longo dos anos
  * Correlação entre duração e popularidade
  * Agrupamento por características musicais (clustering)

---

## 👩‍💻 Autora

**Evellyn Carolyne Gomes da Silva**
Projeto desenvolvido como prática em análise de dados com Python no Google Colab.

