FROM mongo:3.4

MAINTAINER jcjacarrillo@gmail.com

COPY drop/* usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]