# url-shortener-service
Java Spring Boot Project for creating shortened URLs, managing them and redirecting to real ones.  

This project is made of two services:

-Managemetn service: 

  https://github.com/admirvelic/URLShortenerManagementService.git

-Redirection service:

  https://github.com/admirvelic/URLShortenerRedirectionService.git


Prerequisites:

Docker

Refer to documentation on steps to install: https://docs.docker.com/get-docker/

Installation:

1. Clone the repos with:

   git clone https://github.com/admirvelic/URLShortenerManagementService.git

   git clone https://github.com/admirvelic/URLShortenerRedirectionService.git

2. Use docker-compose from Management service to spin up containers for services required for project:

   docker-compose up -d

   It will spin up 3 services:
   
   -MariaDb witch serves as main database for Management service

   -Redis witch serves as in memory database for Redirection service

   -RabbitMQ witch is used for comunication betwen two services

3. Open repositories in your IDE of choice and run:

    -UrlShortenerManagementServiceApplication.java
  
    -UrlShortenerRedirectionServiceApplication.java

Usage:

Please refer to the Postman collection (URL shortener.postman_collection.json) located in this repo for Usage details.

   
