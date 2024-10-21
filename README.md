# Aplicativo de Rastreamento de Despesas em Asp.Net Core MVC 🧾💰

[LinkedIn - Pedro H. Garbim](https://www.linkedin.com/in/pedrohgarbim/)

## Sobre o Projeto / About the Project 
An Expense Tracker App developed in Asp.Net Core MVC using SyncFusion components. This project is a comprehensive Asp.Net Core application that demonstrates how to build an enterprise-level application from scratch. It includes:

- 📊 Implementation of CRUD operations for Categories and Transactions.
- 📋 Grid with paging and sorting.
- 📈 Dashboard with chart elements.
- 📁 Side menu with a dockable sidebar for easy navigation.

Um aplicativo de rastreamento de despesas desenvolvido em Asp.Net Core MVC utilizando componentes SyncFusion. Este projeto é uma aplicação Asp.Net Core completa que demonstra como construir uma aplicação empresarial do zero. Inclui:

- 📊 Implementação de operações CRUD para Categorias e Transações.
- 📋 Grade com paginação e ordenação.
- 📈 Dashboard com elementos gráficos.
- 📁 Menu lateral com barra lateral encaixável para fácil navegação.

An Expense Tracker App developed in Asp.Net Core MVC using SyncFusion components. This project is a comprehensive Asp.Net Core application that demonstrates how to build an enterprise-level application from scratch.

## Rastreamento de Despesas / Expense Tracker

### Tecnologias Usadas / Technologies Used:

- 💻 C#
- 🗄️ SQL Server
- 🌐 .NET MVC

## Visão Geral do Projeto / Project Overview

- **Renda Total (Total Income):** Mostra a quantidade total de renda registrada.
- **Despesa Total (Total Expense):** Exibe o total de despesas.
- **Saldo (Balance):** Mostra o saldo disponível, calculado pela diferença entre a renda e as despesas.
- **Despesa por Categoria (Expense By Category):** Um gráfico de rosca que categoriza as despesas em diferentes áreas, como Educação, Entretenimento, Compras, etc.
- **Renda vs Despesa (Income vs Expense):** Um gráfico de linha que compara a renda e as despesas ao longo de diferentes datas.
- **Transações Recentes (Recent Transactions):** Uma lista detalhada das transações mais recentes, incluindo a categoria, data e valor (positivo para renda, negativo para despesa).
- **Espaço para Widget:** Um espaço reservado para adicionar futuros widgets ou componentes adicionais.

![Dashboard](https://github.com/user-attachments/assets/dc24e1af-0f96-47f8-b7f3-054aa1a2c66d)

## Barra Lateral / Sidebar

A barra lateral serve como um menu de navegação no aplicativo Wallet App, permitindo que os usuários acessem diferentes seções:

- 📊 **Dashboard:** Fornece uma visão geral das finanças, incluindo gráficos e transações recentes.
- 🗂️ **Categorias:** Gerenciar as categorias de receitas e despesas para uma melhor organização financeira.
- 💳 **Transações:** Visualizar, adicionar ou editar transações financeiras.

A barra lateral pode ser minimizada para ocupar menos espaço na tela, proporcionando mais área para o conteúdo principal do aplicativo.

![Barra Lateral](https://github.com/user-attachments/assets/1ef9ad84-f131-4fb5-9176-913eee218051)

## Categorias / Categories

A tela de categorias exibe todas as categorias criadas pelo usuário, mostrando:

- 📝 **Nome:** O nome da categoria.
- 📊 **Tipo:** Indica se é "Receita" ou "Despesa".
- ✏️ **Editar:** Modificar a categoria.
- 🗑️ **Apagar:** Remover a categoria.

As categorias são paginadas, com até 10 exibidas por página, simplificando a navegação e organização.

![Categorias](https://github.com/user-attachments/assets/5818516b-e508-4a2f-9f6b-cbdc7bde745d)

### Criar uma Nova Categoria / Create a New Category

Permite aos usuários adicionar ou editar categorias, especificando:

- 🛠️ **Tipo:** Escolher se a categoria é "Despesa" ou "Receita".
- 📝 **Título:** Inserir o nome da categoria.
- 🖼️ **Ícone:** Selecionar um ícone para identificação visual.
- 💾 **Enviar:** Salvar a nova categoria.

![Criar Categoria](https://github.com/user-attachments/assets/34e7632e-804d-4ea4-9a02-83055c2ca5d9)

## Transações / Transactions

A tela "Transações" lista todas as transações registradas, incluindo:

- 🗂️ **Categoria:** A qual categoria a transação pertence.
- 📅 **Data:** Quando a transação ocorreu.
- 💵 **Quantia:** O valor da transação (positivo para receita, negativo para despesa).
- ✏️ **Editar / 🗑️ Apagar:** Modificar ou remover transações.

Inclui um botão "+ Nova Transação" para adicionar novas entradas. As transações são paginadas, com até 10 por página.

![Transações](https://github.com/user-attachments/assets/43df6510-175f-48d9-b42a-03cd5b136970)

### Criar uma Nova Transação / Create a New Transaction

Os usuários podem adicionar uma nova transação preenchendo:

- 📅 **Data:** Quando a transação ocorreu.
- 🗂️ **Categoria:** Selecionar a partir de categorias previamente definidas.
- 💵 **Quantia:** Inserir o valor (positivo para receita, negativo para despesa).
- 📝 **Nota:** Adicionar quaisquer detalhes adicionais.

Clique em "Enviar" para salvar a transação.

![Criar Transação](https://github.com/user-attachments/assets/9d08aa4c-7c6b-4a68-b1c4-45d93fdb0fd1)

## SQL Server - Tabelas de Categorias e Transações

### Categorias

![Tabela de Categorias](https://github.com/user-attachments/assets/5511f748-253c-47f6-ba44-4210ec773357)

### Transações

![Tabela de Transações](https://github.com/user-attachments/assets/0693bf51-b255-4b7f-a396-dff8b2b8a556)
