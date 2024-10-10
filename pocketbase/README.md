# Steps to run the project

1. Build the image using the following command

```bash
docker build -t pocketbase .
```

2. Run the Docker container using the following command

```bash
docker run -p 8080:8090 pocketbase
```

3. The application will be accessible at `http://localhost:8080`