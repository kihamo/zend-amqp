## Install RabbitMQ
`sudo apt-get install rabbitmq-server`   
`git clone git://github.com/alanxz/rabbitmq-c.git`  
`cd rabbitmq-c`  
`git submodule init && git submodule update`  
`autoreconf -i && ./configure && make && make install`  
`pecl install amqp`  
`echo 'extension = amqp.so' > /etc/php5/conf.d/amqp.ini`