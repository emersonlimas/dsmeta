# < DSMeta >
<img src="https://github.com/emersonlimas/dsmeta/blob/main/frontend/src/assets/exampleImg/example.png" alt="DSMeta">

## Inicialização
Para executar o projeto utilize as ferramentas descritas na sessão *Ferramentas*.

## Ferramentas
* [Spring Tool Suite](https://spring.io/tools) - IDE para desenvolvimento Spring.
* [Visual Studio Code](https://code.visualstudio.com/) - IDE para desenvolvimento.

## Links importantes
* [NodeJs](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/)
* [Twilio](https://www.twilio.com/pt-br/)
* [Heroku](https://www.heroku.com/)
* [Netlify](https://www.netlify.com/) - Base directory: frontend | Build command: yarn build | Publish directory: frontend/dist | Variáveis de ambiente: VITE_BACKEND_URL
* [Figma](https://www.figma.com/file/PehiT8Dw4Lv5ioTSULZeRI/DSMeta3)


# < DSMeta >

## Introdução

Este projeto possui o objetivo principal de listar vendas realizadas em um determinado período.  
Com os objetivos gerais de realizar a filtragem entre datas e enviar notificação via SMS. 

## Análise técnica

### Descrição do ambiente técnico

O sistema é composto por um banco de dados e uma interface web. 
* Funcionalidades principais:
* **F1** - Filtrar data início 1.
* **F2** - Filtrar data fim 2.
* **F3** - Notificar via SMS 3.

As ferramentas utilizadas para o desenvolvimento incluem **< Java >** que é uma linguagem de programação utilizada para o Back-end, para front-end foi utilizado **< ReactJs >** .

Rotas utilizadas pela aplicação web para executar metodos de **POST** e **GET** no banco de dados. O retorno de cada uma das funções estara contido em uma sessão para renderização de páginas web.

| Nome | Funcionalidade|
|------|--------------|
|```GET``` /sales|Lista as 20 maiores vendas.|
|```POST``` /sales/{id}/notification|Notifica via SMS dados da venda.|

## Realização

* [DevSuperior - Escola de programação](https://devsuperior.com.br/)

