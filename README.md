## Expense-Tracker-App-in-Asp.Net-Core-MVC
## https://www.linkedin.com/in/pedrohgarbim/
### About the project / Sobre o projeto 
An Expense Tracker App developed in Asp.Net Core MVC using SyncFusion components, with a complete Asp.Net Core application that demonstrates how to build an enterprise application from scratch.
 Implementation of CRUD operations for the Category and Transaction grid, including paging and sorting, dashboard with chart elements, side menu with a dockable sidebar

 Aplicativo de rastreamento de despesas desenvolvido em Asp.Net Core MVC utilizando componentes SyncFusion.
Trata-se de uma aplicação Asp.Net Core completa que demonstra como construir uma aplicação empresarial do zero.
Pontos discutidos: Implementação de operações CRUD para a grade de Categorias e Transações, incluindo paginação e ordenação, dashboard com elementos de gráfico, menu lateral com barra lateral encaixável, entre outros.

## Expense Tracker /  Rastreamento de Despesas

### Technologies Used Tecnologias Usadas:

C#

SQL Server

.NET MVC

## Projeto / Project  
Total Income (Renda Total): Mostra a quantidade total de renda registrada.

Total Expense (Despesa Total): Exibe o total de despesas.

Balance (Saldo): Mostra o saldo disponível, calculado pela diferença entre a renda e as despesas.

Expense By Category (Despesa por Categoria): Um gráfico de rosca que categoriza as despesas em diferentes áreas, como Educação, Entretenimento, Compras, etc.

Income vs Expense (Renda vs Despesa): Um gráfico de linha que compara a renda e as despesas ao longo de diferentes datas.

Recent Transactions (Transações Recentes): Uma lista detalhada das transações mais recentes, incluindo a categoria, data e valor (positivo ou negativo, indicando receita ou despesa).

Widget Placeholder: Um espaço reservado para adicionar futuros widgets ou componentes adicionais.

![image](https://github.com/user-attachments/assets/4d5227d3-5157-4129-9e34-0d1a2f5b0c9b)

![image](https://github.com/user-attachments/assets/47f665a2-3d4f-4b91-a1bd-f8638cb3c507)

## Dashboard
![image](https://github.com/user-attachments/assets/dc24e1af-0f96-47f8-b7f3-054aa1a2c66d)
## Sidebar
A sidebar apresentada na imagem serve como um menu de navegação no aplicativo Wallet App. Ela permite ao usuário acessar diferentes seções do aplicativo, como:

Dashboard: Onde o usuário pode visualizar um resumo das suas finanças, incluindo gráficos e transações recentes.

Categories: Uma seção para gerenciar as categorias de despesas e receitas, organizando melhor as finanças.

Transactions: A área onde o usuário pode visualizar, adicionar ou editar transações financeiras.

Além disso, a sidebar tem uma funcionalidade que permite ser minimizada, reduzindo seu tamanho para ocupar menos espaço na tela, o que é útil para proporcionar mais área visual para o conteúdo principal do aplicativo.

![image](https://github.com/user-attachments/assets/1ef9ad84-f131-4fb5-9176-913eee218051)
![image](https://github.com/user-attachments/assets/e5c91970-484a-4509-b066-6334e3fa2cac)


## Categories 
A tela de categorias do aplicativo exibe todas as categorias que foram criadas pelo usuário. Cada categoria é listada com o seu nome, o tipo (se é uma "Income" - Receita ou "Expense" - Despesa), e há opções para editar ou apagar a categoria.

Nesta tela, as categorias são paginadas, com até 10 categorias sendo exibidas por página. Isso facilita a navegação e a organização das categorias, permitindo ao usuário gerenciar melhor suas finanças. Ao lado de cada categoria, ícones de edição (lápis) e exclusão (lixeira) estão disponíveis, permitindo modificações rápidas.

![image](https://github.com/user-attachments/assets/5818516b-e508-4a2f-9f6b-cbdc7bde745d)

## Categories - Create a new category / Add or Edit
A tela Create a New Category serve para Criar e editar as categorias, permite ao usuário adicionar uma nova categoria ao sistema. Nesta interface, o usuário pode:

Selecionar o Tipo de Categoria: O usuário pode escolher se a nova categoria será uma "Expense" (Despesa) ou "Income" (Receita) usando os botões de seleção no topo do formulário.
Título: O usuário deve inserir o nome da categoria no campo "Title".
Ícone: O usuário pode especificar um ícone para a categoria no campo "Icon". Este ícone ajuda a identificar visualmente a categoria.
Botão Submit: Após preencher as informações, o usuário pode clicar no botão "Submit" para salvar a nova categoria.
Essa tela simplifica o processo de criar e personalizar categorias, garantindo que o usuário possa organizar suas finanças de acordo com suas necessidades específicas.

![image](https://github.com/user-attachments/assets/34e7632e-804d-4ea4-9a02-83055c2ca5d9)

## Transactions 
 A tela de "Transactions" exibe todas as transações registradas no aplicativo. Cada transação é listada com os seguintes detalhes:

Category (Categoria): Mostra a categoria à qual a transação pertence, como Salário, Entretenimento, Compras, etc.

Date (Data): Exibe a data em que a transação foi realizada.

Amount (Quantia): Mostra o valor da transação, com um sinal positivo para receitas e negativo para despesas.

Actions (Ações): Disponibiliza ícones de edição (lápis) e exclusão (lixeira) ao lado de cada transação, permitindo que o usuário altere ou remova transações conforme necessário.

Além disso, a interface oferece um botão "+ New Transaction" para adicionar novas transações ao sistema. Assim como na tela de categorias, as transações são paginadas, permitindo uma visualização organizada e facilitando a navegação entre elas. Nesta página, são exibidos até 10 itens por página, facilitando o controle das finanças.

![image](https://github.com/user-attachments/assets/43df6510-175f-48d9-b42a-03cd5b136970)

## Create a new Transaction 
A tela "Create a New Transaction" permite ao usuário adicionar uma nova transação ao sistema. Nesta interface, o usuário deve preencher os seguintes campos:

Date (Data): O usuário seleciona a data em que a transação ocorreu.

Category (Categoria): O usuário escolhe a categoria à qual a transação pertence, a partir de uma lista de categorias previamente definidas.

Amount (Quantia): O usuário insere o valor da transação. O valor pode ser positivo (indicando receita) ou negativo (indicando despesa).

Note (Nota): O usuário pode adicionar uma nota ou descrição adicional para a transação.

Após preencher os campos, o usuário clica no botão "Submit" para salvar a transação. Esta tela simplifica o processo de adicionar transações, garantindo que todas as informações essenciais sejam capturadas de forma eficiente.

![image](https://github.com/user-attachments/assets/9d08aa4c-7c6b-4a68-b1c4-45d93fdb0fd1)

## Sql Server - Tabelas de Category e Transaction 
### Categories
![image](https://github.com/user-attachments/assets/5511f748-253c-47f6-ba44-4210ec773357)

### Transaction 
![image](https://github.com/user-attachments/assets/0693bf51-b255-4b7f-a396-dff8b2b8a556)

