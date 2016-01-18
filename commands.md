Comandos
========

`rails new nomedaapliação`

Criamos uma aplicação nova em rails usando todas as opções padrões.

`rails new nomedaapliação --database=postgresql`

Criamos uma aplicação nova em rails usando o banco de dados postgresql

`rake db:create`

Cria o banco de dados.

`rake db:migrate`

Realiza todas as migrações pendentes.

`rake db:seed`

Popula o banco de dados com todos os objetos em `db/seeds.rb`

`rake db:setup`

Cria o banco de dados, realiza as migrações e popula o banco com as seeds.

`rails s`

Inicia o server.

`rails c`

Inicia o console ruby com os dados da sua aplicação rails

`rake assets:precompile`

Compila todos os assets conforme o Asset Pipeline configurado na aplicação.