# playwright-mark - Automação de Testes Web

## :pushpin: Cenários implementados no projeto
- Deve poder cadastrar uma nova tarefa
- Não deve permitir cadastrar tarefa duplicada
- Campo obrigatório
- Deve excluir uma tarefa

## :hammer_and_wrench: Tecnologias Utilizadas
- [Playwright](https://playwright.dev/) - Framework de testes automatizados
- [Node.js](https://nodejs.org/en/) - Plataforma de desenvolvimento
- [TypeScript](https://www.typescriptlang.org/) - Superset do Javascript 

-------------------------------------------------------------------
## :checkered_flag: Como Executar o Projeto
[Node.js](https://nodejs.org/) v16 ou superior para executar.

Realizar o clone do projeto.

Abrir o Prompt de comandos como Administrador e ativar o Yarn por meio [do Corepack](https://nodejs.org/dist/latest/docs/api/corepack.html) executando o comando abaixo:

```sh
corepack enable
```

Informar os comandos abaixo para instalar as dependências do projeto:
```sh
cd playwright-mark-tests
yarn install
```

Informar os comandos abaixo para preparar o ambiente para a execução dos testes(api):
```sh
cd playwright-mark-tests/apps/api
yarn install
yarn db:init ou npm run init
yarn dev 
```
Informar os comandos abaixo para preparar o ambiente para a execução dos testes(web):
```sh
cd playwright-mark-tests/apps/web
yarn install
yarn dev 
```

Informar os comandos abaixo para  executar dos testes automatizados:

```sh
cd playwright-mark-tests
yarn playwright test
yarn playwright tasks
yarn playwright tasks --debug
```

Informar os comandos abaixo para gerar relatório de execução dos testes:
```sh
yarn playwright show-report  ou npx playwright show-report  
```

-------------------------------------------------------------------

