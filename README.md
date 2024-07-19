<a name="ancora"></a>
Para ler em Portugues, basta seguir com a leitura | Click here for the [English version](#ancora1)

# 📊 Análise de Vendas Supermercado e Modelagem

## 📚 Sobre o Projeto

Este projeto visa analisar um conjunto de dados de vendas de supermercado e treinar um modelo de regressão para prever o total das vendas. O conjunto de dados foi obtido do Kaggle, uma plataforma popular para competições de ciência de dados e conjuntos de dados.

O conjunto de dados utilizado pode ser encontrado [aqui](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales).

## 🔍 Análise Prévia dos Dados

Antes de treinar o modelo, foi realizada uma análise prévia dos dados para garantir que estivessem prontos para o treinamento:

1. **Carregamento dos Dados**: Os dados foram carregados a partir de um arquivo CSV.
2. **Limpeza dos Dados**: Colunas irrelevantes (como `Invoice ID`, `Date`, e `Time`) foram removidas.
3. **Transformação de Variáveis Categóricas**: As colunas categóricas foram convertidas em variáveis dummy para serem usadas no modelo.
4. **Divisão dos Dados**: Os dados foram divididos em conjuntos de treinamento e teste.
5. **Escalonamento**: Os dados foram escalonados para melhorar o desempenho do modelo.

## 🛠️ Treinamento do Modelo

O modelo foi treinado usando uma Regressão Linear. O processo inclui:

1. **Treinamento**: O modelo foi treinado com o conjunto de dados de treinamento escalonado.
2. **Previsões**: O modelo fez previsões com base no conjunto de dados de teste.
3. **Avaliação**: O desempenho do modelo foi avaliado usando as seguintes métricas:
   - **Erro Quadrático Médio (MSE)**: Mede a média dos quadrados das diferenças entre previsões e valores reais.
   - **Erro Absoluto Médio (MAE)**: Mede a média das diferenças absolutas entre previsões e valores reais.
   - **R² Score**: Avalia a proporção da variância explicada pelo modelo.
   - **Porcentagem de Acerto**: Calculada como `100 - (Erro Absoluto Médio / Média dos Valores Reais) * 100`.

## 📈 Resultados

- **MSE (Erro Quadrático Médio)**: [Valor calculado]
- **MAE (Erro Absoluto Médio)**: [Valor calculado]
- **R² Score**: [Valor calculado]
- **Porcentagem de Acerto**: [Valor calculado]

### 🔍 Visualizações

- **Previsões vs Valores Reais**: Mostra a relação entre os valores reais e as previsões do modelo.
- **Distribuição dos Erros**: Analisa como os erros se distribuem.

## 📦 Requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

- pandas
- scikit-learn
- matplotlib
- seaborn

Você pode instalar essas dependências com:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## 📝 Conclusão
Este projeto fornece uma visão sobre como preparar dados para modelagem e avaliar o desempenho de um modelo de regressão. A análise dos resultados ajuda a entender a eficácia do modelo e identificar áreas para possíveis melhorias.

## 📎 Referência
O conjunto de dados utilizado foi obtido do Kaggle: Link para o conjunto de dados
	
---

<a id="ancora1"></a> 
# 📊 Supermarket Sales Analysis and Modeling

## 📚 About the Project
This project aims to analyze a supermarket sales dataset and train a regression model to predict the total sales. The dataset was obtained from Kaggle, a popular platform for data science competitions and datasets.

The dataset used can be found here.

## 🔍 Preliminary Data Analysis
Before training the model, a preliminary analysis of the data was conducted to ensure it was ready for modeling:

Data Loading: Data was loaded from a CSV file.
Data Cleaning: Irrelevant columns (such as Invoice ID, Date, and Time) were removed.
Categorical Variable Transformation: Categorical columns were converted to dummy variables for use in the model.
Data Splitting: The data was split into training and test sets.
Scaling: Data was scaled to improve model performance.

## 🛠️ Model Training
The model was trained using Linear Regression. The process includes:

Training: The model was trained on the scaled training dataset.
Prediction: The model made predictions based on the test dataset.
Evaluation: The model's performance was evaluated using the following metrics:
Mean Squared Error (MSE): Measures the average of the squares of the differences between predictions and actual values.
Mean Absolute Error (MAE): Measures the average of the absolute differences between predictions and actual values.
R² Score: Assesses the proportion of variance explained by the model.
Accuracy Percentage: Calculated as 100 - (Mean Absolute Error / Mean of Actual Values) * 100.

## 📈 Results
MSE (Mean Squared Error): [Calculated value]
MAE (Mean Absolute Error): [Calculated value]
R² Score: [Calculated value]
Accuracy Percentage: [Calculated value]

## 🔍 Visualizations
Predictions vs Actual Values: Shows the relationship between actual values and model predictions.
Error Distribution: Analyzes how errors are distributed.

## 📦 Requirements
Ensure you have the following libraries installed:

pandas
scikit-learn
matplotlib
seaborn

You can install these dependencies with:
```bash
pip install pandas scikit-learn matplotlib seaborn
```
## 📝 Conclusion
This project provides insight into preparing data for modeling and evaluating the performance of a regression model. The analysis of the results helps to understand the model's effectiveness and identify areas for potential improvement.

## 📎 Reference
The dataset used was obtained from Kaggle: [Link to the dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)
