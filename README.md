# Projeto React/Node CRUD

Este é um projeto de exemplo que demonstra um aplicativo React frontend integrado a um backend Node.js usando Express, juntamente com uma API RESTful para realizar operações CRUD (Create, Read, Update, Delete) em uma lista de usuários.

## Tecnologias Utilizadas

- **Frontend**:
  - React
  - Axios (para realizar requisições HTTP para o backend)
  - Styled Components (para estilização)
  
- **Backend**:
  - Node.js
  - Express (para criar a API RESTful)
  - UUID (para gerar IDs únicos para os usuários)

## Funcionalidades

- Adicionar um novo usuário com nome e idade.
- Visualizar a lista de usuários cadastrados.
- Atualizar os dados de um usuário existente.
- Deletar um usuário da lista.

## Como Usar

1. **Configuração**:
    - Certifique-se de ter o Node.js instalado em sua máquina.
    - Clone este repositório em sua máquina local.

2. **Backend**:
    - Navegue até a pasta `backend` do projeto.
    - Execute `npm install` para instalar as dependências.
    - Execute `npm start` para iniciar o servidor backend. O servidor estará disponível em `http://localhost:3001`.

3. **Frontend**:
    - Navegue até a pasta `frontend` do projeto.
    - Execute `npm install` para instalar as dependências.
    - Execute `npm start` para iniciar o aplicativo frontend. O aplicativo será aberto automaticamente em seu navegador padrão.

4. **Uso**:
    - No aplicativo React, preencha os campos de nome e idade e clique em "Cadastrar" para adicionar um novo usuário.
    - Você verá a lista de usuários abaixo do formulário.
    - Para editar ou excluir um usuário, clique nos botões correspondentes ao lado das informações do usuário na lista.

## Contribuição

Sinta-se à vontade para contribuir com este projeto através de pull requests. Quaisquer sugestões de melhorias, correções de bugs ou novas funcionalidades são bem-vindas!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
