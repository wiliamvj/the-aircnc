Projeto criado na Semana OmniStack 9.0 da Rocketseat :D

Estrutura
.
├── backend/src/
|   ├── config/
|       └── upload.js (configuração do pacote de upload de arquivo - multer)
|   ├── controllers/  (controllers do projeto)
|   ├── models/       (models do projeto)
|   ├── routes.js     (arquivo de rotas de backend)
|   ├── server.js     (arquivo principal, utilizado para rodar o projeto do backend)
|   ├── .babelrc      (configuração do babel)
|   ├── .env          (variáveis de ambiente correspondentes ao backend)
|   ├── .env.example  (arquivo de exemplo para definir as variáveis de ambiente utilizadas no backend)
|   └── package.json  (dependências do node)
├── uploads/          (diretório onde serão salvos os arquivos enviados para a API)
└── README.md

├── frontend/src/
|   ├── assets/           (arquivos de imagens SVG do frontend)
|   ├── pages/            
|       └── Dashboard     
|       |   └── index.js  (Pagina de exibição de todos os spots)
|       └── Login     
|       |    └── index.js (Pagina de login da aplaicação)
|       └── New     
|           └── index.js  (Pagina de criação de spots)
|   ├── services/         
|           └── api.js    (arquivo de comunicação com o backend)
|   ├── App.css           (arquivo css do React)
|   ├── App.js            (arquivo para renderizar o index da aplicação)
|   ├── index.js          (render do React)
|   ├── routes.js         (arquivos de rotas do frontend)
|   └── package.json      (dependências do node)
|   └── yarn.lock         (arquivo de cache do yarn)
└── README.md

├── mobile/src/
|   ├── assets/           (arquivos de imagens SVG do frontend)
|   ├── pages/            
|       └── Dashboard     
|       |   └── index.js  (Pagina de exibição de todos os spots)
|       └── Login     
|       |    └── index.js (Pagina de login da aplaicação)
|       └── New     
|           └── index.js  (Pagina de criação de spots)
|   ├── services/         
|           └── api.js    (arquivo de comunicação com o backend)
|   ├── App.css           (arquivo css do React)
|   ├── App.js            (arquivo para renderizar o index da aplicação)
|   ├── index.js          (render do React)
|   ├── routes.js         (arquivos de rotas do frontend)
|   └── package.json      (dependências do node)
|   └── yarn.lock         (arquivo de cache do yarn)
└── README.md
