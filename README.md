# 🌐 Fluker

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)]()
[![PythonAnywhere](https://img.shields.io/badge/deploy-pythonanywhere-blue)]()

Fluker é uma rede social em desenvolvimento criada por um grupo de amigos, com o objetivo de oferecer uma plataforma simples e interativa para **compartilhar postagens**, **conversar com amigos** e **acompanhar notificações em tempo real**.

🔗 **Acesse o projeto online:** [https://fluker.pythonanywhere.com](https://fluker.pythonanywhere.com)

---

## 📖 Visão Geral

O **Fluker** busca unir aprendizado prático em desenvolvimento web e diversão, criando uma experiência social moderna e leve.
Nosso foco está em **funcionalidades essenciais** de uma rede social, agora com **armazenamento em banco de dados SQLite**, garantindo mais confiabilidade e escalabilidade.

---

## 🚀 Funcionalidades

✅ **Sistema de postagens** — crie, e visualize postagens de outros usuários.
✅ **Notificações** — receba alertas sobre novas interações.
✅ **Chat integrado** — converse com outros usuários dentro da própria plataforma.
✅ **Autenticação de usuário** — login, logout e gerenciamento de sessão.
✅ **Interface intuitiva** — navegação simples e visual limpo.

*(Mais recursos em breve!)*

---

## 🧠 Tecnologias Utilizadas

* **Python** — linguagem principal do projeto
* **Flask** — framework web para rotas e APIs
* **React** — usado no front-end para componentes interativos e atualização dinâmica
* **HTML, CSS e JavaScript** — base da interface e integração com React
* **SQLite3** — banco de dados principal (usuários, postagens, mensagens, notificações)
* **PythonAnywhere** — hospedagem e deploy do projeto** — hospedagem e deploy do projeto

---

## 🗂️ Estrutura do Projeto

Organização do repositório:

```text
fluker/
├── app.py
├── db.py
├── README.md
├── requirements.txt
├── src/
│   ├── data/                   
│   │   ├── createDataBase.py
│   │   └── database.db
│   │
│   ├── pages/                   
│   │   ├── index.html
│   │   ├── createaccount.html
│   │   ├── feed.html
│   │   └── recoverypassword.html
│   │
│   └── static/                  
│       ├── css/
│       │   ├── styleLogin.css
│       │   ├── styleRecoverPassword.css
│       │   └── styleFeed.css
│       │
│       ├── scripts/
│       │   ├── reactPolling.js
│       │   └── script.js
│       │
│       └── images/
│           ├── coracao.png
│           ├── Logo-Fluker.png
│           ├── logo.png
│           ├── logo1.png
│           ├── Lupa.png
│           ├── perfil.jpg
│           ├── redheart.png
│           └── sino.png
│
└── .git/
```

---

## 📂 `src/data/`

Armazena todos os arquivos relacionados ao banco de dados SQLite do Fluker.

* **`database.db`** → contém todas as tabelas e dados do sistema
* **`createDataBase.py`** → script responsável por criar e estruturar o banco de dados SQLite (tabelas de usuários, posts, mensagens, notificações)

> Agora não são mais utilizados arquivos CSV. Todo armazenamento está centralizado em um único banco SQLite3, mais seguro e eficiente.

---

## 📂 `src/pages/`

Contém as **páginas HTML** que formam a interface visual da rede social.

* **`index.html`** → página inicial (login)
* **`createaccount.html`** → tela de cadastro
* **`feed.html`** → página principal com postagens
* **`recoverypassword.html`** → recuperação de senha

---

## 📂 `src/static/`

Armazena todos os arquivos estáticos entregues diretamente ao navegador.

### 📁 `css/`

Define o visual de cada página.

### 📁 `scripts/`

JavaScript de interação com o usuário e comunicação com o Flask.

### 📁 `images/`

Ícones e imagens usadas na interface.

---

## ⚙️ `.git/`

Pasta interna do Git com o histórico de commits e branches. Não deve ser modificada.

---

## 📅 Roadmap / Próximos Passos

🔹 Melhorias no sistema de perfil e personalização
🔹 Upload de imagens em postagens
🔹 Implementação de comentários e sistema de busca
🔹 Integração de WebSockets para chat e notificações em tempo real
🔹 Possível migração futura para PostgreSQL caso o projeto cresça

---

## 👥 Equipe de Desenvolvimento

* 👨‍💻 **Bernado** — Full-stack / Coordenação
* 👨‍💻 **Ruan** — Banco de Dados (SQLite) / Back-end principal
* 👨‍💻 **Lucas** — Lógica do sistema / Back-end
* 👨‍💻 **Pablo** — Front-end
* 👨‍💻 **Gabriel** — Front-end
