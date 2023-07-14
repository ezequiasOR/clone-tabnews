# Clone TabNews

Implementação do https://www.tabnews.com.br/ para treinar programação

## Tecnologias

- Node.js
- Next.js
- React
- Docker

## .nvmrc

> rc: run commands

- Contém a versão do Node.js utilizado no projeto
- Necessário executar apenas o comando `nvm install` para instalar a versão correta

## Executando o projeto

1. Para levantar o servidor basta rodar o comando `npm run dev`, configurado no arquivo manifesto `package.json`

2. Para verificar se o código está com a formatação esperada, rode o comando `npm run link:check`

3. Para ajustar o código à formatação esperada, rode o comando `npm run lint:fix`

## Configurador de Editor

Neste projeto, é usado o [EditorConfig](https://editorconfig.org/). Caso esteja usando o `Visual Studio Code`, é necessário instalar a extensão [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig).

## Formatador Padrão

Caso esteja usando o `Visual Studio Code`, instale a extensão [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) e nas configure como formatador padrão. Além disso, ative a opção de formatar o código ao salvar o arquivo e desative a opção de salvar automaticamente.
