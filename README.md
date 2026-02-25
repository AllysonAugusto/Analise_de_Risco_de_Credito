# 📊 Análise de Risco de Crédito com Machine Learning

Este projeto tem como objetivo realizar a análise de risco de crédito, utilizando algoritmos de Machine Learning para prever se um cliente irá ou não se tornar inadimplente, com base em dados financeiros e pessoais.

---

## Objetivos do Projeto

- Explorar e analisar dados de clientes  
- Prever o risco de inadimplência  
- Aplicar diferentes algoritmos de Machine Learning  
- Avaliar e comparar o desempenho dos modelos  

---

## Conceitos Abordados

- Machine Learning supervisionado e não supervisionado  
- Algoritmos de classificação, regressão e agrupamento  
- Pré-processamento e limpeza de dados  
- Treinamento, validação e teste de modelos  
- Avaliação de modelos com métricas adequadas  

---

## Algoritmos Utilizados

### Classificação

- Pré-processamento de dados  
- Naïve Bayes  
- Árvores de decisão  
- Random Forest  
- Regressão logística  
- Support Vector Machines (SVM)  
- Redes Neurais Artificiais  
- Avaliação com métricas: Accuracy, Precision, Recall e F1-score  

### Regressão

- Regressão linear simples e múltipla  
- Regressão polinomial  
- Árvores de decisão  
- Random Forest  
- Support Vector Regression (SVR)  
- Redes Neurais Artificiais  

### Regras de Associação

- Algoritmo Apriori  
- Algoritmo ECLAT  

### Agrupamento

- K-Means  
- Agrupamento hierárquico  
- DBSCAN  

---

## Tecnologias e Bibliotecas

- **Linguagem:** Python  
- **Bibliotecas:** NumPy, Pandas, Scikit-learn  
- **Ambientes de desenvolvimento:** Google Colab, Jupyter Notebook  

---

# 📊 Estrutura do Projeto

```text
.
├── data/
│   ├── raw/                              # dados brutos originais
│   │   ├── adult.data
│   │   └── adult.test
│   │
│   └── processed/                        # dados tratados e serializados
│       ├── census.pkl
│       ├── credit.pkl
│       └── risco_credito.pkl
│
├── models/                               # modelos treinados finais
│   ├── svm_finalizado.sav
│   ├── rede_neural_finalizado.sav
│   └── arvore_finalizado.sav
│
├── notebooks/
│   └── credit_risk.ipynb                 # pipeline completo: EDA, pré-processamento, treinamento e avaliação
│
├── README.md

  ```

