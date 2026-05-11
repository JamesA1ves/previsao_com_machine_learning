# 📊 Previsão de Score de Crédito com Machine Learning

Projeto de análise de dados e Machine Learning desenvolvido em Python para prever o score de crédito de clientes bancários.

O objetivo é utilizar dados históricos de clientes para treinar modelos de classificação capazes de prever se um cliente possui score de crédito:

- Poor
- Standard
- Good

Esse tipo de solução pode ser utilizado por instituições financeiras para auxiliar decisões relacionadas a:

- concessão de crédito
- aprovação de empréstimos
- definição de limites
- análise de risco

---

# 🚀 Tecnologias Utilizadas

- Python
- Pandas
- Scikit-Learn

---

# 📚 Conceitos Aplicados

O projeto aborda diversos conceitos importantes de Ciência de Dados e Machine Learning:

- Importação e manipulação de dados
- Tratamento de dados
- Verificação de valores nulos
- Codificação de variáveis categóricas com LabelEncoder
- Separação entre treino e teste
- Modelos de classificação
- Avaliação de acurácia
- Análise de importância das variáveis

---

# 🧠 Modelos Utilizados

Foram utilizados dois algoritmos de classificação:

## 🌳 Random Forest (Árvore de Decisão)

Modelo baseado em múltiplas árvores de decisão, utilizado para classificação supervisionada.

## 👥 K-Nearest Neighbors (KNN)

Modelo baseado nos vizinhos mais próximos para classificação dos dados.

---

# 📈 Resultados

Os modelos foram comparados utilizando a métrica de acurácia.

Resultados obtidos:

| Modelo | Acurácia |
|---|---|
| Random Forest | 82% |
| KNN | 73% |

O modelo Random Forest apresentou melhor desempenho para este conjunto de dados.

---

# 🔍 Variáveis Mais Importantes

O projeto também realiza análise das features mais relevantes para definição do score de crédito, como:

- dívida total
- mix de crédito
- juros de empréstimo
