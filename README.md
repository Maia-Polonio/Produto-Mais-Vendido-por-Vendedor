# Produto-Mais-Vendido-por-Vendedor
🔍 Análise Exploratória de Dados: Produto Mais Vendido por Vendedor 🚀

Para análise de produtos mais vendidos por vendedor num site de E-commerce, utilizei uma CTE (Common Table Expression) e uma função Window Functions para identificar o produto mais vendido por cada vendedor.

CTE - Sellers:
Objetivo: Agrupar dados de vendedores e produtos.
Ações: Contamos o número de pedidos distintos e somamos o valor total das vendas para cada produto e vendedor.

CTE - Rankeamento:
Objetivo: Classificar os produtos vendidos por cada vendedor.
Ações: Utilizamos a função de janela row_number() para rankear os produtos por vendedor, baseando-se na quantidade e valor das vendas.

Seleção Final:
Objetivo: Selecionar o produto mais vendido por cada vendedor.
Ações: Filtramos os dados para obter apenas os produtos com ranking 1, ou seja, o mais vendido por vendedor.

✨ Conclusão: Essa abordagem eficiente permite identificar rapidamente quais produtos são mais vendidos por cada vendedor, ajudando a otimizar estratégias de vendas. 🚀📊
