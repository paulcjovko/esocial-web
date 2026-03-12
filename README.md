# eSocial Web Clone (Projeto Educacional)

Simulação educacional do **eSocial Web Geral**, desenvolvida para estudo de arquitetura de sistemas web, fluxos administrativos e organização de eventos trabalhistas.

⚠️ **Aviso:**
Este projeto **não possui ligação com o sistema oficial do governo** e não envia dados reais ao eSocial.
O objetivo é apenas **reproduzir a experiência de uso para aprendizado técnico**.

---

# 📌 Objetivo do Projeto

Este projeto foi criado para estudar:

* arquitetura de aplicações web
* sistemas administrativos corporativos
* fluxo de eventos do eSocial
* integração entre frontend e backend
* organização de interfaces complexas

A aplicação simula as principais funcionalidades do portal eSocial para fins educacionais.

---

# 🧱 Tecnologias Utilizadas

Frontend

* React
* Vite
* TypeScript
* Material UI

Backend

* Node.js
* Express

Banco de dados

* SQLite / Supabase

Deploy

* Vercel (frontend)
* Render ou Replit (backend)

---

# 🖥️ Funcionalidades

### 🔐 Login Simulado

Sistema de autenticação fictícia utilizando CPF e senha.

### 📊 Dashboard

Painel administrativo com indicadores:

* total de trabalhadores cadastrados
* eventos enviados
* eventos pendentes
* histórico recente de atividades

### 🏢 Cadastro de Empregadores

Permite cadastrar informações da empresa:

* CNPJ
* razão social
* natureza jurídica
* classificação tributária
* dados de contato

### 👨‍💼 Gestão de Trabalhadores

Cadastro e gerenciamento de funcionários contendo:

* nome completo
* CPF
* data de nascimento
* cargo
* salário
* data de admissão
* tipo de vínculo

Funções disponíveis:

* adicionar
* editar
* excluir
* visualizar

### 📄 Simulação de Eventos eSocial

Eventos suportados:

* S-1000 — Informações do empregador
* S-1005 — Estabelecimento
* S-2200 — Admissão de trabalhador
* S-2300 — Trabalhador sem vínculo
* S-3000 — Exclusão de evento

Cada evento gera um registro no sistema com:

* número de protocolo
* data de envio
* status do evento

### 📑 Histórico de Eventos

Tabela com:

* ID do evento
* tipo de evento
* trabalhador associado
* data de envio
* status

### 📈 Relatórios

Relatórios administrativos:

* eventos por período
* trabalhadores cadastrados
* histórico de envios

---

# 🗂️ Estrutura do Projeto

frontend

src
components
pages
services
hooks
layouts

backend

routes
controllers
models
database

---

# 🚀 Como Rodar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/paulcjovko/esocial-clone.git
```

### 2️⃣ Entrar no diretório

```bash
cd esocial-clone
```

### 3️⃣ Instalar dependências

```bash
npm install
```

### 4️⃣ Rodar o servidor

```bash
npm run dev
```

O sistema estará disponível em:

```
http://localhost:5173
```

---

# 🌐 Deploy

Frontend pode ser publicado facilmente no **Vercel**.

Backend pode ser hospedado em:

* Render
* Replit
* Railway

---

# 📚 Objetivo Educacional

Este projeto foi criado para aprendizado nas áreas de:

* desenvolvimento full stack
* modelagem de sistemas administrativos
* simulação de integrações governamentais

Não substitui o sistema oficial do governo.

---

# ⚖️ Aviso Legal

O **eSocial** é um sistema oficial do Governo Federal Brasileiro.

Este projeto:

* não utiliza APIs oficiais
* não envia dados ao governo
* não coleta informações reais

Todo o funcionamento é **simulado para fins educacionais**.

---

# 👨‍💻 Autor

Paulo Cjovko

Projeto desenvolvido para estudo de sistemas administrativos web e arquitetura de aplicações modernas.
