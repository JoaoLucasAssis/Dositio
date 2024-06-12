# Dositio - Plataforma Integrada de Gestão de Produtos e Usuários

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

## Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

![Fastify](https://img.shields.io/badge/Fastify-202020?style=for-the-badge&logo=fastify&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

## Instalação
<details>
<summary>Clique aqui!</summary>
<p>

### Pré-requisitos para instalação!

![Git](https://img.shields.io/badge/Git-E34F26?style=for-the-badge&logo=git&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
--------------------------------------------------------------------------------------------

Para começar, clone o repositório do projeto em seu ambiente local. Siga a etapa abaixo:

* Abra o terminal na pasta onde deseja clonar o repositório.

* Clone o repositório para o seu ambiente local usando o seguinte comando:

```git
git clone https://github.com/JoaoLucasAssis/Dositio.git
```

</p>
</details>

## Executando o Projeto

Para executar o projeto, siga os seguintes passos para o frontend e backend do projeto:

* Navegue até o diretório de cada um e execute o seguinte comando para instalar todas as dependências:

```git
npm install
```

* Após a instalação, você pode executar cada um usando o seguinte comando:

```node
npm run dev
```

### Backend

* Crie um arquivo `.env` no diretório raiz do projeto baseado no arquivo `.env.sample` já existente.
  
* Altere as configurações do arquivo ***.env*** para utilizar os ambientes desejados.

```javascript
STAGE = 'dev'
PORT= '8080'
HOST= '127.0.0.1'
JWT_SECRET= 'Abcd@1234'
DB_URL = 'mongodb://localhost:27017/dositio'
```

A API REST estará em execução em `http://127.0.0.1:8080`.

### Frontend

* Necessário executar apenas o seguinte comando:

```node
npm run dev
```

O servidor estará em execução em `http://localhost:3000`.

## Colaboradores

<table>
  <tr>
  <!-- João Lucas -->
    <td align="center">
      <a href="https://github.com/JoaoLucasAssis">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwxCRWlkfeigdbif83ap111RPNlGARl02wOF5OvW9zUA&s" width="100px;" height="100px;" alt="Foto do João Lucas"/><br>
        <sub>
          <b>JoaoLucasAssis</b>
        </sub>
      </a>
    </td>
    </td>
  </tr>
</table>

## Licença

Este projeto não possui nenhum licença. Sinta-se à vontade para usar, modificar e distribuir este código conforme necessário.
