# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste projeto, foi desenvolvido o  estudo usando  o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). 

## 📋 Pré-requisitos

Foi criando uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Previsão de Estoque Inteligente)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Coleta de dados: É necessário coletar dados históricos de vendas, informações de estoque, dados de marketing e outros fatores que possam influenciar a demanda dos produtos.
- Os dados coletados precisam ser limpos e preparados para análise. Isso pode envolver a remoção de dados ausentes, a normalização de valores e a transformação de dados categóricos em formatos adequados para o modelo de machine learning.
- Seleção de recursos: Nem todos os dados coletados podem ser relevantes para a previsão de estoque. É importante identificar os recursos mais importantes que têm maior impacto na demanda dos produtos.
- Treinamento do modelo: Com os dados pré-processados e os recursos selecionados, o modelo de machine learning pode ser treinado usando algoritmos como regressão linear, árvores de decisão, redes neurais ou algoritmos mais avançados, como Random Forests ou Gradient Boosting.
- Avaliação do modelo: Após o treinamento, o modelo precisa ser avaliado para verificar sua precisão e desempenho. Isso pode ser feito usando métricas como erro médio absoluto (MAE), erro médio quadrático (MSE).
- Previsão de estoque: Com o modelo treinado e avaliado, ele pode ser usado para fazer previsões de estoque com base nos dados atuais de vendas, estoque e outros fatores relevantes. Essas previsões podem ajudar a determinar os níveis ideais de estoque para atender à demanda futura.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importei o dataset que e submeti a treinamento.
-   Configurado as variáveis de entrada e saída de acordo com os dados.
-   Iniciado o treinamento do modelo. 

### 3. Análise

-   Após o treinamento, examinamos as métricas de performance do modelo.
-   Foi verificado as principais características que influenciam as previsões.

### 4. Prever

-   O modelo treinado foi desenvolvido para fazer previsões de estoque de forma a manter produtos com maiores tendências de consumo.
