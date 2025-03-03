# Modelo k-3

Este projeto foi desenvolvido para participar da competição de machine learning "Binary Prediction with a Rainfall Dataset", hospedada no Kaggle.


## Resultados dos Modelos

- **m1** Score no Kaggle: 0.82381 / RMSE: 0.31712350161181013
- **m1_1** Score no Kaggle: 0.82381 / RMSE: 0.31712350161181013
- **m_2** Score no Kaggle: 0.85894 / RMSE: 0.31684929778141385

## Detalhamento das Versões
### m1:

- Descrição: Modelo inicial criado utilizando os datasets disponibilizados na competição.
- Tratamento de Dados: Nenhum tratamento de dados foi realizado.
- Modelo: Utilização do CatBoostRegressor sem ajuste de hiperparâmetros.
- Submissão: Um script foi desenvolvido para gerar um arquivo CSV para submissão na competição.

### m1_1:

- Adicionado código para validação cruzada.

### m1_2:

- Adicionado tratamento para outliers
