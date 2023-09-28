# URL Shortener Service

The URL Shortener Service is a robust Java Spring Boot project that simplifies the creation and management of shortened URLs and seamlessly redirects to the original ones. This project is modularized into two distinct services:

### Services:
1. **[Management Service](https://github.com/admirvelic/URLShortenerManagementService.git)**
   - Repository: https://github.com/admirvelic/URLShortenerManagementService.git

2. **[Redirection Service](https://github.com/admirvelic/URLShortenerRedirectionService.git)**
   - Repository: https://github.com/admirvelic/URLShortenerRedirectionService.git

## Prerequisites:
Ensure that Docker is installed on your system. If not, you can download and install Docker by following the official [Docker documentation](https://docs.docker.com/get-docker/).

## Installation Steps:

1. **Clone the Repositories:**
   ```sh
   git clone https://github.com/admirvelic/URLShortenerManagementService.git
   git clone https://github.com/admirvelic/URLShortenerRedirectionService.git

2. Start the Services with Docker:

Navigate to the Management Service directory and use docker-compose to start the required containers.

`docker-compose up -d`

The above command initializes the following three services:

- <b>MariaDB</b>: Acts as the main database for the Management Service.
- <b>Redis</b>: Serves as an in-memory database for the Redirection Service.
- <b>RabbitMQ</b>: Facilitates communication between the Management and Redirection services.

3. Run the Applications:

Open the cloned repositories in your preferred IDE and run them.

## Usage:

For a detailed guide on how to use the available endpoints and services, please refer to the included Postman collection, URL shortener.postman_collection.json, located in the repository.