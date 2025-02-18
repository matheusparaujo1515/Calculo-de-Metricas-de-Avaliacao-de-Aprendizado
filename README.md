# Desafio de Calculo de Metricas de Aprendizado de Maquina

## Contexto
Este projeto fez parte do desafio proposto no **Bootcamp BairesDev - Machine Learning Practitioner**, cujo objetivo foi calcular e analisar metricas de aprendizado de maquina aplicadas a um modelo de classificacao binaria. O desafio envolveu a geracao de dados sintéticos e a implementacao de um modelo de aprendizado supervisionado, utilizando tecnicas estatísticas para avaliacao da performance do modelo.

## Objetivo
O desafio consistiu em desenvolver um pipeline de treinamento e avaliacao de um modelo de classificacao binaria, abrangendo as seguintes etapas:
- Criacao de um dataset sintético com distribuicao normal.
- Treinamento de um modelo Random Forest.
- Calculo de metricas de avaliacao como acuracia, precisao, sensibilidade, especificidade e F-score.
- Visualizacao da matriz de confusao utilizando heatmap.

## Tecnologias e Bibliotecas Utilizadas
- Python
- Pandas (Manipulacao e processamento de dados)
- Numpy (Geracao de dados sintéticos)
- Seaborn (Visualizacao de dados)
- Matplotlib (Plotagem de graficos)
- Scikit-learn (Treinamento do modelo e calculo de metricas)

## Como Funciona
1. **Geracao do Dataset**: Criacao de um conjunto de dados contendo tres colunas numericas geradas aleatoriamente e uma variavel resposta binaria.
2. **Treinamento do Modelo**: Divisao do dataset em treino e teste, seguida pelo treinamento de um classificador Random Forest.
3. **Avaliacao do Modelo**: Calculo das metricas de desempenho atraves da matriz de confusao.
4. **Visualizacao dos Resultados**: Criacao de um heatmap para ilustrar a matriz de confusao.

## Como Executar o Codigo
1. Instale as dependencias necessarias:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
2. Execute o script para gerar os dados, treinar o modelo e calcular as metricas.
3. Visualize os resultados atraves da matriz de confusao.

## Exemplo de Uso
1. O script cria um dataset contendo 1000 amostras.
2. Um modelo Random Forest e treinado para classificar os dados.
3. As metricas de desempenho sao calculadas e exibidas no console.
4. A matriz de confusao e plotada para melhor compreensao dos resultados.

## Melhorias Futuras
- Implementacao de otimizacao de hiperparametros para o modelo.
- Aplicacao de tecnicas de balanceamento de classes para datasets desbalanceados.
- Comparacao com outros algoritmos de aprendizado de maquina.

## Documentacao das Bibliotecas
- Pandas: https://pandas.pydata.org/docs/
- Numpy: https://numpy.org/doc/
- Seaborn: https://seaborn.pydata.org/
- Matplotlib: https://matplotlib.org/stable/contents.html
- Scikit-learn: https://scikit-learn.org/stable/documentation.html
