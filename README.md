*Projeto realizado a partir de informações sobre vendas de 01/01/2022 até 24/11/2022*


## V1 

 
1. Gerar conjuntos frequentes 
      - Utilizar o algoritmo *apriori* c/ min_support=0.02 ('se um conjunto é frequente, então todos os seus subconjuntos também são')
  
2. Gerar regras de associação
  - Usar o Suporte para obtermos a fração das transações em que occorrem um conjunto de itens
       - Conjunto frequente se, frequencia > limiar estipulado ( confiança > 0.5 )
       - s(X) = itemsetX / Ntransactions
       - s(X->Y) = (itemsetX U itemsetY ) / Ntransactions
       - sendo que, confianca(X->Y) = (itemsetX U itemsetY) / itemsetX
       
3. Resultados
      - Avaliar os 10 conjuntos mais frequentes
      - Avaliar as 10 primeiras linhas do modelo após as regras de associação
      

      
      
## V2 -> reduzir numero de colunas
 
