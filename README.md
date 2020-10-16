# Minio docker

Docker for Minio Server.

### Installation

1. Clone repository
    ````bash
    git clone https://github.com/jsalazarv/minio-docker.git
    ````

2. Access the project
    ````bash
    cd minio-docker
    ````

3. Create .env file and configure environment variables
    ````dotenv
    MINIO_ACCESS_KEY=MY_ACCESS_KEY
    MINIO_SECRET_KEY=MY_SECRET_KEY
    ````

4. Build Docker
    ````bash
    docker-compose up --build -d
    ````

5. Access the web browser at http://127.0.0.1:9000/