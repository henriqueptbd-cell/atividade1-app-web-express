# Atividade 1 - App Web com Express

Aplicação web desenvolvida com Node.js e Express para servir páginas HTML estáticas,
como atividade avaliativa da disciplina de Desenvolvimento Web I — Fatec DSM.

## 🔗 Deploy

hospedagem pelo Render
https://atividade1-app-web-express.onrender.com/

## 📁 Estrutura do Projeto
```
app/
├── server.js
├── package.json
├── .env
└── public/
    ├── assets/
    │   ├── css/
    │   │   └── main.css
    │   └── img/
    └── pages/
        ├── index.html
        ├── login.html
        ├── cadastro.html
        └── 404.html
```

## 🚀 Como rodar localmente

**Pré-requisitos:** Node.js instalado.
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/atividade1-app-web-express

# Acesse a pasta
cd atividade1-app-web-express

# Instale as dependências
npm install

# Inicie o servidor
node server.js
```

Acesse em: `http://localhost:3001`

## 📄 Páginas

| Rota | Página |
|------|--------|
| `/` | Página inicial com informações sobre o curso DSM |
| `/login` | Formulário de login |
| `/cadastro` | Formulário de cadastro |
| `*` | Página de erro 404 |

## 🛠️ Tecnologias

- Node.js
- Express
- HTML5

## 👨‍💻 Autor

Henrique — 1º Semestre DSM · Fatec
