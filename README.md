# 📉 Predição de Churn de Clientes

Projeto de **Machine Learning** para previsão de **Customer Churn**, com foco na identificação antecipada de clientes com maior probabilidade de cancelamento. O projeto contempla todo o ciclo de Ciência de Dados, desde a análise exploratória até a interpretação do modelo final, utilizando boas práticas de pré-processamento, modelagem e avaliação.

---

## 📌 Objetivo

O churn representa a perda de clientes e pode gerar impactos significativos na receita de uma empresa. O objetivo deste projeto é desenvolver um modelo capaz de identificar clientes com maior risco de cancelamento, permitindo que ações de retenção sejam realizadas de forma proativa.

---

## 📂 Dataset

O conjunto de dados contém informações cadastrais e comportamentais dos clientes, incluindo características demográficas, serviços contratados e informações financeiras.

**Variável alvo**

* Churn (Cliente cancelou ou não o serviço)

---

### 🛠️ Tecnologias Utilizadas

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-Learn
* ⚡ XGBoost 
* 📓 Jupyter Notebook

---

## 🔍 Etapas do Projeto

### 📊 1. Análise Exploratória (EDA)

* Análise das distribuições das variáveis
* Identificação de padrões relacionados ao churn
* Visualização de correlações
* Análise das principais características dos clientes

---

### 🧹 2. Pré-processamento

* Tratamento de valores ausentes
* Encoding de variáveis categóricas
* Escalonamento dos atributos
* Construção de Pipeline utilizando Scikit-Learn

---

### 🤖 3. Modelagem

Foram avaliados diferentes modelos de classificação, comparando seu desempenho através de diversas métricas.

Entre as etapas realizadas:

* Separação Treino/Teste
* Pipeline completo
* Validação cruzada
* Comparação entre modelos
* Ajuste de threshold
* Seleção do modelo final

---

### 📈 4. Avaliação

O desempenho foi analisado utilizando métricas como:

* ROC-AUC
* Precision
* Recall
* F1-Score
* Matriz de Confusão

Além das métricas tradicionais, também foram analisados:

* Distribuição das probabilidades previstas
* Curva de calibração
* Análise de erros
* Interpretação do modelo

---

## 💡 Principais Insights

* Clientes com contratos mensais apresentaram maior propensão ao churn.
* O ajuste do threshold permitiu priorizar a identificação de clientes em risco, aumentando o recall do modelo.
* A interpretação dos coeficientes possibilitou compreender os fatores mais associados ao cancelamento.
* O modelo mostrou potencial para apoiar estratégias de retenção de clientes.

---

## 📊 Estrutura do Projeto

```text
📦 Customer-Churn
│
├── 📓 Projeto - Churn.ipynb
└── 📁 images/ (opcional)
```

---

## 🚀 Possíveis Aplicações

* Campanhas de retenção
* CRM Inteligente
* Segmentação de clientes
* Priorização de contatos comerciais
* Apoio à tomada de decisão

---

## 📚 Conceitos Aplicados

* Machine Learning
* Classificação Supervisionada
* Feature Engineering
* Data Visualization
* Model Evaluation
* Threshold Tuning
* Model Interpretation
* Business Analytics

---

## 🎯 Resultados

O modelo desenvolvido demonstrou boa capacidade de discriminação entre clientes com maior e menor probabilidade de churn. A escolha de um threshold inferior ao padrão permitiu aumentar a sensibilidade do modelo, tornando-o mais adequado para cenários onde perder um cliente é mais custoso do que realizar contatos preventivos.

Os resultados reforçam a importância de combinar métricas quantitativas com interpretação do modelo e conhecimento do problema de negócio para gerar soluções mais úteis e acionáveis.
