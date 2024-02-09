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
será configurado a seguinte aplicação rails com:
- Usuário padrão admin e senha admin
- Página de login
- Rota para cração de novos usuários
- Rota para cadastrar novo filme
- Rotas para dar nota nos filmes
- Exibi a média das notas de cada filme


#### Desafio:

- Criar uma rota para importar em massa vários filmes
- Criar uma rota para submeter notas em massa para varios filmes
- Estas tarefas devem ser executadas em segundo plano numa segunda instância da aplicação
  - Recomendamos o uso do [Sidekiq](https://github.com/sidekiq/sidekiq) para genrenciar as tarefas em segundo plano
