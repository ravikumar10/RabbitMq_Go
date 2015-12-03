# RabbitMq_Go
RabbitMQ is a message broker. In essence, it accepts messages from producers, and delivers them to consumers.
In-between, it can route, buffer, and persist the messages according to rules you give it.

RabbitMQ speaks AMQP 0.9.1, which is an open, general-purpose protocol for messaging. There are a number of clients for RabbitMQ in many different languages. We'll use the Go amqp client in this tutorial.

First, install amqp using go get:

$ go get github.com/streadway/amqp

Now we can run both scripts. In a terminal, run the sender:

$ go run send.go
then, run the receiver:

$ go run receive.go
