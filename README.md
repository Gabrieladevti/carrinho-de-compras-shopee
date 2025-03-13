# Carrinho de Compras Shopee

**Carrinho de Compras Shopee** é uma aplicação simples de carrinho de compras inspirada na plataforma Shopee. Este projeto permite que os usuários adicionem produtos ao carrinho, removam itens, visualizem o total da compra e mantenham o carrinho persistente entre sessões utilizando o armazenamento local.

## Funcionalidades

- **Adicionar produtos ao carrinho**: Permite que os usuários adicionem itens ao carrinho com um simples clique.
- **Remover produtos do carrinho**: Os itens podem ser removidos do carrinho facilmente.
- **Visualizar o total da compra**: O valor total da compra é calculado automaticamente conforme os produtos são adicionados ou removidos.
- **Persistência de dados**: O carrinho de compras é armazenado no **localStorage**, garantindo que os itens permaneçam salvos mesmo após o recarregamento da página.

## Tecnologias Utilizadas

- **JavaScript**: Para manipulação do DOM, gerenciamento do carrinho e cálculo do total de compras.
- **HTML**: Para estruturar a página da aplicação.
- **CSS**: Para estilizar e deixar o layout da aplicação responsivo.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **index.html**: Página principal, onde os produtos são exibidos e o carrinho de compras é mostrado.
- **styles.css**: Arquivo responsável pela estilização da página e layout.
- **app.js**: Lógica do JavaScript, responsável por adicionar, remover itens do carrinho e calcular o total.
- **storage.js**: Gerencia o armazenamento e recuperação de dados no **localStorage**.
