# Dockerized User Data Update App

This project is a simple application designed to practice Docker and AWS ECR (Elastic Container Registry). The app allows users to update their data, and it's built using three Docker containers: one for the app itself, one for the MongoDB database, and one for Mongo Express (a web-based MongoDB admin interface). The project also includes a Docker Compose configuration to manage the containers.

## Project Structure

- **App Container**: This container hosts the main application, which allows users to update their data.
- **MongoDB Container**: This container runs a MongoDB instance, which serves as the database for storing user data.
- **Mongo Express Container**: This container runs Mongo Express, providing a web interface to interact with the MongoDB instance.

## Screenshots

### 1. Image in AWS ECR

![photo_2024-09-04_05-53-57](https://github.com/user-attachments/assets/fb75d6b2-41f4-4d84-a3d9-d57b65b09742)


This screenshot shows the Docker image successfully pushed to AWS ECR.

### 2. Docker Containers Running

![photo_2024-09-04_05-53-54](https://github.com/user-attachments/assets/9d7882cb-638e-4d6c-b798-ddbc98f872bb)


This screenshot shows the three containers (App, MongoDB, Mongo Express) running successfully using Docker Compose.

### 3. Mongo Express Interface

![photo_2024-09-04_05-53-52](https://github.com/user-attachments/assets/619b196a-d4e5-4106-87d7-7e9e385e87e1)


This screenshot demonstrates the Mongo Express interface, displaying a sample user document in the MongoDB collection.

### 4. App

![photo_2024-09-04_05-53-50](https://github.com/user-attachments/assets/f0974de9-89a8-46a0-8ac8-bb085b4c7407)

This screenshot show the simple app



 . **Run the application using Docker Compose**:
    ```bash
    docker-compose  docker-compose.yaml up 
    ```

    This will start all three containers: the app, MongoDB, and Mongo Express.

. **Access the application**:
    - The app should be accessible via `http://localhost:your-app-port`
    - Mongo Express can be accessed via `http://localhost:your-mongo-express-port`


-
