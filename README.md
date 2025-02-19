# Sistema de Controle de Estoque - Frios Moretti

Este projeto é um sistema de controle de estoque que gerencia produtos, entradas, retiradas e movimentações em um banco de dados. Ele permite o cadastro e a manipulação dessas informações por meio de uma API construída com Node.js, Express e PostgreSQL. Desenvolvido como parte da disciplina de Projeto Orientado.

## Começando

Essas instruções permitirão que você obtenha uma cópia do projeto na sua máquina local para fins de desenvolvimento e teste.

### Pré-requisitos

Você precisará ter instalado:

- [Node.js](https://nodejs.org/) (v14 ou superior)
- [PostgreSQL](https://www.postgresql.org/) (v13 ou superior)
- [Git](https://git-scm.com/)

### Instalação

Siga os passos abaixo para configurar o ambiente de desenvolvimento:

1. Clone o repositório:
   ```bash
   git clone https://github.com/jsevitor/nodejs-frios-moretti.git
   cd nodejs-frios-moretti
   ```

2. Instale as dependências do projeto:
   ```bash
   npm install
   ```

3. Configure o banco de dados PostgreSQL e as variáveis de ambiente:
   - Crie um banco de dados no PostgreSQL.
   - Crie um arquivo `.env` e configure as variáveis de ambiente, incluindo as credenciais do banco de dados.

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

. O servidor estará disponível em [http://localhost:3001](http://localhost:3001).

### Implantação

Para implantar o projeto em um ambiente de produção, siga os passos abaixo:

1. Configure as variáveis de ambiente no servidor de produção.
2. Execute as migrações e seeders no banco de dados de produção.
3. Inicie o servidor com `npm start`.

### Construído com

- [Node.js](https://nodejs.org/) - Ambiente de execução JavaScript
- [Express](https://expressjs.com/) - Framework web
- [Nodemon](https://nodemon.io/) - Ferramenta para reiniciar o servidor automaticamente
- [CORS](https://www.npmjs.com/package/cors) - Middleware para habilitar CORS
- [PostgreSQL](https://www.postgresql.org/) - Banco de dados relacional

### Autores

- **José Vitor Oliveira** - *Desenvolvedor Full Stack* - [jsevitor](https://github.com/jsevitor)
- **Gabriela Queiroz** - *Documentação* - [GabiQueiroz26](https://github.com/GabiQueiroz26)
- **Vinícius Nunes** - *Designer* - [vinicgabriel](https://github.com/vinicgabriel)
- **Roberto (João)** - *Testes* - [Apaskasko](https://github.com/Apaskasko)

### Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE.md) para detalhes.

### Expressões de gratidão

- Agradecimentos especiais aos colegas de equipe e ao professor que auxiliaram no desenvolvimento deste projeto.
