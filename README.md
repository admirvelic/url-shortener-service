# url-shortener-service

The URL Shortener Service is a Java Spring Boot project that allows you to create shortened URLs, manage them, and redirect to the original ones. It consists of two services:

Management Service 

Redirection Service

To use this project, you need to have Docker installed. You can refer to the official Docker documentation for installation steps:

 Get Docker.

Here are the installation steps:

Clone the repositories using the following commands:

git clone https://github.com/admirvelic/URLShortenerManagementService.git

git clone https://github.com/admirvelic/URLShortenerRedirectionService.git

Use docker-compose from the Management Service to spin up the required containers for the project:

docker-compose up -d

This command will start three services:

MariaDB: Serves as the main database for the Management Service.

Redis: Serves as an in-memory database for the Redirection Service.

RabbitMQ: Used for communication between the two services.

Open the repositories in your preferred IDE and run the following files:

UrlShortenerManagementServiceApplication.java

UrlShortenerRedirectionServiceApplication.java

For detailed usage instructions, please refer to the Postman collection (URL shortener.postman_collection.json) located in this repository.