## Dockerizing the Application

To Dockerize this application, follow these steps:

1. **Build the Docker image**: Run the following command in the directory that contains the Dockerfile. Replace `my-node-app` with the name you want to give to your Docker image.

    ```bash
    docker build -t my-node-app .
    ```

2. **Run the Docker image**: After building the image, you can run it with the following command. Replace `your-image-name` with the name you gave to your Docker image.

    ```bash
    docker run -p 3000:3000 my-node-app
    ```

    This command runs the Docker image and maps port 3000 inside the Docker container to port 3000 on your local machine. Adjust the port numbers as necessary based on your application's configuration.

3. **Access the application**: You can now access the application in your web browser at `http://localhost:3000`.

Remember to replace `my-node-app` with the name you gave to your Docker image.
