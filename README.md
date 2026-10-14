# 🍔 DevBite — Interface de Sistema de Pedidos Tech

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

O **DevBite** é uma interface web para um sistema de pedidos de uma lanchonete temática voltada para profissionais da área de tecnologia. O projeto foi desenvolvido focando em **semântica HTML5**, **layout responsivo com CSS3 (Flexbox e Grid)** e **preparação estrutural para futura integração com JavaScript**.

---

## 🎨 Identidade Visual e Design

A interface foi projetada utilizando uma estética **Dark Mode Tech**, combinando tons escuros inspirados em editores de código com cores quentes alimentares:

* **Carvão / Café Escuro:** Cores de fundo (`#1c1917`, `#292524`).
* **Amarelo Cheddar:** Cor primária de destaque e botões (`#f59e0b`).
* **Vermelho Pimenta:** Destaque para ações destrutivas e alertas (`#ef4444`).
* **Tipografia:** Combinação de fontes modernas do sistema com fonte *Monospace* nos títulos, preços e elementos da marca.

---

## 📱 Telas do Sistema

O projeto é composto por **3 telas interligadas** por um menu de navegação responsivo:

### 1. Cardápio (`index.html`)
* **Navegação Superior:** Logo e links funcionais para todas as áreas do site com indicador de itens no carrinho.
* **Barra de Categorias:** Filtros visuais por tipo de produto (*Burgers*, *Bebidas*, *Sobremesas*).
* **Vitrine de Produtos:** Grade responsiva (CSS Grid) exibindo os itens do cardápio com imagem, título, descrição, preço e botão "Adicionar".

### 2. Finalização de Pedido (`checkout.html`)
* **Tabela de Carrinho:** Exibição dos itens selecionados, quantidade, subtotal e valor total acumulado.
* **Formulário de Entrega:** Coleta de dados do cliente (Nome, Endereço, Telefone) com validações nativas do HTML.
* **Forma de Pagamento:** Opções via seletores de rádio (*Pix*, *Cartão*, *Dinheiro*).

### 3. Painel Administrativo (`admin.html`)
* **Menu Diferenciado:** Atalhos para ações administrativas do back-office.
* **Cadastro de Produtos:** Formulário completo para inclusão de novos itens no cardápio (Nome, Categoria, Preço, URL da imagem e Descrição).
* **Gestão de Pedidos Recentes:** Tabela com histórico de vendas e *badges* coloridas para indicação de status (*Em Preparo*, *Saiu p/ Entrega*, *Concluído*).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Uso correto de tags estruturais (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<form>`, `<fieldset>`).
- **CSS3:**
  - **Variáveis CSS (`:root`):** Centralização e fácil manutenção de paleta de cores e fontes.
  - **CSS Grid:** Utilizado nas grades de produtos e na divisão de colunas do checkout.
  - **Flexbox:** Utilizado no cabeçalho, navegação, rodapé e componentes internos dos cards.
  - **Media Queries:** Garantia de responsividade para dispositivos móveis, tablets e desktops.

---

## 📐 Estrutura de Arquivos

```text
devbite/
├── index.html        # Tela Principal - Cardápio
├── checkout.html     # Tela de Checkout e Carrinho
├── admin.html        # Tela de Gerenciamento / Admin
├── style.css         # Estilos globais e responsividade
└── README.md         # Documentação do projeto
