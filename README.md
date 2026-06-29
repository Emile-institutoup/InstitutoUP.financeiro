# Instituto Up — Sistema Financeiro

## Como publicar no Railway via GitHub

### 1. Criar repositório no GitHub
1. Acesse github.com e faça login
2. Clique no "+" no canto superior direito → "New repository"
3. Nome: `instituto-up-financeiro`
4. Deixe como "Public"
5. Clique em "Create repository"

### 2. Subir os arquivos no GitHub
1. Na página do repositório criado, clique em "uploading an existing file"
2. Arraste TODOS os arquivos desta pasta para a área indicada
3. Clique em "Commit changes"

### 3. Conectar Railway ao GitHub
1. Acesse railway.app
2. Clique em "New Project" → "GitHub Repository"
3. Selecione o repositório "instituto-up-financeiro"
4. Railway vai detectar automaticamente e publicar

### 4. Configurar domínio
1. No Railway, clique no serviço criado
2. Vá em "Settings" → "Networking" → "Generate Domain"
3. Seu link estará disponível (ex: instituto-up.railway.app)

## Estrutura do projeto
```
instituto-up-railway/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx       ← Sistema completo
│   └── index.js
├── package.json
├── railway.json
├── Procfile
└── README.md
```
