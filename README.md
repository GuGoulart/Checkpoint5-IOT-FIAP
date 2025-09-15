# Checkpoint 05 — Redes Neurais com Keras
 
1. **Exercício 1 — Classificação (Wine Dataset)**  
   Aplicação de uma rede neural para classificar vinhos em 3 categorias.  
 
2. **Exercício 2 — Regressão (California Housing)**  
   Aplicação de uma rede neural para prever o preço médio de casas na Califórnia. 
 
---
 
## Como executar os notebooks

1. Acesse: [Google Colab](https://colab.research.google.com/).  
2. Clique em **File → Upload notebook** e selecione os arquivos que deseja ver 
3. Execute as células na ordem 

---

### Notebook 1 Classificação (Wine Dataset)

🔹 Descrição
Dataset: Wine, com 13 atributos (ex.: teor alcoólico, acidez, etc.) e 3 classes de vinho.
Objetivo: treinar uma rede neural para classificar corretamente o tipo de vinho.
 
🔹 Etapas
1. Carregamento do dataset
2. Normalização dos atributos usando StandardScaler.
3. Construção de rede neural com Keras:
  -Entrada: 13 atributos.
   
  -Duas camadas ocultas de 32 neurônios (ativação ReLU).

  -Camada de saída com 3 neurônios (ativação softmax).

  -Função de perda: categorical_crossentropy.

  -Otimizador: Adam.
 
 
4. Treinamento por 50 épocas.
 
 
5. Avaliação do modelo em dados de teste.
 
 
6. Comparação com RandomForestClassifier.
 
 
 
🔹 Métrica utilizada
 
Accuracy (acurácia) — porcentagem de acertos do modelo.
 
 
🔹 Resultados esperados
 
O modelo em Keras deve alcançar alta acurácia.
 
Comparar o valor obtido com o RandomForest e comentar qual teve melhor desempenho.
 
 
 
---
 
## Exercício 2 — Regressão (California Housing)
 
🔹 Descrição
 
Dataset: California Housing, com 8 atributos (ex.: número de quartos, idade da casa, etc.) e valor médio das casas.
 
Objetivo: treinar uma rede neural para prever o preço médio das casas.
 
 
🔹 Etapas
 
1. Carregamento do dataset com sklearn.datasets.fetch_california_housing.
 
 
2. Normalização dos atributos usando StandardScaler.
 
 
3. Construção de rede neural com Keras:
 
Entrada: 8 atributos.
 
Três camadas ocultas: 64 → 32 → 16 neurônios (ativação ReLU).
 
Camada de saída: 1 neurônio (linear).
 
Função de perda: MSE (Mean Squared Error).
 
Otimizador: Adam.
 
 
 
4. Treinamento por 100 épocas.
 
 
5. Avaliação do modelo em dados de teste.
 
 
6. Comparação com LinearRegression e RandomForestRegressor.
 
 
 
🔹 Métricas utilizadas
 
MSE (Mean Squared Error)
 
RMSE (Root Mean Squared Error)
 
MAE (Mean Absolute Error)
 
 
🔹 Resultados esperados
 
A rede neural deve obter erros relativamente baixos.
 
Comparar RMSE/MAE com os modelos tradicionais e discutir qual teve melhor desempenho.


 ## Integrantes:
 Gustavo Goulart Bretas 
 
 RM555708
