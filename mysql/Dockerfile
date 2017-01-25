FROM mysql:5.6
MAINTAINER kaznishi<kaz.nishimu@gmail.com>

COPY my.cnf /etc/my.cnf

# 「/docker-entrypoint-initdb.d/」にSQLファイルを置いておくと、初回起動時に実行される
COPY initdb.d/*.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
