# CI/CD Project

This repository contains a CI/CD project that allows you to automate the process of building, testing, and deploying your application.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository onto your local machine.
2. Install the necessary dependencies.
3. Configure your AWS credentials.
4. Update the configuration files to suit your needs.

## Dependencies

This project requires the following dependencies:

- AWS CLI
- Docker
- Jenkins
- GitHub

## Configuration

To configure this project, you will need to update the following files:

- `Jenkinsfile`: This file contains the pipeline configuration for your application.
- `Dockerfile`: This file contains the configuration for your Web App.

## Usage

To use this project, follow these steps:

1. Push changes to your GitHub repository.
2. Jenkins will automatically detect the changes and trigger a build.
3. The build process will run the tests and create a Docker image.
4. The Docker image will be pushed to DockerHub.
5.  Jenkins will then connect to the other instance through SSH and deploy the Web Application by pulling from DockerHub.

## Contributing

If you would like to contribute to this project, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
