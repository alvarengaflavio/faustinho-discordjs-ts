<h1 style="text-align:center;">Faustinho Bot Discord.js v14</h1>

## Recursos

- 🟦 Typescript
- 🔥 Comandos Slash (suporta auto completar!)
- ✉️ Comandos de mensagem
- 🕛 Cooldowns
- 🏴 Permissões detalhadas
- 💪 Manipuladores de Eventos e Comandos
- 🍃 Suporte ao MongoDB

## Instalação, Compilação e Execução

1. Clone o repositório e crie um arquivo chamado `.env` e preencha-o conforme abaixo

```js
TOKEN=SEU_TOKEN_AQUI
CLIENT_ID=ID_DO_SEU_BOT
PREFIX=!
MONGO_URI=SUA_STRING_DE_CONEXÃO_COM_O_MONGO
MONGO_DATABASE_NAME=NOME_DO_SEU_BANCO_DE_DADOS
```

2. Instale o TypeScript. Para instalar o TypeScript, você pode executar o seguinte comando no seu terminal. Isso instalará a versão mais recente do TypeScript globalmente em seu computador. (Você pode pular esta etapa se já tiver o TypeScript instalado)

```ts
npm install -g typescript
```

3. Compile o projeto executando o seguinte comando:

`Este comando também instalará os módulos do node se você ainda não os tiver instalado.`

```js
npm run build
```

4. Uma vez que a compilação estiver completa, será gerada uma pasta chamada `build` que contém a versão compilada do seu código ts para js. Você pode executar o seguinte comando no seu terminal para executar o projeto:

```js
npm start
```
