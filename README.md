## Contexto
Rossmann opera mais de 3.000 drogarias em 7 países europeus. Atualmente, os gerentes de loja da Rossmann têm a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas da loja são influenciadas por muitos fatores, incluindo promoções, competição, feriados escolares e estaduais, sazonalidade e localidade. Com milhares de gerentes individuais prevendo vendas com base em suas circunstâncias únicas, a precisão dos resultados pode ser bastante variada. Você pode baixar o conjunto de dados aqui: https://www.kaggle.com/c/rossmann-store-sales/data.


## Problema de Negócio
Em primeiro lugar, precisamos entender qual é o nosso problema de negócios. Portanto, criamos um contexto para nos ajudar a construir a solução. Então, vamos seguir essas quatro etapas.


- Qual é o contexto?

    * Em reunião com os líderes de cada departamento, o CEO da Rossmann fez a proposta de reformar todas as lojas.
    
    
- Qual é a causa?

     * O CEO da Rossmann quer prever quanto cada loja vai vender nas próximas 6 semanas. Ele precisa saber se o orçamento será suficiente para fazer uma reforma em cada loja.
     
     
- Quem vai liderar o projeto?

    * Precisamos de alguém que realmente saiba qual é o problema do negócio, porque ele vai liderar a solução. Portanto, ele é nosso stakeholder.
    
    
- Como ficará nossa solução?

    * Qual é o formato?
    
        - Granularidade (hora, dia, produto) ---> 6 semanas
        
        - Tipo de problema (classificação, regressão, agrupamento, etc.) ---> Regressão
        
        - Como vamos entregar? (painel, csv, Notebook) ---> Notebook
 
## Etapas do Projeto
Seguiremos todas essas etapas a seguir para a resolução do nosso projeto:

- 0.0. IMPORTS
- 1.0. DESCRIÇÃO DOS DADOS
- 2.0. FEATURE ENGINEERING
- 3.0. FILTRANDO OS DADOS
- 4.0. ANÁLISE EXPLORATÓRIA DOS DADOS
- 5.0. PREPARAÇÃO DOS DADOS
- 6.0. SELEÇÃO DE FEATURES
- 7.0. MACHINE LEARNING
- 8.0. INTERPRETANDO OS RESULTADOS
