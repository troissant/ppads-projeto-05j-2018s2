# Casos de uso

## CDU001 > Efetuar Pedido

### Fluxo principal

1. Cliente entra no sistema (login)
2. Cliente navega pelo catálogo de farmácia X e seleciona os itens e quantidades a serem comprados 
3. Cliente vai para o Checkout
4. Cliente confirma endereço de entrega
5. Cliente seleciona forma de pagamento de cartão de crédito
6. Cliente insere os dados do cartão de crédito para a compra
7. Cliente efetua a compra
8. Sistema retorna dados do pedido (código, informações, etc...)

  ### Fluxo alternativo 

1. Cliente entra no sistema (login)
2. Cliente navega no menu e procura farmácia X e farmácia Y
3. Cliente navega pelo catálogo das farmácias X e Y e encontra um remédio em farmácia X e dois em Y
4. Cliente seleciona os itens a serem comprados
5. Cliente vai para o Checkout
6. Cliente confirma endereço de entrega
7. Cliente seleciona forma de pagamento de boleto bancário
8. Sistema gera boleto bancário
9. Cliente paga o boleto bancário
10. Sistema aguarda o pagamento do boleto e retorna dados do pedido (código, informações, etc...)

  ### Fluxo alternativo

1. Cliente navega pelo catálogo de farmácia X e seleciona os itens e quantidades a serem comprados
2. Cliente vai para o Checkout
3. Cliente não possui cadastro então Cliente se cadastra no momento do Checkout
4. Cliente confirma endereço de entrega
5. Cliente seleciona a forma de pagamento cartão de crédito
6. Cliente insere os dados do cartão de crédito para a compra
7. Cliente efetua a compra
8. Sistema retorna os dados do pedido (código, informações, etc...)


## CDU002 > Acompanhar Pedido

1. Cliente entra no sistema (login)
2. Cliente vai no Menu da conta e seleciona Meus Pedidos 
3. Sistema retorna lista de Pedidos da conta
4. Cliente seleciona Pedido para acompanhar
5. Sistema retorna dados do pedido selecionado (itens, horário da compra, status, etc...)

## CDU003 > Consultar Histórico

1. Cliente entra no sistema (login)
2. Cliente vai no Menu da conta e seleciona Meus Pedidos
3. Sistema retorna lista de Pedidos da conta 
4. Cliente visualiza histórico de Pedidos 
