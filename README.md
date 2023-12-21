# Docker Compose Collection for Web Developers

Welcome to the Docker Compose Collection for web developers! This collection includes Docker Compose configurations for common services used in web development projects. With these configurations, you can quickly set up your development environment on any system.

## Services Included

- **MySQL:** A popular relational database.
- **MeiliSearch:** A powerful, fast, and open-source search engine.
- **Socket.IO:** Real-time bidirectional event-based communication.
- **Redis:** An in-memory data structure store, used as a caching layer.
- **MongoDB:** A NoSQL database for storing and retrieving data.

Feel free to explore each service's folder for specific configurations and customization options.

## Quick Start

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/moh-slimani/docker-compose-collection.git
    ```

2. Navigate to the desired service folder, e.g., `mysql`:

    ```bash
    cd docker-compose-collection/mysql
    ```

3. Copy the example environment file *(if available)*:

    ```bash
    cp .env.example .env
    ```

4. Update the `.env` file with your preferred configurations.

5. Run the Docker Compose command to start the service:

    ```bash
    docker-compose up -d
    ```

6. That's it! Your service is now up and running.

## Configuration

Each service folder contains a `.env.example` file with default configurations. Copy this file to `.env` and modify it according to your project's needs.

## To-Do List
- [ ] add `.env.example` file to mysql.
- [ ] add `.env.example` file to meilisearch.
- [ ] add `.env.example` file to mongo.

## Contributing

If you have improvements or additional services to contribute, feel free to submit a pull request.

## License

This Docker Compose Collection is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy coding!