A ESTRUTURA DE PASTAS DO KITE :
KITE-CHAT/
│
├── frontend/                 # Tudo que roda no navegador
│   ├── public/              # Arquivos públicos (imagens, favicon, etc.)
│   ├── src/                 # Código-fonte principal do front
│   │   ├── assets/          # Imagens, fontes, etc.
│   │   ├── components/      # Componentes reutilizáveis
│   │   ├── pages/           # Páginas do site (Home, Login, etc.)
│   │   ├── App.vue / .js    # Componente principal (Vue ou React)
│   │   └── main.js          # Entrada principal do front
│   ├── index.html           # HTML base
│   └── vite.config.js       # Configuração do Vite ou Webpack
│
├── backend/                 # Tudo que roda no servidor
│   ├── app/                 # Código-fonte da API (controllers, rotas, etc.)
│   │   ├── routes/          # Rotas da API
│   │   ├── controllers/     # Lógica de cada rota
│   │   ├── models/          # Modelos do banco de dados
│   │   └── utils/           # Funções auxiliares
│   ├── main.py / server.js  # Arquivo principal da API (Flask, Node, etc.)
│   └── requirements.txt / package.json # Dependências
│
├── database/                # Scripts e arquivos do banco de dados
│   ├── schema.sql           # Estrutura do banco
│   └── seed.sql             # Dados iniciais (ex: admin)
│
├── .env                     # Variáveis de ambiente (nunca subir pro GitHub!)
├── .gitignore               # Ignora arquivos desnecessários no Git
├── README.md                # Explicação do projeto
└── package.json / pyproject.toml  # Configuração do projeto