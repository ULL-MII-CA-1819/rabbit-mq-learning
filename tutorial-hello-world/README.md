# Learning to use RabbitMQ

* Instalación: [https://www.rabbitmq.com/install-homebrew.html](https://www.rabbitmq.com/install-homebrew.html)
* Tuve que poner el PATH:

```
[~/local/src/CA/sol-nodejs-the-right-way/connecting-robust-microservices-chapter-4/hello-rabbit]$ sudo  rabbitmqctl --help
Password:
sudo: rabbitmqctl: command not found
[~/local/src/CA/sol-nodejs-the-right-way/connecting-robust-microservices-chapter-4/hello-rabbit]$ export PATH=$PATH:/usr/local/sbin
[~/local/src/CA/sol-nodejs-the-right-way/connecting-robust-microservices-chapter-4/hello-rabbit]$  rabbitmq-server

  ##  ##
  ##  ##      RabbitMQ 3.7.8. Copyright (C) 2007-2018 Pivotal Software, Inc.
  ##########  Licensed under the MPL.  See http://www.rabbitmq.com/
  ######  ##
  ##########  Logs: /usr/local/var/log/rabbitmq/rabbit@localhost.log
                    /usr/local/var/log/rabbitmq/rabbit@localhost_upgrade.log

              Starting broker...
 completed with 6 plugins.
```
* He seguido este tutorial "Hello RabbitMQ!" [https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html](https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html)
* En este repo estan los ejemplos. GitHub Repo: [https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs](https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs)
    * Folder src. GitHub Repo src: [https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs/src](https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs/src)
* Ejecución:

```
[~/campus-virtual/1819/ca1819/srcCA/rabbit-mq-learning/tutorial-hello-world]$ node send.js
 [x] Sent 'Hello World!'
[~/campus-virtual/1819/ca1819/srcCA/rabbit-mq-learning/tutorial-hello-world]$ node receive.js 
 [*] Waiting for messages in hello. To exit press CTRL+C
 [x] Received Hello World!
^C
```
