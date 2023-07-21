# Classificação de Saúde Fetal utilizando Inteligência Artificial

## Sobre

Este é o repositório do projeto de Classificação de Saúde Fetal utilizando técnicas de Aprendizado de Máquina para a disciplina de Inteligência Artificial. O objetivo deste projeto é realizar a classificação adequada da saúde fetal com base em dados biomédicos, permitindo uma detecção precoce de possíveis problemas e, consequentemente, melhorando a qualidade do atendimento médico durante a gravidez.

## Descrição do Projeto

Neste projeto, utilizamos o conjunto de dados [Fetal Health Classification](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification) disponibilizado no Kaggle. O conjunto de dados contém informações biomédicas extraídas de cardiotocogramas (CTGs), que são gráficos que representam a frequência cardíaca fetal em relação às contrações uterinas.

As etapas principais do projeto foram as seguintes:

1. Análise Exploratória de Dados: Realizamos uma análise exploratória detalhada do conjunto de dados para entender suas características, identificar possíveis correlações e avaliar a qualidade dos dados.

2. Pré-processamento de dados: Os dados já haviam sido tratados previamente, então não foi necessário um grande esforço de pré-processamento dos dados.

3. Separação do Conjunto de Treinamento e Teste: Dividimos o conjunto de dados em conjuntos de treinamento e teste para avaliar a capacidade de generalização dos modelos.

4. Treinamento dos Modelos: Utilizamos a biblioteca Scikit-learn para treinar diversos modelos de aprendizado de máquina, incluindo (mas não limitado a) SVM, Random Forest e Regressão Logística.

5. Teste de melhora nas métricas com a utilização de Oversampling e Undersampling: Apesar de refletir a realidade, uma vez que a classe majoritária possui um numero extremamente maior de ocorrências do que as demais classes, testamos as técnicas para balancear as classes do conjunto de dados. Verificamos que não houve um incremento das métricas de avaliação em relação aos modelos treinados com os dados desbalanceados.

5. Avaliação do Desempenho: Calculamos as métricas de avaliação, incluindo a matriz de confusão e a acurácia, para cada modelo treinado. Isso nos permitiu comparar o desempenho dos diferentes modelos e selecionar o melhor para a tarefa de classificação.

## Autores

Este projeto foi desenvolvido como parte do trabalho acadêmico na disciplina de Inteligência Artificial. Os autores deste projeto são:

- Paulo André
  GitHub: [github.com/pauloandreoliv](https://github.com/pauloandreoliv)

- Diana Correia
  GitHub: [github.com/sykes-07](https://github.com/sykes-07)

## Como Executar o Projeto

Para executar este projeto, siga as etapas abaixo:

1. Abra o arquivo Jupyter Notebook no Google Colab ou em sua IDE preferida.

2. Execute as células do notebook sequencialmente para reproduzir a análise, treinamento dos modelos e avaliação de desempenho.

Obs.: Você pode modificar o notebook para experimentar diferentes algoritmos de aprendizado de máquina ou técnicas de pré-processamento.

## Requisitos do Projeto

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas
- Numpy
- Matplotlib

## Observações

Este projeto foi desenvolvido como uma atividade acadêmica com o propósito de aprendizado e prática de técnicas de análise de dados e aprendizado de máquina. Os resultados obtidos e os modelos treinados não devem ser usados como diagnóstico médico. Sempre consulte um profissional de saúde qualificado para qualquer avaliação ou tratamento médico.
