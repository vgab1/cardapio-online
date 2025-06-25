# ☕ devCoffee - Cardápio Online para Cafeterias

Sistema de cardápio online para cafeterias e confeitarias, com carrinho de compras integrado e finalização de pedido via WhatsApp.

## 📋 Funcionalidades

- Exibição do cardápio com itens de comida e bebida
- Adição e remoção de itens do carrinho
- Cálculo automático do total do pedido
- Campo para preenchimento de endereço
- Verificação de horário de funcionamento (12h às 22h)
- Integração com WhatsApp para finalização do pedido
- Aviso visual se o restaurante está aberto ou fechado

---

## 🍽️ Itens do Cardápio

### Comidas

- Croissant
- Donuts
- Cookies
- Brownie
- Cheesecake
- Torta de Limão

### Bebidas

- Expresso
- Cappuccino
- Latte
- Sucos Naturais

---

## 💻 Tecnologias Utilizadas

- **HTML**
- **CSS (com classes utilitárias tipo Tailwind)**
- **JavaScript puro**
- **[Toastify JS](https://apvarun.github.io/toastify-js/)** (para notificações)
- **Integração com WhatsApp Web (via `wa.me`)**

---

## 📦 Estrutura do Projeto

- `index.html` – Estrutura da interface do cardápio
- `style.css` – Estilização dos componentes
- `script.js` – Toda a lógica de interação (carrinho, horário, envio via WhatsApp)

---

## ▶️ Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/vgab1/cardapio-online.git
   Abra o arquivo index.html no navegador.
   ```

Interaja com o cardápio, adicione itens ao carrinho e clique em Finalizar Pedido.

Preencha o endereço e finalize o pedido via WhatsApp.

```
📱 Finalização pelo WhatsApp
Os pedidos são enviados via link do WhatsApp com os dados do pedido e o endereço informado:
Você pode personalizar o número de destino trocando a variável phone.

🧑‍💻 Autor
Desenvolvido por Victor Gabriel (Gabriel)
```
