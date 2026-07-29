# 📉 Telecom Retention Radar: Predição de Churn de Clientes

Projeto de **Machine Learning** desenvolvido para prever o **churn de clientes** em uma empresa de telecomunicações. O trabalho contempla todas as etapas de um projeto de Ciência de Dados, desde a compreensão do problema de negócio até a interpretação do modelo final, com foco na geração de insights que apoiem estratégias de retenção de clientes.

---

## 🎯 Objetivo

Desenvolver um modelo preditivo capaz de identificar clientes com maior probabilidade de cancelar seus serviços, além de compreender quais características possuem maior influência nesse comportamento.

O projeto busca transformar dados em informações úteis para apoiar a tomada de decisão e direcionar campanhas de retenção de forma mais eficiente.

---

## 📂 Dataset

O conjunto de dados contém informações de clientes de uma empresa de telecomunicações, incluindo:

* Dados demográficos;
* Tipo de contrato;
* Serviços contratados;
* Informações de cobrança;
* Tempo de permanência;
* Valor mensal e valor total pago.

A variável alvo do estudo é:

**Churn**

* **Yes:** cliente cancelou o serviço;
* **No:** cliente permaneceu na empresa.

---

## ⚙️ Tecnologias Utilizadas

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-Learn
* 📓 Jupyter Notebook

---

## 🔬 Metodologia

O projeto foi desenvolvido seguindo um pipeline completo de Ciência de Dados:

### 📊 Análise Exploratória dos Dados (EDA)

* Distribuição das variáveis;
* Análise do desbalanceamento da variável alvo;
* Relação entre atributos e churn;
* Identificação de padrões de comportamento.

### 🧹 Pré-processamento

* Tratamento de valores ausentes;
* Codificação de variáveis categóricas;
* Padronização dos dados;
* Construção de Pipelines com Scikit-Learn.

### 🤖 Modelagem

Foram comparados diferentes algoritmos de classificação utilizando validação cruzada e métricas apropriadas para o problema.

As principais etapas incluíram:

* Separação Treino/Teste;
* Cross Validation;
* Comparação entre modelos;
* Seleção do modelo final;
* Ajuste do threshold de decisão.

### 📈 Avaliação

O desempenho foi analisado utilizando:

* ROC-AUC;
* Precision;
* Recall;
* F1-Score;
* Matriz de Confusão;
* Curva ROC;
* Curva de Calibração;
* Distribuição das probabilidades previstas.

---

## 💡 Principais Resultados

* O modelo apresentou boa capacidade de discriminar clientes com maior risco de churn.
* A utilização de um **threshold de 20%** priorizou a identificação de clientes com maior probabilidade de cancelamento, aumentando o recall do modelo.
* A interpretação dos coeficientes permitiu identificar características fortemente associadas ao churn, como contratos mensais e determinadas configurações dos serviços contratados.
* Os resultados demonstram o potencial do modelo como ferramenta de apoio à decisão para campanhas de retenção.

---

## ⚠️ Limitações

* Possibilidade de **data leakage** em tenure, exigindo cuidados para utilização em ambiente de produção;
* O modelo foi desenvolvido utilizando uma única base de dados de telecomunicações;
* As relações encontradas representam associações estatísticas, não relações de causalidade.

---

## 🚀 Trabalhos Futuros

* Mitigar possíveis fontes de data leakage;
* Incorporar informações temporais sobre o comportamento dos clientes;
* Explorar novas variáveis relacionadas ao histórico de utilização dos serviços;
* Ajustar o threshold considerando diferentes cenários de custo-benefício.

---

## 📁 Estrutura do Repositório

```text
📦 Churn
│
├── 📓 Projeto.ipynb
├── 📄 Telecom_Retencao.pdf
```

---

## 📄 Documentação

O repositório contém:

* **Projeto.ipynb** → Notebook completo contendo todas as etapas do desenvolvimento.
* **Telecom_retencao.pdf** → Relatório/apresentação do projeto com metodologia, resultados e conclusões.

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
