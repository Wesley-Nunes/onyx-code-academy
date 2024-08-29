# Onyx Code Academy

This repository showcases the different layers of the Onyx Code Academy project.  
It provides a streamlined setup to help you get started quickly by using Docker to manage and run the various components.

## Getting Started

### Cloning the Repositories

To get started, you'll need to clone this repository and its related components. Follow these steps:

1. **Clone the main repository:**

    ```bash
    git clone git@github.com:Wesley-Nunes/onyx-code-academy.git
    cd onyx-code-academy
    ```

2. **Clone the front-end repository:**

    ```bash
    git clone -b 0.1.0 git@github.com:Wesley-Nunes/onyx-code-academy-front-end.git
    ```

3. **Clone the mock server repository:**

    ```bash
    git clone -b 0.1.0 git@github.com:Wesley-Nunes/onyx-code-academy-mock-server.git
    ```

   **Note:** The branch name `0.1.0` corresponds to the current version of the project. Make sure to use the correct branch for the version you are working on.

### Running the Front-End with the Mock Server

To run the front-end alongside the mock server, use Docker Compose. Execute the following command from the `onyx-code-academy` directory:

```bash
docker compose -f frontend-mockserver-compose.yaml up --watch
```

- The front-end application will be available at [http://localhost:3000](http://localhost:3000).
- The mock server will be accessible at [http://localhost:4000](http://localhost:4000).

