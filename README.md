# 📊 Projeção do Mercado Imobiliário — Viana do Castelo

<img width="1124" height="736" alt="Captura de ecrã 2026-10-11 135126" src="https://github.com/user-attachments/assets/ab7e9c17-1f7b-46c8-b8b4-060853a68605" />

## 📌 Sobre o Projeto

Análise exploratória e preditiva do preço médio da habitação (€/m²) nos 10 concelhos do distrito de Viana do Castelo, desenvolvida em Power BI. Dados de 2020 a 2026, com previsão até 2028.

## 🛠️ Tecnologias & Metodologias

- **Power BI & DAX:** métricas dinâmicas, inteligência temporal e formatação personalizada.
- **Modelação de Dados:** Star Schema (tabelas de factos + dimensões).
- **Algoritmo Preditivo:** Suavização Exponencial (ETS) com intervalo de confiança de 95% e sazonalidade S=2.
- **Fontes de Dados:** Idealista / INE (2020-2026).

## 💡 Principais Insights

- **Preço médio atual:** 1 010 €/m² (+28,5% face a 2020; +5,6% nos últimos 12 meses).
- **Previsão a 12 meses:** 1 067 €/m².
- **Litoral vs interior:** Viana do Castelo (1 595 €/m²) e Caminha (1 347 €/m²) registam a maior valorização do distrito, enquanto Melgaço (602 €/m²) e Paredes de Coura (695 €/m²) têm os preços mais baixos.

## ⚠️ Limitações

- Os valores do Idealista são preços **pedidos**, não preços de venda.
- Valores nominais, sem ajuste à inflação.
- A previsão prolonga a tendência histórica e não antecipa mudanças em juros, crédito ou legislação.
- Esta análise tem fins informativos e não constitui aconselhamento financeiro.

## ▶️ Como abrir

Descarregar `Imob_Viana_2028.pbix` e abrir no **Power BI Desktop** (Windows).
