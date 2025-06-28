# Controle-de-Estoque
Sistema de controle de estoque de produtos, usando como exemplo uma loja de celulares.

DB_Estoque.oml : banco de dados e regras de negócio.

FrontEnd.oml  : Dashboard intuitivo para cadastro de entidades, visualização de tarefas pendentes, mensagens e gráfico de faturamento mensal.

Contém:

1 - CRUD de produtos. Também é possível configurar quantidade mínima em estoque para cada produto. Um email será disparado automáticamente quando a quantidade mínima for atingida e quanndo estiver zerado em estoque.

2 - CRUD de clientes. Os dados podem ser consultados e usados para entrar em contato através de e-mail e telefone.

3 - CRUD de fornecedores. Com finalidade de consulta para entrar em contato para pedidos e cotações.

4 - CRUD de tarefas. Ao cadastrar nova tarefa, por padrão a mesma receberá status pendente e serão exibidas no dashboard. O usuário poderá marcar a tarefa como concluída e automaticamente a remoção da tarefa é feita do dashboard. 

5 - CRUD do time. Integrantes do time podem ser cadastrados e através de login e senha poderão acessar o sistema. O acesso as funcionalidades é controlado por permissões de acesso. Usuários master terão mais permissões, como limpar a base de dados, por exemplo, entre outras.

6 - Gráfico de faturamento. A cada saída de produto, o seu respectivo valor é incrementado ao faturamento do mês. O total de faturamento mensal é exibido e um gráfico mostra   os dez produtos com maior saída e suas respectivas quantidades.

7 - Mensagens. Finalidade de comunicar através de email. Avisos para produtos em quantidade mínima e zerados, envio de mensagens para clientes, fornecedores e time.

Tecnologias e componentes utilizados:

- Javascript
- CSS
- Máscaras (CPF, telefone, moeda)
- Gráfico (Informa faturamento mensal, produtos e quantidade retirada por produto)
- Consumo de API (Api Cep)
- Upload de imagem
- Importação de planilha (cadastra de produtos contidos na planilha)
- Query SQL
- Filtros (filtros de busca)
- Tratamento de exceção
- Autenticação de usuário
- Controle de acesso
