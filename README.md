# Kubernetes Fibonacci Calculator
** Disclamer ** This project has an overly complex architecture for its function but It is where I was applying my knowledge of Kubernetes

It is a Fibonacci Calculator where a React frontend sends a request to an Express backend to calculate fib sequence numbers but the Backend stores the sequence number in a Redis database where a worker is listening to changes in it and calculating the result and updating Redis with the value

It uses Kubernetes to orchestrate all elements of the application where each element has a deployment and a service to connect them to each other

Technologies:
- Kubernetes
- Docker
- Docker Compose
- Redis
- Express
- Nodejs
- React
- MongoDB
