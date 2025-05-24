# 📺 Clone da Netflix

Este é um projeto de front-end desenvolvido com React, inspirado na interface da plataforma de streaming **Netflix**. O objetivo é praticar conceitos avançados de desenvolvimento web como componentes reutilizáveis, integração de player de vídeo, estilização dinâmica com `styled-components` e estruturação de código moderna.

## 🚀 Demonstração

[🔗 Acesse o projeto aqui (versão em produção via GitHub Pages)](https://seu-usuario.github.io/seu-repo)  
> *Substitua o link acima com a URL real do seu projeto*

---

## 🛠️ Tecnologias Utilizadas

- **React 18** – Biblioteca principal para construção da interface
- **Express** – Servidor opcional para simulação de backend (ex.: servir arquivos ou mocks)
- **Styled-components** – Estilização com CSS-in-JS
- **React HTML5 Video** – Player customizado de vídeos
- **React Scripts** – Ferramentas de build e desenvolvimento
- **Testing Library** – Testes automatizados com Jest

---

## 📦 Estrutura do Projeto

/public
/src
┣ /components
┣ /pages
┣ /assets
┣ App.js
┣ index.js

yaml
Copiar
Editar

---

## 🔧 Scripts Disponíveis

No diretório do projeto, você pode executar:

- `npm start` – Inicia o servidor de desenvolvimento
- `npm run build` – Cria a versão otimizada para produção
- `npm test` – Executa a suíte de testes
- `npm run eject` – Expõe as configurações do Create React App

---

## 🧪 Testes

Este projeto utiliza a **Testing Library** para realizar testes automatizados de componentes e interações. Para rodar os testes:

```bash
npm test
🌐 Deploy
O deploy pode ser feito diretamente no GitHub Pages com o pacote gh-pages. Para isso:

Instale a dependência:

bash
Copiar
Editar
npm install --save gh-pages
Adicione ao package.json:

json
Copiar
Editar
"homepage": "https://seu-usuario.github.io/seu-repo",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
Execute:

bash
Copiar
Editar
npm run deploy
