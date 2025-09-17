# 🖥️ Projeto Banca de Jornal - Repositório do Front-end

Este é o repositório para a aplicação cliente (interface do usuário) do sistema de controle financeiro da banca de jornal.

## 📖 Tabela de Conteúdos

- [Visão Geral](#-visão-geral)
- [Tecnologias e Ferramentas](#-tecnologias-e-ferramentas)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação e Execução](#-instalação-e-execução)
- [Scripts Disponíveis](#-scripts-disponíveis)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Integração com o Back-end](#-integração-com-o-back-end)
- [Guia de Estilo de Código](#-guia-de-estilo-de-código)

## 🎯 Visão Geral

Descreva o que esta aplicação faz. (Ex: "Interface web para que o dono da banca possa registrar vendas, controlar estoque e visualizar relatórios financeiros.").

## 🛠️ Tecnologias e Ferramentas

- **Framework:** (Ex: React, Vue, Angular)
- **Linguagem:** (Ex: TypeScript)
- **Estilização:** (Ex: Styled-Components, Tailwind CSS)
- **Gerenciador de Estado:** (Ex: Redux, Zustand, Vuex)
- **Gerenciador de Pacotes:** (Ex: npm, yarn)

## ✅ Pré-requisitos

- [Node.js](https://nodejs.org/) (versão X.X.X ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## 🚀 Instalação e Execução

1.  **Clone o repositório:** `git clone ...`
2.  **Acesse a pasta do projeto:** `cd nome-do-repo-frontend`
3.  **Instale as dependências:**
    ```bash
    npm install
    ```
4.  **Execute a aplicação em modo de desenvolvimento:**
    ```bash
    npm start
    ```
5.  A aplicação estará disponível em `http://localhost:3000`.

## ✨ Scripts Disponíveis

- `npm start`: Roda a aplicação em modo de desenvolvimento.
- `npm run build`: Gera a versão de produção da aplicação.
- `npm test`: Executa os testes unitários.
- `npm run lint`: Analisa o código em busca de erros de padrão.

## 📁 Estrutura de Pastas

- `src/`: Código fonte da aplicação.
  - `components/`: Componentes reutilizáveis.
  - `pages/` ou `views/`: Páginas da aplicação.
  - `services/` ou `api/`: Lógica para se comunicar com o back-end.
  - `store/` ou `context/`: Gerenciamento de estado global.
  - `assets/`: Imagens, fontes, etc.

## 🔗 Integração com o Back-end

A URL base da API do back-end é configurada no arquivo `.env`. Crie um arquivo `.env.local` na raiz do projeto com a seguinte variável:

`REACT_APP_API_URL=http://localhost:8080/api`

## 🎨 Guia de Estilo de Código

Este projeto usa [ESLint](https://eslint.org/) e [Prettier](https://prettier.io/) para garantir a consistência do código. Recomenda-se instalar as extensões correspondentes no seu editor.
