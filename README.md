# 🤖 Chatbot Astro

Um mini chatbot/widget construído com **Astro** + **Tailwind CSS**, que pode ser embedado em qualquer site com facilidade. Ideal para testes de interface, coleta de dados e integração com WhatsApp.

## 🔗 Live Demo

Acesse o projeto ao vivo em:
👉 [https://chatbot-astro.vercel.app](https://chatbot-astro.vercel.app)

---

## 📦 Tecnologias Utilizadas

* [Astro](https://astro.build/)
* [Tailwind CSS](https://tailwindcss.com/)
* [Vite](https://vitejs.dev/)
* [TypeScript](https://www.typescriptlang.org/)

---

## 🚀 Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/carlospinellowork/chatbot-astro.git
cd chatbot-astro

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

---

## 🌐 Como Embedar em Outro Site

Você pode incorporar este chatbot em qualquer site colando o código abaixo no HTML do seu projeto:

```html
<div style="position: fixed; bottom: 20px; right: 20px; z-index: 9999;">
  <iframe src="https://chatbot-astro.vercel.app" style="width: 100%; max-width: 700px; height: 400px; border: none;"></iframe>
</div>
```

Esse widget será exibido no canto inferior direito da tela.

---

## 📁 Estrutura de Pastas

```bash
📁 src
 ┣ 📁 components     # Componentes reutilizáveis
 ┣ 📁 layouts        # Layouts do Astro
 ┣ 📁 pages          # Páginas do projeto
 ┗ 📁 styles         # Estilos globais
```

---

## 🛠️ Melhorias Futuras

* Integração com API do WhatsApp
* Respostas automáticas com IA
* Histórico de mensagens
* Suporte a temas (dark/light)
* Integração com backend

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.

---

Feito com 💙 por [Carlos Eduardo](https://github.com/carlospinellowork)
