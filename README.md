# Controle-de-Estoque
Sistema de controle de estoque de produtos, usando como exemplo uma loja de celulares.

DB_Estoque.oml contém banco de dados e regras de negócio do sistema.

FrontEnd.oml contém telas do sistema.

Sistema contém:

1 - CRUD de produtos. Os produtos podem ser cadastrados, listados e retirados do estoque. Também é possível configurar
    quantidade mínima em estoque para cada produto, dessa forma é possível ter mais controle para reposição.

2 - Gráfico de faturamento. Possui gráfico de faturamento mensal, exibido no dashboard com os dez produtos com maior saída 
    do mês, quantidades e valor total faturado.

3 - CRUD de tarefas. Tarefas podem ser cadastradas, listadas, marcadas como concluídas. Serão exibidas no dashboard as tarefas 
    pendentes.

4 - CRUD de clientes. Clientes podem ser cadastrados, listados e terem suas informações editadas quando necessário. Os dados 
    podem ser consultados e usados para entrar em contato através de e-mail e telefone.

5 - CRUD do time. Integrantes do time podem ser cadastrados e através de login e senha poderão ter acesso ao sistema de acordo 
    com permissão concedida.

6 - CRUD de fornecedores (Em implementação). Contém cadastro de fornecedores para possíveis consultas de seus contatos e 
    endereços.

7 - Mensagens (Em implementação). Mensagens de aviso para produtos em quantidade mínima e zerados, envio de mensagens para clientes, fornecedores e time.

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
