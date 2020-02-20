# Desafio

a. Como foi a definição da sua estratégia de modelagem?

A modelagem foi definida de acordo com o problema apresentado.
Como era necessário estimar a qualidade do vinho, de acordo com 12 atributos de entrada e 01 de saída, o trabalho foi baseado em príncipios de análise preditiva supervisionada, utilizando algoritmos de classificação.



b. Como foi definida a função de custo utilizada?

Não foi utilizada nenhuma função de custo, apenas indicadores de acurácia do modelo.



c. Qual foi o critério utilizado na seleção do modelo final?

O critério para a seleção foi o modelo que apresentou o maior valor de acurácia balanceada entre todos os modelos avaliados.



d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este método?

O modelo foi avalidado com os dados de teste (30% da base inicial) e validado através da acurácia balanceada resultante. 
Esse método de validação foi escolhido pelo fato das classes da variável de saída não estarem balanceadas.



e. Quais evidências você possui de que seu modelo é suficientemente bom?

O algoritmo XGBoost	foi escolhido por apresentar o melhor índice de acurácia balanceada após a execução dos processos de feature selection através do Random Forest, redução de dimensionalidade PCA e cross validation.
