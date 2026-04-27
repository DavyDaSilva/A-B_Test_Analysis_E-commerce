# Análise de A/B Test — Otimização de Conversão em E-commerce

## Visão Geral do Projeto

Este projeto analisa um teste A/B realizado em uma plataforma de e-commerce para determinar se um novo design de página aumenta a taxa de conversão dos usuários.

O objetivo é tomar uma **decisão orientada por dados** sobre substituir ou não a versão atual.

---

## 🎯 Objetivo

* Avaliar se a **nova página aumenta a taxa de conversão**
* Utilizar métodos estatísticos para validar os resultados
* Fornecer uma **recomendação de negócio clara**

---

## Hipóteses

* **H₀ (Hipótese Nula):** A nova página não afeta a taxa de conversão
* **H₁ (Hipótese Alternativa):** A nova página melhora a taxa de conversão

---

## Preparação dos Dados

* Limpeza de valores inconsistentes (ex: string "NaN")
* Padronização dos formatos das colunas
* Remoção de registros inválidos ou ausentes
* Garantia da separação correta entre grupos (controle vs tratamento)

📍 (here a image of data cleaning process or dataframe preview from Step 1)

---

## Análise Exploratória (EDA)

* Comparação das taxas de conversão entre os grupos
* Análise da distribuição de tráfego
* Verificação de balanceamento e possíveis anomalias

📍 (here a image of conversion rate comparison graph from Step 2)

📍 (here a image of distribution or traffic analysis)

---

## Teste Estatístico

* Aplicação do **teste Z para proporções**
* Cálculo de **intervalos de confiança**
* Avaliação da significância estatística

📍(here a image of statistical results or p-value output)

---

## Principais Resultados

* Taxa de Conversão (Controle): X%
* Taxa de Conversão (Tratamento): X%
* Diferença: X%
* P-valor: X

📍(here a image of metrics comparison or summary table)

---

## ✅ Conclusão

* Se p-valor < 0.05 → Rejeitamos H₀
* Se p-valor ≥ 0.05 → Não rejeitamos H₀

**Decisão Final:**

> (Escreva aqui sua conclusão real — ex: “A nova página apresenta melhora estatisticamente significativa e deve ser implementada.”)

---

## 🛠️ Ferramentas e Tecnologias

* Python
* Pandas
* NumPy
* Statsmodels
* Jupyter Notebook

---

## 📌 Próximos Passos (Opcional)

* Implementar regressão logística para análise mais profunda
* Criar um dashboard interativo
* Executar novos experimentos para validação
