### Desafio para vaga de BackEnd - Foco em Ruby On Rails:

Objetivo do Desafio:

O objetivo deste desafio é avaliar suas habilidades no desenvolvimento com o framework Ruby On Rails, bem como quaisquer integrações necessárias, a implementação de funcionalidades que executam em segundo plano de forma síncrona, a escrita de testes e a criação de uma documentação clara.

#### Requisitos:

- ruby-3.1.4
- sqlite3

Clone o projeto e ao executar:

```ruby
bundle install
rails db:migrate
rails db:seed
```
Será configurado uma aplicação rails contando com as seguintes funcionalidades:
- Usuário padrão admin@rotten e senha admin
- Página de login
- Rota para criação de novos usuários
- Rota para cadastrar novo filme
- Rota para dar nota nos filmes
- Exibir a média das notas de cada filme


#### Desafio:

- Criar uma rota para importar em massa vários filmes
  - Você pode criar essa rota para receber um arquivo csv ou um payload json, ou outra forma que ficar mais fácil de integrar
- Criar uma rota para submeter notas em massa para vários filmes
  - Você pode criar essa rota para receber um arquivo csv ou um payload json, ou outra forma que ficar mais fácil de integrar
- As tarefas acima **devem ser executadas em segundo plano**
  - Recomendamos usar o [Sidekiq](https://github.com/sidekiq/sidekiq) para gerenciar as tarefas em segundo plano, mas você pode escolher outra solução

#### Pontos Extras:
- Criar testes para as rotas da API e models da aplicação
  - Recomendamos usar o [Rspec](https://semaphoreci.com/community/tutorials/getting-started-with-rspec) para os testes, mas você pode escolher outra solução


#### Entrega:

No README.md descreva as instruções sobre como executar o projeto, configurar variáveis de ambiente e executar os testes.
Ao finalizar, forneça um link para o repositório do GitHub contendo o código-fonte e a documentação, enviado para o email vagas{at}oxeanbits{dot}com
