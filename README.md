# Analise-de-Vendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/caiocgoes/E-commerce/blob/main/LICENSE)
# Sobre o projeto

Esse é um mini projeto resultado de um desafio proposto na comunidade dos dados.  Projeto é focado na análise simples de uma base de dados de vendas, com desenvolvimento tanto de dashboards e visualizações interativas para explorar indicadores de desempenho financeiro, como também responder perguntas importantes do negócio usando SQL e análise exploratoria com python. Os principais objetivos do projeto era responder as seguintes perguntas de negócio: 

Qual categoria de produto obteve o maior faturamento;

Qual mês com maior faturamento;

Qual produto campeão em vendas;

Análise de vendas por vendedor;

Análise de vendas por cliente;


O projeto gerou insights estratégicos para o entendimento tanto das vendas como também do comportamento do consumidor, servido como base para tomada de melhores decisões comerciais

# Tecnologias Utilizadas

- Python (pandas, matplotlib, seaborn, sqlite3 and numpy)
- Power BI

# Modelagem dos dados

<img width="634" height="185" alt="modelagem" src="https://github.com/user-attachments/assets/daad9d68-5e71-46e9-bddf-e9d524613d17" />

# Visualização 

<img width="1444" height="809" alt="Dashboard" src="https://github.com/user-attachments/assets/6ae47523-63fb-44f8-9767-74b821699d2b" />

#Análise geral dos resultados

1. Categoria com maior faturamento:

   1.1 A categoria Eletrônicos e a que possui dominância nas vendas (67%), Uma boa estratégia seria maximizar a categoria por meio de: 
       a) Upsell → Oferecer para os clientes que já estão a comprar em tal categoria versões melhores dos produtos mais comprados (ex: Mais memoria, talvez uma câmera melhor em casos de celulares principalmente, o que possuam maior garantia)
       b) Cross - Sell : Vender itens relacionados aos produtos a qual o cliente já esta comprando. No caso de notebooks o produto campeão, oferecer promoções por exemplo de mouse pad gamers, headsets ou carregadores. 
       c) O objetivo principal para essa categoria nesse momento seria manter a liderança e aumentar o ticket médio
   
   1.2 A categoria moveis e a que possui segunda maior dominância nas vendas (27%). Uma boa estratégia seria alavancar o crescimento da categoria, chegar por exemplo a 35 % - 40 %, por meio de:
       a) Oferecer por exemplo frete grátis, tendo em vista que a logistica é um dos maiores desafios dessa categoria; 
       b) Outro fator é o preço de produtos nessa categoria, uma boa estrategia seria oferecer um bom parcelamento para os clientes, ou combos com ofertas (cadeira + mesa)
   
   1.3 No caso de acessórios, possui um faturamento baixo, mas normalmente tem um baixo custo logistico e compras inpulsivas, ou seja, performa com outros produtos juntos. Um boa estrategia seria:
       a) Colocar ofertas para que sempre o cliente leve um acessório com algum outro produto;
       b) Criação de combos de produtos de acessórios com outros produtos;
   
   1.4 No caso dos livros, apesar do faturamento mais baixo assim como acessórios, tem uma grande quantidade de pedidos e foi verificado que os clientes a maioria comprarm mais de uma vez. Com isso podemos sugerir algumas opções:
       a) Transformar a categoria de livros em uma categoria de porta de entrada;
       b) Fazer campanhas focadas em livros com o objetivo de trazer mais clientes;
       c) Notificações de novos titulos;

3. Qual mês de maior faturamento:

   O mês com maior faturamento foi o mês de abril com R$ 1,57 milhão. 

4. Qual produto campeão em vendas ?

   O produto campeão de vendas foi o notebook com 8,2 milhão em vendas. Podemos ver que junto com o notebook outros produtos que estão vendendo muito são Mesa, Monitor e Cadeira, ou seja, temos um comportamento que diz que grande parte dos clientes
   são da área de Tecnologia (confirmando a maior categoria de vendas ser eletronico) e estão comprando itens para montar setup. Algumas estrategias com base nesses dados:
   a) Criar jornadas de compras (gamer change): Ao invés de vender somente um produto, vender a ideia de criar o seu setup, ou seja, comprar uma cadeira, monitor, mesa e cadeira +  acessorios
   b) Criar por exemplo kits com promoção tipo: Kit Home office (Notebook + Monitor + Mouse + Teclado) ou Kit programador (Notebook + Livro python + Mochila), o que aumenta o ticket medio de eletronicos, gira produtos de acessórios e ainda vende livros.
   c) Cross-Sell: Tendo em vista que acessorios e livros estão vendendo muito menos que Eletronicos, buscar criar combos que unam diferentes categorias. Sabendo que a maioria dos clientes provavelmente estão buscando criar seu setup, tentar vender
   produtos das categorias de livros e acessorios que estão ligados a área tech, como mouse pad, livros de tecnologia como livro de python.

5. Analise de vendas por vendedor

   O vendedor com maior faturamento entregue foi a Ana. Mas análisando em geral os resultados, vemos que temos uma boa distribuição de clientes, leads ou metas bem padronizadas. Apesar do faturamento semelhante entre vendedores, há diferenças claras de estratégia: alguns focam em volume enquanto outros maximizam ticket médio. Isso abre oportunidade para otimização através de treinamento direcionado e definição de KPIs mais completos
    Alguns insights importantes:
    a) Entender o comportamento do vendedor Carlos, pois apesar de não ser o vendedor com maior faturamento, é o que esta vendendo melhor, tendo em vista o seu maior ticket médio entre os demais vendedores.
    b) Tendo em vista que a vendedora Daniela foi a que menos vendeu em faturamento, mas a que vendeu mais em peças e pedidos, buscar fazer com que a vendedora venda produtos com maior preço, com o objetivo de aumentar seu ticket médio. Um treinamento de upsell seria ideal.

6. Análise de vendas por cliente:

   O Cliente que mais comprou foi o Mathias, e maioria dos clientes compraram mais de uma vez. Algumas estrategias validas para entender melhor o comportamento do cliente:
   a) Separar os clientes em recorrentes, com foco em retenção, e pontuais, com foco em aumentar frequencia.
   b) Aumento de LTV, atraves de emails marketing, recomendações personalizadas, cupons de retorno.
   c) Criar uma tabela de clusterização de clientes para identificação por exemplo de clientes VIPs, Super Vips e direcionar melhor as campanhas de CRM.   



