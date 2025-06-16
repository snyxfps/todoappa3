---

# 📋 Projeto TodoApp - A3 Vue.js (Vite)

## 🎯 Descrição

Este é um sistema de gerenciamento de tarefas (TodoApp) com agenda e controle de acesso via login/cadastro, desenvolvido como parte da atividade A3 da disciplina de Desenvolvimento Web.

O sistema foi feito em **Vue 3 + Vite**, com armazenamento de dados no **LocalStorage do navegador**, sem necessidade de backend.

---

## ✅ Funcionalidades

* **Cadastro de usuários**
* **Login com validação**
* **Proteção de rotas** (acesso só após login)
* **Botão "Sair"** que encerra a sessão
* **Criação de tarefas com data e hora**
* **Agrupamento de tarefas por dia no estilo calendário**
* **Armazenamento local de dados** (não precisa de banco de dados externo)

---

## 🚪 Fluxo de navegação

1. **Tela inicial (Login)**
   ➡️ Usuário só consegue acessar outras páginas depois de logado.

2. **Tela de Cadastro**
   ➡️ Novo usuário pode criar uma conta.

3. **Após Login**
   ➡️ Acesso liberado às abas:

   * **Agenda:** Criar, listar, excluir e concluir tarefas, com data/hora por dia.
   * **Sobre:** Informações sobre o projeto.
   * **Contato:** Formulário de contato fictício.

4. **Botão Sair**
   ➡️ Faz o logout e bloqueia novamente o acesso.

---

## 🗄️ Onde os dados ficam salvos?

No **LocalStorage do navegador**:

| Nome da Chave    | O que guarda                           |
| ---------------- | -------------------------------------- |
| `usuarios`       | Lista de todos os usuários cadastrados |
| `usuarioLogado`  | Dados do usuário atualmente logado     |
| `tarefasPorData` | Tarefas organizadas por data           |

---

## 🛠️ Tecnologias usadas

* Vue 3
* Vite
* JavaScript
* HTML5 / CSS3

---

## 🚀 Como rodar o projeto

1. **Instalar dependências:**

```
npm install
```

2. **Rodar o projeto:**

```
npm run dev
```
---
