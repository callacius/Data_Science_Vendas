# Departamento de Vendas

>   Um dos pontos cruciais de marketing é conhecer os clientes e  identificar suas necessidades.
>   Entendendo os consumidores podemos enviar campanhas  específicas para necessidades específicas.
>   Se dados sobre os clientes estão disponíveis, podemos aplicar  Ciência de Dados para segmentar o mercado.
>   Fomos contratados por um banco de NYC para analisar os dados e  dividir os clientes em pelo menos 3 grupos.  
  
-   Para que as empresas sejam competitivas e crescerem, o uso de  IA/ML é muito importante para previsões de vendas futuras.
-   Modelos de previsão de vendas futuras baseados em dados do passado devem considerar efeitos sazonais, como por exemplo: demanda, feriados, promoções e concorrência.
-   Neste projeto, nós trabalhamos como cientista de dados de uma  rede de lojas físicas e temos dados de 1.115 lojas!
-   O objetivo é prever vendas futuras.

**DADOS DAS TRANSAÇÕES**
-   Id: identificador da transação (loja + data).
-   Loja: identificador único da loja.
-   Sales: vendas/dia (objetivo).
-   Customers: número de clientes no dia.
-   Open: boleano que indica se a loja estava aberta ou  fechada (1 = aberta, 0 = fechada).
-   Promo: se existe uma promoção no dia.
-   StateHoliday: feriado (a = feriado público, b = Páscoa, c = Natal, 0 = nenhum).
-   SchoolHoliday: feriado escolar.
-   StoreType: tipo da loja (a, b, c, d).
-   Assortment: a = basic, b = extra, c = extended.
-   CompetitionDistance (metros): distância para a loja  concorrente mais perto.
-   CompetitionOpenSince [Month/Year]: data que a loja concorrente foi aberta.
-   Promo2: promoção contínua e consecutiva em algumas lojas(0 = não está participando, 1 = está participando)
-   Promo2Since [Year/Week]: data quando a loja começou a  participar da Promo2.
-   PromoInterval: intervalos consecutivos que a Promo2 é  iniciada (meses). Exemplo: "Feb,May,Aug,Nov" indica que  cada “round” da promoção começa em
February, May, August, November
**FACEBOOK PROPHET (PROFETA)**
-   É um software open source lançado pelo time de Ciência de Dados do Facebook.
-   Permite a previsão de séries temporais baseado em “regressão  aditiva”.
-   Tendências não lineares podem ser descobertas anualmente,  semanalmente, diariamente(considera feriados).
-   Funciona melhor com efeitos sazonais e com grande quantidade de dados.

Fontes
  https://research.fb.com/prophet-forecasting-at-scale/
  https://facebook.github.io/prophet/docs/quick_start.html#python-api

Fonte: ![Curso Udemy](**https://www.udemy.com/course/ciencia-de-dados-para-empresas-e-negocios**)
