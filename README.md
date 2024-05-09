# Delivery-Center---Desafio-do-clube-Universidade-dos-Dados

Esse conjunto de dados representa uma plataforma integrada de lojistas e marketplaces para venda de comidas no varejo brasileiro, representando os dados de pedidos, entregas e seus intermediários entre os meses de janeiro e abril de 2021. Ele está disponível no Kaggle, sem a inteireza dos dados para preservar a privacidade dos envolvidos, no link: https://www.kaggle.com/datasets/nosbielcs/brazilian-delivery-center?select=channels.csv. Esse conjunto demonstra como as decisões de negócio passaram a ser cada vez mais guiadas pelos dados gerados pelos envolvidos nas transações comerciais na medida em que eles permitem entender o comportamento real e potencial das empresas e os hábitos de consumo dos clientes. Os dados disponíveis auxiliam a aumentar a eficiência da empresa e a satisfação dos usuários. Mais ainda, eles permitem que eu treine as minhas aptidões com as bibliotecas Numpy, Pandas, Matplotlib e Seaborn.

Ele é formado por diferentes datasets. São elas:

- channels: este dataset possui informações sobre os canais de venda (marketplaces) onde são vendidos os produtos dos lojistas.
- deliveries: este dataset possui informações sobre as entregas realizadas pelos entregadores parceiros.
- drivers: este dataset possui informações sobre os entregadores.
- hubs: Este dataset possui informações sobre os hubs (centros de distribuição dos pedidos da onde saem as entregas).
- orders: este dataset possui informações sobre as vendas processadas através da plataforma.
- payments: este dataset possui informações sobre os pagamentos realizados.
- stores: este dataset possui informações sobre os lojistas que utilizam a plataforma para vender seus itens.

As perguntas a seguir intentam responder à um desafio do clube Universidade dos Dados:

1. Suponha que, em uma ação de marketing, para atrair mais entregadores, vamos dar uma bonificação para os 20 entregadores que possuem maior distância percorrida ao todo. A bonificação vai variar de acordo com o tipo de profissional que ele é e o modelo que ele usa para se locomover. É preciso levantar, então, essas informações.
2. O time de Pricing precisa ajustar os valores pagos aos entregadores. Para isso, eles precisam da distribuição da distância média percorrida pelos motoqueiros separada por estado, já que cada região terá seu preço.

As conclusões encontradas a partir da análise são:
- Aproximadamente 72% dos entregadores são freelancers e aproximadamente 28% são operadores de logística
- Aproximadamente 73% dos entregadores são motoboys e aproximadamente 27% são ciclistas
- Aproximadamente 89% das lojas vendem food
- Cerca de 11% das lojas vendem good
- A média de distância percorrida pelos 20 motoboys que mais fizeram deliveries é aproximadamente 7597 km
- Desses 20, 60% dos entregadores é do tipo freelance e 40% é do tipo logistic operator.
- 10 motoboys percorreram entre 2967.23 e 3651.29 km
- A média de distância percorrida pelos 20 ciclistas que mais fizeram deliveries é de 608.11 km
- Desses 20, todos são freelancers
- 10 ciclistas percorreram 524.12 km e 617.13 km
- O estado com maior distância mediana para food é o Rio Grande do Sul
- Os estados com maior mediana para good são Rio Grande do Sul e São Paulo
- O estado com menor mediana para food é São Paulo
- O estado com menor mediana para good é o Rio de Janeiro
- A receita líquida média das lojas que vendem good é quase o triplo da receita média bruta das lojas que vendem food
- O Rio Grande do Sul possui a maior receita líquida média e a segunda menor para os bens de tipo food.
- O Rio de Janeiro possui a menor para os bens de tipo good e a segunda maior receita líquida média para os bens de tipo food, atrás apenas de São Paulo
- O Paraná possui a menor receita líquida média para os bens de tipo food
- Apesar das receitas líquidas médias serem maiores para o tipo de bem good, a receita líquida total das lojas que vendem food é aproximadamente 3 vezes maior do que aquelas que vendem good
- O Rio Grande do Sul, que possuía a receita líquida média mais alta para os goods, apresenta a segunda menor receita líquida total
São Paulo e Rio de Janeiro lideram as receitas
