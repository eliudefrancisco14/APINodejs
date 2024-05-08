# API Node.js com Express, MySQL2, Sequelize, body-parser e dotenv

Esta é uma API simples desenvolvida em Node.js, que utiliza o Express como framework web, MySQL2 como cliente de banco de dados, Sequelize como ORM (Object-Relational Mapping), body-parser para fazer o parsing dos corpos das requisições HTTP, e dotenv para gerenciar variáveis de ambiente.

## Requisitos

- Node.js (v14 ou superior)
- MySQL Server
- npm (Node Package Manager) ou yarn (opcional)

## Instalação

```bash
git clone https://github.com/eliudefrancisco14/APINodejs.git
cd APINodejs
npm install
```

ou, se estiver utilizando yarn:

```bash
git clone https://github.com/eliudefrancisco14/APINodejs.git
cd APINodejs
yarn install
```

### Configurar as variáveis de ambiente:

Crie um arquivo chamado `.env` na raiz do projeto e defina as seguintes variáveis de ambiente:

```plaintext
DB_HOST=seu-host
DB_USER=seu-usuario
DB_PASSWORD=sua-senha
DB_DATABASE=seu-banco-de-dados
```

### Executar as migrações do banco de dados:

Certifique-se de que seu servidor MySQL esteja em execução, e então execute as migrações do Sequelize para criar as tabelas necessárias:

```bash
npx sequelize-cli db:migrate
```

### Model

Criei uma model, que é a de usuários, juntamente com 5 endpoints principais para um CRUD normal, que são:

- Criar Usuários
- Editar Usuário
- Deletar Usuário
- Ver Usuários
- Ver Usuário Por Id

### Iniciar o servidor:

Por fim, inicie o servidor Node.js:

```bash
npm start
```

ou, com yarn:

```bash
yarn start
```

O servidor estará disponível em `http://localhost:3000` por padrão.

## Uso

Esta API fornece endpoints para realizar operações CRUD (Create, Read, Update, Delete) em recursos específicos. Consulte a documentação da API ou o código fonte para obter informações detalhadas sobre os endpoints disponíveis e como usá-los.

## Documentação da API

Não está disponível ainda.

## Contribuição

Se você quiser contribuir para este projeto, por favor, siga estas etapas:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/sua-feature`)
3. Faça commit das suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/sua-feature`)
5. Crie um novo Pull Request

