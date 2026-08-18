Clientes

Rota: /cadastrarCliente -> Recebe os dados do front-end. Regra de Negócio: O Back-End fará um IF verificando se a idade é maior que 15 anos. Se for maior, retornar com um texto "Tudo certo". Se for igual ou menor, Retornar com "Não aprovado".

Rota: /vizualizarCliente -> Recebe os dados do front-end. Permite visualizar quais são os clientes do momento, Se o número for maior de 20, Colocar os novos em espera

Rota: /editarCliente -> Recebe os dados do front-end. Permite editar quais são os clientes do momento

Rota: /RemoverCliente -> Recebe os dados do front-end. Permite remover os clientes que cancelarem um pedido do momento
----------------------------------------------------------------------------------------------------------------------------------------------------------

Produtos

Rota: /cadastrarProduto ->  Recebe os dados do front-end. Regra de Negócio: O Back-End fará uma verificação de um sabor de pizza novo. Caso tenha ingredientes suficientes, irá adicionar ao cardápio.

Rota: /vizualizarProduto -> Recebe os dados do front-end. Permite visualizar quais são as pizzas disponíveis no momento, caso uma pizza não esteja disponível para ser feita, colocar uma faixa vermelha escrita “Fora de estoque” na imagem da pizza.


Rota: /editarProduto-> Recebe os dados do front-end. Permite editar quais são as Pizzas disponíveis do momento, se os ingredientes para uma pizza não estiverem disponíveis, bloquear a edição

Rota: /RemoverCliente -> Recebe os dados do front-end. Permite remover as pizzas que os ingredientes não estejam disponíveis no momento


Rota: /Bloqueio de pedido -> Recebe os dados do front-end. Regra de Negócio: O sistema não pode realizar pedidos das 23h até 18h.

