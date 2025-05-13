# 🍕 Página Única de Pizzaria

Bem-vindo ao repositório do projeto de **Página Única para uma Pizzaria**! Esta aplicação web tem como objetivo fornecer uma experiência simples e intuitiva para o usuário escolher, personalizar e finalizar seu pedido de pizza em uma única tela.

---

## 🧱 Estrutura Geral da Página

### 🔝 Cabeçalho (Header)
- Logo da pizzaria.
- Ícone de carrinho de compras com contador de itens.

### 🖼️ Corpo Principal (Main)
Lista de pizzas disponíveis, cada uma com:
- Imagem da pizza.
- Nome da pizza.
- Preço.
- Botão "Adicionar ao Carrinho".

---

## ⚙️ Funcionalidades Principais

### 📦 Modal do Carrinho (ao clicar no ícone do carrinho)
Exibe:
- **Listagem das pizzas selecionadas:**
  - Nome da pizza.
  - Quantidade com botão de `+` / `-`.
  - Preço unitário e subtotal.
  - Botão para remover item do carrinho.
  
- **Seção de entrega:**
  - Opções:
    - [ ] Retirada
    - [ ] Entrega
  - Se “Entrega” for selecionado:
    - Campo para inserir o endereço (input ou dropdown com endereços salvos).

- Botão **"Finalizar Pedido"**.

---

### 🔍 Modal de Detalhes da Pizza (ao clicar na imagem da pizza)
Exibe:
- Imagem maior da pizza.
- Descrição da pizza.
- Ingredientes base.
- Preço.
- Campo para selecionar **ingredientes adicionais** (checkboxes ou toggles).
- Campo para observações (opcional).
- Botão **"Adicionar ao Carrinho"**.

---

### ➕ Ingredientes Adicionais (ao adicionar pizza)
Permite:
- Visualizar lista de ingredientes extras com preços.
- Selecionar os adicionais (checkboxes ou toggles).
- Ver cálculo do novo valor total com os adicionais.
- Confirmar e adicionar a pizza personalizada ao carrinho.

---

## 🚀 Tecnologias que serão utilizadas
- **Frontend:** JavaScript
- **Estilização:** Tailwind CSS 
- **Gerenciamento de Estado:** React Context
- **Modais e Animações:** Framer Motion

---

