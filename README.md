# README

#### Requisitos:

- ruby-3.1.4
- sqlite3

Ao executar:

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
- Rotas para dar nota nos filmes
- Exibi a média das notas de cada filme


#### Desafio:

- Criar uma rota para importar em massa vários filmes
- Criar uma rota para submeter notas em massa para vários filmes
- Estas tarefas devem ser executadas em segundo plano numa segunda instância da aplicação
  - Recomedamos usar o [Sidekiq](https://github.com/sidekiq/sidekiq) para gerenciar as tarefas em segundo plano, mas você pode escolher outra soluçãn

#### Pontos Extras:
- Criar testes para as rotas da API e models da aplicação
  - Recomendamos usar o [Rspec](https://semaphoreci.com/community/tutorials/getting-started-with-rspec) para os testes, mas você pode escolher outra solução


#### Entrega:

No README.md descreva as instruções sobre como executar o projeto, configurar variáveis de ambiente e executar os testes.
Ao finalizar, forneça um link para o repositório do GitHub contendo o código-fonte e a documentação, enviado para o email vagas{at}oxeanbits{dot}com
