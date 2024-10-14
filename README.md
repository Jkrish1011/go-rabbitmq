# Go implementation to use RabbitMQ

A sample project which demonstrates the usage of Rabbitmq between two functionalities.

## Steps to Run the project

Note: All commands are run from the root

# 1. Pull the Docker Image of RabbitMQ

Note: Keep this terminal running

```
docker compose up
```

# 2. Run the Receiver

Open a new terminal to run the receiver and keep it running.

```
go run receive.go
```

# 3. Run the Sender

Open a new terminal to run the Sender

```
go run send.go
```

You can see the messages being sent from the sender terminal in the receiver terminal
