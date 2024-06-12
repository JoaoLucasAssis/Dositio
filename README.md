# Dositio - Aplicação web para gestão 

Este projeto acadêmico consiste em uma aplicação web para gerenciamento de `produtos`, `categorias` e `usuários`, utilizando uma API REST como backend e uma aplicação frontend para interação com o usuário.

### Backend

O backend deste projeto é uma API RESTful desenvolvida com Fastify e MongoDB. 

Ele oferece rotas para manipulação de recursos como `produtos`, `categorias` e `usuários`, seguindo os princípios RESTful.

#### Como funciona o Backend

O servidor Fastify é responsável por lidar com as requisições HTTP, roteando-as para as funções correspondentes que realizam as operações no banco de dados MongoDB. 

As requisições HTTP podem ser feitas por qualquer cliente HTTP, como ThunderClient ou Postman.

Para mais detalhes sobre como executar o backend, consulte a seção [Executando o Projeto](https://github.com/JoaoLucasAssis/Dositio_Backend/blob/main/README.md) no README específico do backend.

### Frontend

O frontend deste projeto é uma aplicação web desenvolvida com Next.js e React.js. 

Ele consome a API REST fornecida pelo backend e oferece uma interface para interagir com os recursos disponíveis.

#### Funcionalidades do Frontend

* Autenticação de usuários
* Visualização de produtos e categorias
* Navegação entre diferentes páginas da aplicação

Para mais detalhes sobre como executar o frontend, consulte a seção [Executando o Projeto](https://github.com/JoaoLucasAssis/Dositio/blob/main/Dositio_Frontend/README.md) no README específico do frontend.
