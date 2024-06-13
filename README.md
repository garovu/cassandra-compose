# Cassandra Compose

This project provides a Docker Compose configuration for running Cassandra in a local development environment.

## Prerequisites

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

1. Clone this repository:

    ```shell
    git clone https://github.com/garovu/cassandra-compose.git
    ```

2. Navigate to the project directory:

    ```shell
    cd cassandra-compose
    ```

3. Start the Cassandra containers:

    ```shell
    docker-compose up -d
    ```

4. Verify that Cassandra is running:

    ```shell
    docker-compose ps
    ```

## Usage

- To connect to Cassandra using cqlsh:

  ```shell
  docker-compose exec cassandra cqlsh
  ```

- To stop the Cassandra containers:

  ```shell
  docker-compose down
  ```

## Contributing

Contributions are welcome! Please read the [Contributing Guidelines](CONTRIBUTING.md) for more information.

## License

This project is licensed under the [MIT License](LICENSE).
