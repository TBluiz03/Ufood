# 🍕Ufood 

# Integrantes do grupo
•Leonardo Honorato Pereira

•Jonathan Ishida

•Luiz Felipe

•Luiz Otávio




# Scrum Master
-Leonardo Honorato Pereira


# Objetivo
Aplicação destinada à verificação e compra de alimentos fornecidos pela cantina da universidade, O projeto visa reduzir o tempo de espera nas filas, 
aumentar a eficiência das vendas e automatizar a gestão de pedidos para o estabelecimento.

# Problema 

No horário do intervalo, a maioria dos estudantes comparece a cantina para consumo 
dos alimentos fornecidos , por conta disso, há uma grande fila de espera fazendo com que o estudante perca boa parte do intervalo causando insatisfação. 
Pela alta demanda, os funcionários precisam  anotar pedidos rapidamente, podendo ocorrer problemas na separação dos pedidos.
Pode ocorre também:
•alguns produtos acabam enquanto estudantes ainda estão na fila;
•alunos não sabem antecipadamente quais produtos estão disponíveis;
•pagamentos são realizados somente no momento da retirada.

# Usuários
👳- Funcionario
👨- Cliente
👨‍💼- Gerente

# Funcionalidades Iniciais

1. pode ter uma pagina num app ou site para os alunos mostrando o cardápio e o que tem disponível 
2. ele pode usar seu RA para "cadastrar" e assim fazer o pedido selecionando
3. recebe no "painel de administrador" no qual ele pode ver os pedidos recebidos e poder alterar caso algum produto apareça novamente em estoque 
4. por uma tela ou chamando pelo RA do aluno
5. aparecer como "acabou o estoque" e que não seja possível selecionar
6. o aluno pode mostrar o comprovante e seu numero no pedido pelo celular
7. depois do pagamento não será possível cancelar
8. pode ter um status de "enviado | preparando | Pronto"
9. nome do produto , código do produto e preço 
10. nome do produto , código do produto , preço e comprovante


# Criando as primeiras Histórias de Usuário

1-Como cliente quero visualizar apenas os produtos disponíveis pela cantina, para assim não perder tempo vendo produtos já esgotados.

2-Como cliente quero fazer o pedido antecipadamente, para que não seja necessário esperar na fila.
3-Como cliente quero ver todas as formas de pagamento disponíveis, como cartão, dinheiro, pix, para saber se posso pagar com a opção que tenho no momento.

4-Como funcionário quero ser notificado pelo aplicativo através de um sinal sonoro, assim que um novo pedido for criado, para que não haja atrasos.

5-Como funcionário quero que o sistema coloque em ordem de cronológica os pedidos, para que assim não haja reclamações por atraso

6-Como funcionário quero que o sistema atualize e me avise em uma aba de notificações quais produtos estão esgotados e precisam ser repostos na cantina

7-Como gerente da cantina quero que o sistema me mostre em um ranking quais produtos vendem mais e quais vendem menos para saber em quais devo investir mais ou menos

8- Como cliente quero poder opinar sobre produtos aos quais eu comprei para que o gerente possa manter ou retirar do cardápio trocando por outros produtos melhores

9- Como funcionário quero uma forma fácil de comprovar que determinado pedido é do cliente em questão evitando entrega de pedidos errados.

10- Como gerente quero de ver um relatório financeiro para saber o faturamento, lucro, custos etc.

# Critérios de Aceitação e MVP: Menor versão do produto

1-Como cliente quero visualizar apenas os produtos disponíveis pela cantina, para assim não perder tempo vendo produtos já esgotados.

-Os produtos disponíveis aparecem primeiro no aplicativo e os esgotados em último lugar, assim o cliente não perde tempo rolando a tela procurando um produto já esgotado
-Os produtos devem ter nome e preço
-Os clientes podem visualizar o produtos mesmo sem ter uma conta
-Os produtos indisponíveis aparecem em cinza com uma marcação em vermelho escrito: "ESGOTADO", enquanto os produtos disponíveis aparecem com a coloração padrão da foto do produto

2-Como cliente quero fazer o pedido antecipadamente, para que não seja necessário esperar na fila.

•deve ser exibido os produtos disponíveis
•Cada produto deve ter nome e preço
•O cliente deve ser notificado assim que o produto estiver pronto
•O cliente deve visualizar os produtos disponíveis e não disponíveis
•Assim que o cliente efetuar o pagamento, a cantina deve ser notificada para agilizar o processo.

3-Como cliente quero ver todas as formas de pagamento disponíveis, como cartão, dinheiro, pix, para saber se posso pagar com a opção que tenho no momento.

- As formas de pagamento aparecem com nome e preço logo abaixo, indicando se determinada opção tem desconto ou juros, exemplo: em dinheiro o valor tem um determinado desconto, no cartão teria um acréscimo.
- Caso uma opção de pagamento não esteja sendo aceita pro algum motivo, como problemas de conexão com o sistema bancário, essa opção deve ser ocultada do usuário

4-Como funcionário quero ser notificado pelo aplicativo através de um sinal sonoro, assim que um novo pedido for criado, para que não haja atrasos.

•A notificação deve tocar assim que um novo pedido for emitido
•Deve aparecer uma mensagem com o nome do cliente, RA e o pedido
•O funcionário deve atualizar no app o status do produto para "Em Preparo".
•O funcionário deve atualizar o cliente sobre o status do pedido.
•O cliente deve ser notificado assim que o produto estiver pronto

#Decomposição do trabalho
História: Visualizar produtos disponíveis.
criar estrutura da entidade Produto;
criar migration da tabela de produtos;
criar endpoint para listar produtos;
criar interface de listagem;
integrar frontend com o API

História: Visualizar pagamentos disponíveis.
criar estrutura da entidade Pagamentos;
criar migration da tabela de pagamentos;
criar endpoint para listar pagamentos;
criar interface de listagem;
integrar frontend com a API




