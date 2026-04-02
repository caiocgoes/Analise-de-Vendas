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

# Análise geral dos resultados

1. Categoria com maior faturamento:

   1.1 A categoria de Eletrônicos é a que apresenta maior dominância nas vendas (67%). Uma boa estratégia seria maximizar seu desempenho por meio de:

     a) Upsell → Oferecer aos clientes que já estão comprando nessa categoria versões superiores dos produtos mais vendidos (ex: mais memória, melhor câmera — especialmente no caso de celulares — ou maior tempo de garantia).

     b) Cross-sell → Vender itens complementares aos produtos que o cliente já está adquirindo. No caso de notebooks (produto campeão), oferecer promoções de itens como mouse, mousepad gamer, headsets ou carregadores.

     c) O principal objetivo para essa categoria é manter a liderança e aumentar o ticket médio.
   
   1.2 A categoria de Móveis é a segunda com maior participação nas vendas (27%). Uma estratégia adequada seria alavancar seu crescimento, buscando atingir algo entre 35% e 40%, por meio de:

     a) Oferecer frete grátis, considerando que a logística é um dos principais desafios dessa categoria;

     b) Trabalhar o fator preço, oferecendo melhores condições de pagamento, como parcelamento facilitado ou criação de combos (ex: cadeira + mesa).
   
   1.3 A categoria de Acessórios possui baixo faturamento, porém geralmente apresenta baixo custo logístico e forte apelo de compra impulsiva. Ou seja, performa melhor quando associada a outros produtos. Estratégias recomendadas:

     a) Criar ofertas que incentivem o cliente a sempre adicionar um acessório à compra;

     b) Desenvolver combos de acessórios com outros produtos.
   
   1.4 Apesar do faturamento mais baixo (assim como acessórios), a categoria de Livros apresenta alto volume de pedidos e forte recorrência, já que a maioria dos clientes realizou mais de uma compra. Dessa forma, sugerem-se as seguintes estratégias:

    a) Posicionar a categoria como porta de entrada de clientes;

    b) Criar campanhas focadas em livros com o objetivo de atrair novos clientes;

    c) Implementar notificações sobre novos títulos e recomendações personalizadas.

3. Qual mês de maior faturamento:

   O mês com maior faturamento foi abril, com aproximadamente R$ 1,57 milhão. 

4. Qual produto campeão em vendas ?

   O produto com maior faturamento foi o notebook, com aproximadamente R$ 8,2 milhões em vendas. Observa-se também que produtos como mesa, monitor e cadeira apresentam alto desempenho, indicando um padrão de consumo voltado à montagem de setup de trabalho ou estudo, possivelmente ligado ao público de tecnologia. Estratégias sugeridas:

    a) Criar jornadas de compra (game changer): Em vez de vender produtos isolados, vender a ideia de montar um setup completo (ex: notebook + monitor + mesa + cadeira + acessórios).

    b) Criar kits promocionais, como: Kit Home Office (Notebook + Monitor + Mouse + Teclado), Kit Programador (Notebook + Livro de Python + Mochila)

Isso contribui para aumentar o ticket médio, impulsionar a venda de acessórios e integrar a categoria de livros.

    c) Cross-sell entre categorias: Dado que acessórios e livros têm menor participação, criar estratégias que conectem essas categorias aos eletrônicos, especialmente considerando o perfil do cliente (ex: produtos voltados à área de tecnologia, como mousepad e livros técnicos).

5. Analise de vendas por vendedor

  A vendedora com maior faturamento foi Ana. No entanto, de forma geral, observa-se uma boa distribuição de resultados entre os vendedores, indicando equilíbrio na base de clientes ou nas metas. Apesar do faturamento semelhante, existem diferenças claras de estratégia: alguns vendedores focam em volume, enquanto outros priorizam o ticket médio. Isso abre oportunidades para otimização por meio de treinamentos direcionados e definição de KPIs mais completos. Insights:

    a) Analisar o comportamento do vendedor Carlos, que, apesar de não ter o maior faturamento, apresenta o maior ticket médio, indicando maior eficiência na venda de produtos de maior valor.

    b) A vendedora Daniela, embora tenha alto volume de pedidos e peças vendidas, apresenta menor faturamento. Recomenda-se treiná-la para aumentar o ticket médio, por meio de técnicas como upsell.

6. Análise de vendas por cliente:

 O cliente com maior volume de compras foi Mathias, e observa-se que a maioria dos clientes realizou mais de uma compra, indicando um bom nível de recorrência. Estratégias sugeridas:

    a) Segmentar os clientes em:

    Recorrentes → foco em retenção
    Pontuais → foco em aumento de frequência

    b) Aumentar o LTV (Lifetime Value) por meio de:

    e-mail marketing
    recomendações personalizadas
    cupons de retorno

    c) Criar uma clusterização de clientes (ex: VIP, Super VIP), permitindo direcionar melhor as campanhas de CRM e personalizar ofertas.


