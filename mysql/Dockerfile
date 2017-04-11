FROM mysql:5.7

MAINTAINER Mihail Krastev <mlinuxgada@gmail.com>

RUN chown -R mysql:root /var/lib/mysql/

ADD my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306
