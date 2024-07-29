# Setup Three-Tier Application with Docker Containers

## Overview

This project demonstrates how to set up a three-tier application using Docker containers on AWS. It involves creating a Docker Compose file to define and run a web service, an application service, and a database service. This project is beginner-friendly and aims to provide hands-on experience with Docker and AWS services.

## AWS Resources Used

- **EC2 Instances**: For hosting the Docker containers.
- **IAM Roles**: For providing necessary permissions to the EC2 instances.

**Note**: Be mindful of AWS resource usage to avoid incurring unexpected costs. 

## Steps

### Task 1: Sign in to AWS Management Console

1. Open the AWS Console and sign in using your IAM Username and Password.

### Task 2: SSH into EC2 Instance

1. Select your EC2 instance and click on the "Connect" button.
2. Use the "EC2 Instance Connect" option to open a new tab for executing Linux commands.

### Task 3: Create Docker Compose File

1. Create a project directory and navigate into it.
2. Create a `docker-compose.yaml` file with the necessary configurations for web, app, and db services. The Docker Compose file defines three services: web, app, and db. The web service uses Nginx as a web server, the app service uses Node.js, and the db service uses MySQL.

### Task 4: Create Application Files

1. Create the necessary directories and files for your application. 
   - The `api` folder should have an `index.html` file and an `app.js` file.
   - The `index.html` file contains the HTML content for the web service.
   - The `app.js` file contains the Node.js application code.

### Task 5: Build and Run the Application

1. Start the services defined in the `docker-compose.yaml` file using:
   ```bash
   sudo /usr/local/bin/docker-compose up
   ```

2. Access the application by navigating to the EC2 instance's IPv4 DNS with the appropriate port (e.g., http://<IPv4_DNS>:8080).

## Useful npm Commands
    . Initialize a Node.js application:
npm init -y

    . Install necessary dependencies:
npm install express path


## Documentation

For more information, please refer to the official documentation:

- [Docker Documentation](https://docs.docker.com)
- [AWS Documentation](https://docs.aws.amazon.com)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
# Setup Three-Tier Application with Docker Containers

## Overview

This project demonstrates how to set up a three-tier application using Docker containers on AWS. It involves creating a Docker Compose file to define and run a web service, an application service, and a database service. This project is beginner-friendly and aims to provide hands-on experience with Docker and AWS services.

## AWS Resources Used

- **EC2 Instances**: For hosting the Docker containers.
- **IAM Roles**: For providing necessary permissions to the EC2 instances.

**Note**: Be mindful of AWS resource usage to avoid incurring unexpected costs. 

## Steps

### Task 1: Sign in to AWS Management Console

1. Open the AWS Console and sign in using your IAM Username and Password.

### Task 2: SSH into EC2 Instance

1. Select your EC2 instance and click on the "Connect" button.
2. Use the "EC2 Instance Connect" option to open a new tab for executing Linux commands.

### Task 3: Create Docker Compose File

1. Create a project directory and navigate into it.
2. Create a `docker-compose.yaml` file with the necessary configurations for web, app, and db services. The Docker Compose file defines three services: web, app, and db. The web service uses Nginx as a web server, the app service uses Node.js, and the db service uses MySQL.

### Task 4: Create Application Files

1. Create the necessary directories and files for your application. 
   - The `api` folder should have an `index.html` file and an `app.js` file.
   - The `index.html` file contains the HTML content for the web service.
   - The `app.js` file contains the Node.js application code.

### Task 5: Build and Run the Application

1. Start the services defined in the `docker-compose.yaml` file using:
   ```bash
   sudo /usr/local/bin/docker-compose up
   ```

2. Access the application by navigating to the EC2 instance's IPv4 DNS with the appropriate port (e.g., http://<IPv4_DNS>:8080).

## Useful npm Commands
    . Initialize a Node.js application:
npm init -y

    . Install necessary dependencies:
npm install express path


## Documentation

For more information, please refer to the official documentation:

- [Docker Documentation](https://docs.docker.com)
- [AWS Documentation](https://docs.aws.amazon.com)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
