# 🦟 Projeto Dengue – Big Data 2025.2

## 📌 Objetivo
Este projeto faz parte da disciplina **Tópicos em Big Data** e tem como foco analisar os casos de **Dengue no Brasil (2023–2025)**, aplicando conceitos de limpeza de dados, regressão linear simples e distribuição de frequência em dados reais do SINAN.

---

## 🛠️ Pipeline Realizado

### 1. Limpeza da Base de Dados
- Carregar os arquivos CSV do SINAN (dados brutos de notificações).  
- Implementa funções para:
  - Identificar automaticamente o cabeçalho das tabelas.  
  - Converter valores numéricos para o formato correto.  
- Transformei as datas em variáveis de **Ano** e **Mês**.  
- Resultado: dados padronizados e organizados para análise temporal.

---

### 2. Regressão Linear Simples
- Apliquei regressão linear simples com `numpy.polyfit` para verificar a **tendência da evolução dos casos** entre 2023 e 2025.  
- O gráfico mostra:
  - Pontos reais de cada ano.  
  - Linha de tendência indicando forte crescimento em 2024.  

---

### 3. Distribuição de Frequência
- Calculamos a frequência percentual de casos por **Ano** e por **Mês**.  
- Gráficos gerados:
  - **Distribuição por ano** → 2024 concentra ~68% dos casos.  
  - **Distribuição por mês (2025)** → meses de março e abril apresentaram os maiores índices.  

---

## 📊 Resultados Obtidos
- **Ano de 2024** foi o mais crítico, confirmando registros de epidemia.  
- **Março e abril** são os meses com maior incidência de casos, mostrando sazonalidade.  
- O pipeline (Limpeza → Regressão Linear → Frequência) demonstrou como a análise de Big Data pode ser aplicada para **suporte a decisões em saúde pública**.

---

## 👨‍💻 Autor
Celso Muniz de Carvalho Neto  
Disciplina: Tópicos em Big Data – 2025.2 – UNESA
