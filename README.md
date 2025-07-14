# 🐳 Aplicação Node.js com Docker e Testes Automatizados

Projeto simples de demonstração de uso de **Docker com Node.js e Express**.

---

## 🧾 Descrição

Este repositório contém um exemplo básico de aplicação **Node.js** rodando em um container **Docker**, além de um script de teste automatizado para validar o funcionamento do servidor.

---

## 📁 Estrutura

- `index.js` — Código fonte do servidor Express  
- `Dockerfile` — Define a imagem Docker da aplicação  
- `comandos.sh` — Script com comandos úteis para build, execução e teste dos containers  
- `test.sh` — Script de teste automatizado para verificar se o servidor está respondendo corretamente  
- `package.json` — Dependências e configurações do projeto Node.js  
- `.gitignore` — Arquivos e pastas ignorados pelo Git

---

## 🚀 Como Rodar

**Build e execução dos containers:**

- Constrói as imagens Docker (`app` e `test`)  
- Cria uma rede Docker  
- Sobe o servidor Node.js na porta `3000`  
- Executa o teste automatizado

**Acesse a aplicação:**  
[http://localhost:3000](http://localhost:3000)

---

## ✅ Testes

O script `test.sh` faz uma requisição HTTP para o servidor e valida se a resposta está correta.  
O resultado do teste será exibido no terminal.

---

## ⚙️ Requisitos

- Docker  
- Node.js (caso deseje rodar localmente sem Docker)

---

Desenvolvido com 💙 por Isabela
