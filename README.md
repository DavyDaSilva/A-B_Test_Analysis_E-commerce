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

## Métricas Principais

Taxa de Conversão (Controle): X%
Taxa de Conversão (Tratamento): X%
Lift (Diferença): X%
P-valor: X

📍(here a image of comparação de conversão → do Step 4: Análise Exploratória (EDA) onde você calcula a taxa de conversão)

---

## Abordagem Estatística

Teste de hipótese (Z-test para proporções)
Nível de significância: 5%
Intervalo de confiança

📍(here a image of resultado do teste estatístico → do Step 5: Teste Estatístico onde aparece o p-value)

---

## Resultados
Diferença observada entre os grupos: X%
Significância estatística: (Sim/Não)

📍(here a image of resumo das métricas → do Step 6: Resultados onde você mostra controle vs tratamento)

---

## ✅ Conclusão

* Se p-valor < 0.05 → Rejeitamos H₀
* Se p-valor ≥ 0.05 → Não rejeitamos H₀

**Decisão Final:**

> A nova página não apresenta melhora estatisticamente significativa, portanto não deve ser implementada.

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
