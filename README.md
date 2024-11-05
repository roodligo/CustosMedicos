# Custos Médicos

Este projeto visa prever os custos médicos com base em características como idade, sexo, índice de massa corporal (IMC), número de filhos, status de fumante e região. Inicialmente, foi utilizado um modelo de Regressão Linear, mas o modelo foi aprimorado para Random Forest, que demonstrou melhor desempenho na previsão dos custos médicos.

## Dataset

O dataset utilizado é `insurance.csv`, que contém os seguintes campos:



- **age**: Idade do paciente
- **sex**: Gênero do paciente
- **bmi**: Índice de Massa Corporal
- **children**: Número de filhos
- **smoker**: Status de fumante
- **region**: Região onde o paciente vive
- **charges**: Custos médicos (variável alvo)

Dataset obtido em:
https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download

Apresentação do Projeto:
https://www.youtube.com/watch?v=XcFZjodQgNM

- **Bibliotecas**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## Estrutura do Projeto

1. **Exploração de Dados**: Analisa as primeiras entradas e a estrutura do dataset.
2. **Pré-processamento**: Executa o pré processamento dos dados, identificado clusters e outliers.
3. **Divisão dos Dados**: Divide o dataset em treino e teste.
4. **Treinamento do Modelo**: Inicia com uma Regressão Linear para modelagem dos custos médicos, posteriormente substituída por Random Forest para aprimorar a precisão.
5. **Avaliação do Modelo**: Avalia o desempenho com métricas (MAE), (MSE) e (R²).
