# Ambiente Rails

### Rails

Para instalar rails em qualquer OS, escolha um link de sua preferêcnia:

+ [Rails Girls](http://guides.railsgirls.com/install/)
+ [Install Rails](http://installrails.com/)

### Postgres

Aplicações Rails utilizam sqlite nativamente, porém na CJR é costume usar o postgresql devido sua compatibilidade com o Heroku.

+ [Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-14-04)
	+ Dica: instale o [brew](http://brew.sh/) no Mac.
+ [Mac OS](http://exponential.io/blog/2015/02/21/install-postgresql-on-mac-os-x-via-brew/)
+ De novo, não recomendamos windows. :sunglasses:

Além disso, recomendo criar um usuário no postgres próprio (que não seja o super admin) e configurá-lo com uma senha que você conheça e as permissões básicas. Use esse [link](http://www.postgresql.org/docs/9.1/static/sql-createrole.html) para saber mais.

Acesse, pelo terminal, usando o comando `psql`, o postgres e faça:

`=> CREATE USER {nome de usuário} WITH PASSWORD '{senha}' CREATEDB CREATEROLE;`

### Git

+ [Ubuntu](https://www.digitalocean.com/community/tutorials/como-instalar-o-git-no-ubuntu-14-04-pt)
+ Mac OS já vem com o git naturalmente. Mas caso precise instala-lo, use o brew.

