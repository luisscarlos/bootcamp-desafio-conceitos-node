# Desafio sobre conceitos básicos do Node.js desenvolvido durante o Bootcamp 11 Rocketseat

## Desafio:

Desenvolver uma aplicação para armazenar repositórios de um portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

### Passos para executar o desafio desenvolvido:
-  Clonar o projeto
> Executar o comando `git clone git clone https://github.com/luisscarlos/01-desafio-conceitos-node.git` no teminal na pasta que deseja clonar

- Iniciar dependências
 > Na raiz do projeto executar o comando`yarn` no terminal

- Iniciar o projeto
> Executar o comando`yarn dev` no terminal

- Executar os testes automatizados com jest
> Executar o comando`yarn test` no terminal

### Routes

| Routes                 | Method |
| ---------------------- | ------ |
| /repositories          | GET    |
| /repositories          | POST   |
| /repositories/:id      | PUT    |
| /repositories/:id      | DELETE |
| /repositories/:id/like | POST   |

-  As rotas podem ser executadas através do Insomnia, importando o arquivo `Insomnia_requests.json`.

Made with 🚀 by Luis.
