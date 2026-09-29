# 🎬 Netflix Analytics Dashboard | Power BI

> Dashboard interativo desenvolvido no Power BI para exploração e análise estratégica do catálogo global da Netflix.

---

## 📌 Preview do Dashboard

![Dashboard Overview](Images/dashboard-overview.png)

---

## 📊 Sobre o Projeto

Este projeto consiste na criação de um painel analítico para explorar o catálogo da Netflix, identificando a distribuição de produções ao longo dos anos, padrões por país de origem, diversidade de gêneros e perfil de classificação indicativa. 

O objetivo principal foi transformar dados brutos em visualizações interativas e intuitivas que facilitem a extração de *insights* estratégicos.

---

## 💡 Principais Insights da Análise

- **Proporção do Catálogo:** Predomínio de **Filmes (~70%)** em relação a **Séries (~30%)**.
- **Crescimento Histórico:** Pico de adições de títulos no catálogo entre **2017 e 2020**.
- **Liderança de Produção:** **Estados Unidos** e **Índia** ocupam os primeiros lugares em volume absoluto de conteúdos.
- **Gêneros Mais Frequentes:** Dramas, Comédias e Documentários lideram o ranking de categorias.

---

## 🎯 Objetivos de Negócio

- Mapear a evolução temporal dos lançamentos e adições à plataforma.
- Comparar volume e métricas entre **Filmes** vs. **Séries**.
- Analisar a distribuição geográfica das produções por país.
- Entender a representatividade de cada faixa etária / classificação indicativa (ex: TV-MA, TV-14, PG-13).
- Permitir a filtragem dinâmica por gênero, ano, tipo de mídia e país.

---

## 🛠️ Tecnologias & Conceitos Utilizados

- **Power BI Desktop:** Modelagem de dados, tratamento visual e construção do layout.
- **Power Query (M):** Limpeza, eliminação de duplicadas, tratamento de valores nulos e estruturação de colunas.
- **DAX (Data Analysis Expressions):** Construção de métricas personalizadas e medidas dinâmicas.
- **Data Storytelling & UX:** Design limpo, focado na usabilidade e na facilidade de leitura dos KPIs.

---

## 📐 Estrutura do Repositório

```text
├── Dashboard/
│   └── Netflix_Analytics_Dashboard.pbix   # Arquivo do Power BI
├── Data/
│   └── netflix_titles.csv                 # Base de dados original
├── Images/
│   └── dashboard-overview.png             # Print/Preview do painel
└── README.md                              # Documentação do projeto
