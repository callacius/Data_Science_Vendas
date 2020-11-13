# Departamento de Vendas

>   Um dos pontos cruciais de marketing é conhecer os clientes e  identificar suas necessidades.
>   Entendendo os consumidores podemos enviar campanhas  específicas para necessidades específicas.
>   Se dados sobre os clientes estão disponíveis, podemos aplicar  Ciência de Dados para segmentar o mercado.
>   Fomos contratados por um banco de NYC para analisar os dados e  dividir os clientes em pelo menos 3 grupos.  
  
-   CUSTID: Identificação do cliente
-   BALANCE: Saldo para fazer compras
-   BALANCE_FREQUENCY: Frequência que o saldo é atualizado (1 = frequente, 0 = não frequente)
-   PURCHASES: Quantidade de compras realizadas
-   ONEOFFPURCHASES: Quantidade de compras feitas “de uma só vez” (sem  parcelar)
-   INSTALLMENTS_PURCHASES: Quantidade de compras parceladas
-   CASH_ADVANCE: Dinheiro adiantado
-   PURCHASES_FREQUENCY: Frequência das compras (entre 1 e 0)
-   ONEOFF_PURCHASES_FREQUENCY: Frequência de compras à vista (entre 1 e  0)
-   PURCHASES_INSTALLMENTS_FREQUENCY: Frequência de compras parceladas  (entre 1 e 0)
-   CASH_ADVANCE_FREQUENCY: Frequência de saques de dinheiro adiantado
-   CASH_ADVANCE_TRX: Número de transações feitas como "Cash in Advance"
-   PURCHASES_TRX: Número de compras
-   CREDIT_LIMIT: Limite do cartão de crédito
-   PAYMENTS: Valor pago
-   MINIMUM_PAYMENTS: Valor mínimo pago
-   PRC_FULL_PAYMENT: Percentual de pagamentos da fatura “completa”
-   TENURE: Posse do titular do cartão


1.  **INTUIÇÃO K-MEANS**
-   Algoritmo não supervisionado (clustering - agrupamento)
-   Os registros são agrupados baseado em atributos similares, por meio do  cálculo da Distância Euclidiana
![Intuição k-means](https://github.com/callacius/Data_Science_Marketing/blob/main/images/01.png?raw=true)
![Intuição k-means](https://github.com/callacius/Data_Science_Marketing/blob/main/images/02.png?raw=true)

2.  **DEFINIÇÃO DO NÚMERO DE GRUPOS: “ELBOW METHOD”  (MÉTODO DO COTOVELO)**
![Elbow Method](https://github.com/callacius/Data_Science_Marketing/blob/main/images/03.png?raw=true)
![Elbow Method](https://github.com/callacius/Data_Science_Marketing/blob/main/images/04.png?raw=true)
![Elbow Method](https://github.com/callacius/Data_Science_Marketing/blob/main/images/05.png?raw=true)
![Elbow Method](https://github.com/callacius/Data_Science_Marketing/blob/main/images/06.png?raw=true)
![Elbow Method](https://github.com/callacius/Data_Science_Marketing/blob/main/images/07.png?raw=true)

3.  **PRINCIPAL COMPONENT ANALYSIS: VISÃO GERAL**
-   PCA é um algoritmo de aprendizagem não supervisionada.
-   Aplica redução de dimensionalidade, porém, tenta manter as informações  originais com as mesmas características.
-   Encontra um novo conjunto de características que são chamados de  componentes.
-   Os componentes são criados por meio das características não correlacionadas.
![component Analysis](https://github.com/callacius/Data_Science_Marketing/blob/main/images/08.png?raw=true)

4.  **AUTOENCODERS – INTUIÇÃO**
-   São um tipo de redes neurais artificiais para codificar dados.
-   Utiliza a mesma entrada e a mesma saída para comparar os resultados
![AutoEncoders](https://github.com/callacius/Data_Science_Marketing/blob/main/images/09.png?raw=true)

**CAMADAS DO AUTOENCODER**
-   Versão comprimida da informação na camada do meio (codificação).
-   Funcionam se existir correlação entre os dados de entrada (resultados  ruins se os dados de entrada são todos independentes).
![AutoEncoders](https://github.com/callacius/Data_Science_Marketing/blob/main/images/10.png?raw=true)

Fonte: ![Curso Udemy](**https://www.udemy.com/course/ciencia-de-dados-para-empresas-e-negocios**?raw=true)
