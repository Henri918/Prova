# 🚀 skyNode Solutions - Server Monitor

Sistema de monitoramento em tempo real para servidores, desenvolvido como projeto de estudo de Desenvolvimento de Sistemas (2º ano).

## 🛠️ Tecnologias Utilizadas
- **Back-end:** Node.js & Express
- **Front-end:** HTML Semântico, CSS Grid/Flexbox e JavaScript (OOP)
- **Comunicação:** Fetch API (JSON)

## 📋 Árvore DOM do Projeto
A estrutura hierárquica da interface segue o padrão abaixo:

\`\`\`text
Document
┗━━ <html>
    ┣━━ <head> (Metadados e CSS)
    ┗━━ <body>
        ┣━━ <header> (Título skyNode)
        ┣━━ <main>
        ┃   ┗━━ <section class="grid-container">
        ┃       ┣━━ <article id="card-cpu">
        ┃       ┣━━ <article id="card-ram">
        ┃       ┗━━ <article id="card-temp">
        ┣━━ <footer> (Rodapé de status)
        ┗━━ <script> (Lógica de Objetos)
\`\`\`

## 🚀 Como Rodar o Projeto

Siga os passos abaixo para executar o sistema na sua máquina:

1. **Clonar o repositório:**
   \`\`\`bash
   git clone <link-do-seu-repositorio>
   \`\`\`

2. **Instalar as dependências:**
   (Isso vai ler o package.json e criar a pasta node_modules que ignoramos no git)
   \`\`\`bash
   npm install
   \`\`\`

3. **Iniciar o servidor:**
   \`\`\`bash
   node server.js
   \`\`\`

4. **Acessar o Dashboard:**
   Abra o seu navegador e vá para: \`http://localhost:3000\`

---
*Desenvolvido para fins educacionais - skyNode Solutions*