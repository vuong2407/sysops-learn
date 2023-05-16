# SysOps Learn

This project serves as a practical guide to learning Operations and System concepts by deploying and managing a stack consisting of MySQL, Redis, and Node.js applications. It also includes monitoring capabilities with Prometheus, Grafana, and Cadvisor, and implements CI/CD using GitHub Actions.

## Features

- **App:** The project includes deployments of MySQL, Redis, and Node.js applications. It provides hands-on experience in setting up and configuring these popular technologies, allowing you to learn about their deployment, configuration, and management aspects.

- **Monioring:** The stack incorporates Prometheus, Grafana, and Cadvisor for monitoring and observability. By exploring these tools, you will gain insights into monitoring various metrics and performance indicators of your deployed applications, ensuring their health and optimizing their performance.

- **CI/CD:** GitHub Actions is used for Continuous Integration and Continuous Deployment (CI/CD) in this project. It demonstrates the automation of build, test, and deployment processes, enabling you to understand and practice modern software development practices.

## Getting Started

To get started with this project, follow the steps below:

1. **Prerequisites:** Make sure you have the following installed on your local machine:

   - Docker: [Download and Install Docker](https://docs.docker.com/engine/install/)
   - Docker compose: [Download and Install Docker Compose](https://docs.docker.com/compose/install/)

2. **Clone the Repository:** Clone this repository to your local machine using the following command:

```
https://github.com/vuong2407/sysops-learn.git
```

3. **Setup and Configuration:** Follow the instructions in the project documentation to set up and run docker, docker-compose for project

- Build Nodejs App

```
docker build -t sysops-nodejs-app .
```

- Run Docker compose

```
docker compose up
```

- (if you want to run in background)

```
docker compose up -d
```

## Contributing

Contributions to this project are welcome and encouraged. If you have any suggestions, improvements, or bug fixes, feel free to submit a pull request. Please ensure that your contributions align with the project's coding conventions and follow the guidelines outlined in the CONTRIBUTING.md file.

## License

This project is licensed under the [MIT License](LICENSE.md). You are free to modify and distribute the codebase, subject to the terms and conditions of the license.

## Acknowledgements

We would like to express our gratitude to the developers and contributors of the MySQL, Redis, Node.js, Prometheus, Grafana, Cadvisor, and GitHub Actions projects for their invaluable tools and resources, which have made this learning experience possible.

## Contact

If you have any questions, suggestions, or feedback, please feel free to reach out to us at your-email@example.com. We appreciate your involvement and are happy to assist you in your learning journey.
