📄 Blog Fake - JavaScript

Projeto simples desenvolvido com JavaScript puro para simular um sistema de blog, consumindo uma API externa.

🚀 Funcionalidades
📥 Buscar e listar posts de uma API
➕ Adicionar novos posts
🔄 Atualizar automaticamente a lista após inserção
⚠️ Validação de campos obrigatórios
🧠 Como funciona

O projeto utiliza a API pública:

👉 http://jsonplaceholder.typicode.com/posts

🔹 Fluxo:

Ao carregar a página:
Executa readPosts()
Busca os posts da API
Exibe na tela
Ao clicar em Inserir:
Captura título e conteúdo
Valida os campos
Envia um POST para a API
Limpa os inputs
Atualiza a lista de posts

🛠️ Tecnologias utilizadas
HTML5
CSS3
JavaScript (Vanilla JS)
Fetch API (requisições HTTP)

📂 Estrutura do projeto
/projeto
│
├── index.html
├── assets
│   ├── css
│   │   └── style.css
│   └── js
│       └── script.js

📌 Principais funções
🔹 readPosts()
Busca os posts da API
Renderiza na tela
Mostra mensagem de carregamento
🔹 addNewPost(title, body)
Envia novo post via POST
Limpa os campos
Atualiza a lista
⚠️ Observação importante

A API utilizada (JSONPlaceholder) é apenas para testes:

👉 Os posts criados não são salvos de verdade
👉 Eles não persistem após atualização da página

▶️ Como rodar o projeto
Baixe os arquivos
Abra o index.html no navegador

Ou use uma extensão como Live Server no VS Code.

💡 Possíveis melhorias
✏️ Editar posts
❌ Deletar posts
🎨 Melhorar o design
🔍 Paginação ou busca
💾 Integrar com API real
📷 Preview

Simula um pequeno blog com:

formulário de criação
listagem dinâmica de posts
