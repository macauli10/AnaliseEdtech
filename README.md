# 📊 Análise de Leads - EdTech (Power BI + Python)

Este projeto simula a atuação de um **Analista de Dados** em uma empresa do setor de EdTech, com foco na análise da **jornada de leads** e performance da equipe de vendas, visando otimizar a conversão de novos alunos.

---

## ⚙️ Ferramentas Utilizadas

- **Python** (VSCode) - para limpeza, transformação e análise exploratória dos dados
- **Pandas / NumPy** - para manipulação de dados
- **Power BI** - para visualização dos dados em painéis interativos
- **Jupyter Notebook** (opcional) - para testes rápidos e validação de hipóteses

---

## 🔄 Processo de ETL

### 1. Extração
- Dados fornecidos em múltiplas tabelas `.csv` representando diferentes etapas do funil de aquisição.

### 2. Transformação (com Python)
- Remoção de valores nulos e inconsistentes
- Substituição de outliers por médias ou exclusão quando necessário
- Tradução e padronização de variáveis para facilitar entendimento
- Criação de colunas auxiliares para facilitar a análise (como tempo médio assistido, taxa de conversão por origem etc.)

### 3. Carga
- Dados limpos e estruturados foram importados para o Power BI para visualização.

---

## 📌 Objetivo do Projeto

Analisar as etapas do funil de aquisição de leads:
- **Lead ➝ Awareness ➝ Consideration ➝ Conversion**

E responder perguntas como:
- Onde os leads estão desistindo?
- Qual canal de origem gera mais conversão?
- Quais características estão associadas a maior engajamento?

---

## 📈 Principais Insights

- De **358 potenciais clientes**, cerca de **17% foram convertidos**
- **Social Media** foi o canal com maior volume de leads
- **55% dos leads são do gênero feminino**
- Leads vindos de **Website** assistem a maior porcentagem das apresentações
- O **principal motivo de não conversão** é **"Não pode pagar"**

---

## 📊 Visualizações no Power BI

O dashboard mostra:
- Taxas de conversão por origem e estágio
- Perfil demográfico dos leads
- Principais motivos de desinteresse

> O painel foi exportado em PDF e está disponível na pasta `/dashboard/`.

---


