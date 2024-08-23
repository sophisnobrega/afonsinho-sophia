# Ponderada do Afonsinho s2

Tabela Regras de Negócio

| Número | História do Usuário | Descrição | Critérios de Aplicação | Responsável |
| --- | --- | --- | --- | --- |
| ES001 | Cléber precisa cadastrar os itens de estoque no sistema, mas é a primeira vez que a empresa usa ele.  | Para cadastrar itens no estoque, antes o estoquista deve cadastrar o armazém. | Registro de itens | Estoquista |
| ES002 | Cléber precisa enviar um pedido para a entrega. | Para liberar pedidos para serem entregues, uma ordem de venda deve ser feita, se não, o pedido não pode sair do estoque. | Entregas de itens do estoque | Estoquista e Vendas |
| ES003 | Cléber precisa registrar a chegada de novos pedidos no armazém. | Para que sejam cadastrados itens no estoque, o armazém deve ser configurado e uma compra deve ser realizada. | Registro de itens recém-chegados | Estoquista e Compras |
| ES004 | Cléber precisa analisar o estoque para emitir mais ordens de compras. | Para que o estoque seja analisado, é necessário que todas as entradas e saídas de pedidos sejam devidamente registradas. | Análise de relatório | Estoquista |
| ES005 | Cléber quer deletar um item do estoque. | Não é possível o delete de nenhum item do estoque, sem uma ordem de venda. | Delete de um item | Vendas |

*Achei mais fácil me basear em user stories para criar as regras.*

Diagramas

![ES1.png](..doc/Imagens/ES1.png)

![ES2.png](Ponderada%20do%20Afonsinho%20s2%209d073f8ed06c419b9cdc938aa0f0c7a4/ES2.png)

![ES3.png](Ponderada%20do%20Afonsinho%20s2%209d073f8ed06c419b9cdc938aa0f0c7a4/ES3.png)

![ES4.png](Ponderada%20do%20Afonsinho%20s2%209d073f8ed06c419b9cdc938aa0f0c7a4/ES4.png)

![ES5.png](Ponderada%20do%20Afonsinho%20s2%209d073f8ed06c419b9cdc938aa0f0c7a4/ES5.png)
