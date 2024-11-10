# dio_db_ecommerce
Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE


Descrição do Desafio
=====================
O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações; 
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento; 
* Entrega – Possui status e código de rastreio;
  
Agora é a sua vez de ser o protagonista! Implemente o desafio sugerido pela expert e suba seu projeto para um repositório próprio, com isso, você aumentará ainda mais seu portfólio de projetos no GitHub!

Descrição do Projeto Conceitual
===============================
Escopo: Venda de produtos

Narrativa:  
Produto:
* Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros).
* Cada produto possui um fornecedor.
* Um ou mais produtos podem compor um pedido.

Cliente:
* O cliente pode se cadastrar no site com seu CPF ou CNPJ.
* O endereço do cliente irá determinar o valor do frete.
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

Pedido:
* Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
* Um produto ou mais compoem o pedido.
* O pedido pode ser cancelado.
* Pode ser pago com mais de uma forma de pagamento.

Fornecedor:
* Deverá ser pessoa Jurídica
* Podem existir 1 ou mais fornecedores cadastrados para o mesmo produto.

Estoque:
* Deve possuir o local que o produto está estocado e a quantidade do estoque.

Entrega:
* Deve possuir dados de status e código de rastreio.
* Um pedido pode ser entregue mais de uma vez caso a tentativa anterior seja falha.
* Deve ser entregue por uma transportadora cadastrada.

Pagamento:
* Devem existir várias formas de pagamento.
