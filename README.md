# 📊 Projeção do Mercado Imobiliário — Viana do Castelo
<img width="1104" height="738" alt="Captura de ecrã 2026-10-13 235509" src="https://github.com/user-attachments/assets/e1b2eae5-ff2c-4b7b-bf2b-2759d9f421e4" />

## 📌 Sobre o Projeto

Análise exploratória e preditiva do preço médio da habitação (€/m²) nos 10 concelhos do distrito de Viana do Castelo, desenvolvida em Power BI. Dados de 2020 a 2026, com previsão até 2028.

## 🛠️ Tecnologias & Metodologias

- **Power BI & DAX:** métricas dinâmicas, inteligência temporal e formatação personalizada.
- **Modelação de Dados:** Star Schema (tabelas de factos + dimensões).
- **Algoritmo Preditivo:** Suavização Exponencial (ETS) com intervalo de confiança de 95% e sazonalidade S=2.
- **Fontes de Dados:** Idealista / INE (2020–2026).

## 💡 Principais Insights

- **Preço médio atual:** 1 378 €/m² (+77,6% face a 2020; +18,3% nos últimos 12 meses).
- **Previsão a 12 meses:** 1 470 €/m².
- **Litoral vs interior:** Viana do Castelo (2 275 €/m²) e Caminha (1 974 €/m²) registam a maior valorização do distrito, enquanto Melgaço (693 €/m²) e Paredes de Coura (1 046 €/m²) têm os preços mais baixos.

## ⚠️ Limitações

- Os valores do Idealista são preços **pedidos**, não preços de venda.
- Valores nominais, sem ajuste à inflação.
- A previsão prolonga a tendência histórica e não antecipa mudanças em juros, crédito ou legislação.
- Esta análise tem fins informativos e não constitui aconselhamento financeiro.

## ▶️ Como abrir

Descarregar `Imob_Viana_2028.pbix` e abrir no **Power BI Desktop** (Windows).
