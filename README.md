# Modelo Conceitual de E-commerce 
Este repositório contém o modelo conceitual de banco de dados desenvolvido para gerenciar um sistema de e-commerce com fornecedores, produtos, clientes, pedidos, estoque, pagamentos e entregas. O modelo foi construído utilizando diagrama Entidade-Relacionamento, com foco em organização, integridade e escalabilidade dos dados.

###Entidades:
-	Fornecedor: Inclui informações como razão social, CNPJ e um identificador único.
-	Produto: Contém detalhes como valor, descrição e categoria.
-	Cliente: Abrange tanto pessoas físicas (CPF) quanto jurídicas (CNPJ), cada uma com seus atributos específicos.
-	Pedido: Inclui informações sobre o cliente, produtos solicitados, status do pedido e detalhes de frete.
-	Estoque: Gerencia informações como quantidade disponível de produtos.
-	Entrega: Integra o pedido com dados de rastreio e status da entrega.
-	Pagamento: Contempla diferentes métodos como PIX e cartão, com seus respectivos atributos.
