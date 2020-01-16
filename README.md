# AirCNC

![Node](https://img.shields.io/badge/node-13.6.0-green) ![Yarn](https://img.shields.io/badge/yarn-1.21.1-green)

Projeto criado na Semana OmniStack 9.0 da [Rocketseat](https://rocketseat.com.br)


## Estrutura
```
├── backend/src/
|   ├── config/
|       └── upload.js       (configuração do pacote de upload de arquivo - multer)
|   ├── controllers/        (controllers do projeto)
|   ├── models/             (models do projeto)
|   ├── routes.js           (arquivo de rotas de backend)
|   ├── server.js           (arquivo principal, utilizado para rodar o projeto do backend)
|   └── package.json        (dependências do node)
├── uploads/                (diretório onde serão salvos os arquivos enviados para a API)
└── README.md

├── frontend/public/
|   └── package.json        (dependências do node)
├── frontend/src/
|   ├── assets/             (arquivos de imagens SVG do frontend)
|   ├── pages/            
|       └── Dashboard     
|       |   └── index.js    (Pagina de exibição de todos os spots)
|       └── Login     
|       |    └── index.js   (Pagina de login da aplicação)
|       └── New     
|           └── index.js    (Pagina de criação de spots)
|   ├── services/         
|           └── api.js      (arquivo de comunicação com o backend)
|   ├── App.css             (arquivo css do React)
|   ├── App.js              (arquivo para renderizar o index da aplicação)
|   ├── index.js            (render do React)
|   ├── routes.js           (arquivos de rotas do frontend)
|   └── package.json        (dependências do node)
|   └── yarn.lock           (arquivo de cache do yarn)

├── mobile/.expo/           (arquivos de configurações do expo)
├── mobile/assets/          (arquivos de imagens PNG do expo)
├── mobile/src/         
|   ├── assets/             (arquivos de imagens SVG do mobile)
|   ├── components/     
|           └── SpotList.js (exibe todo os spots)
|   ├── pages/            
|       └── Book.js         (arquivo de solicitação de reserva em spot)
|       └── List.js         (Pagina de exibição de todos os spots
|       └── Login.js        (Pagina de login da aplicação)
|   ├── services/         
|           └── api.js      (arquivo de comunicação com o backend)
|   ├── App.js              (arquivo para renderizar o index da aplicação)
|   ├── routes.js           (arquivos de rotas do frontend)
|   └── package.json        (dependências do node)
|   └── yarn.lock           (arquivo de cache do yarn)
└── README.md
```

## Alterações do projeto original
- Utilização do babel para atualizar a versão do ECMAScript
- Utilização do arquivo `.env` para salvar as variáveis de ambiente através do pacote `dotenv`
