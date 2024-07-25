Este código é uma tentativa de implementar os serviços ofertados pelos Correios na Odoo, por um leigo e aspirante a "garoto de programa".
Estou utilizando a versão 17.0 da Odoo e a mais recente de Python.
Espero que essas linhas sirvam pelo menos para inspiração.
Deverá ser solicitado: CEP, número, medidas da embalagem e peso bruto total.
Objetivo: validar o CEP informado, calcular o valor da entrega levando em consideração seu endereço local e o de destino, utilizar seu próprio contrato, dar as opções de serviços dos Correios e os valores para o usuário selecionar
Na Odoo ele deve conter mais um módulo para adicionar o valor à fatura do pedido.
