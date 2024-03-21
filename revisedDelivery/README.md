## Setup Instructions

### 1. Running StacksOfDocker's Docker Compose

First, navigate to the root directory and run the following command to start the Docker Compose setup:

docker-compose up -d

This will launch the services defined in the `docker-compose.yaml` file. Make sure to replace `<your_email>` with your email address in the Traefik command inside the `docker-compose.yaml` file.

### 2. Running Paperless-ngx Docker Compose

Next, navigate to the `paperless-ngx` directory and run the following command to start the Paperless-ng setup and wait about a min:

docker-compose up -d

This will deploy Paperless-ng and configure it to work with Traefik as a reverse proxy.

### 3. Accessing the Services

Once both Docker Compose setups are running, you can access the services using the Urls.
Credentials to Login:

    username: "USER"
    password: "PASS"
