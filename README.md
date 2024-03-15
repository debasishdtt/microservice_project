<h1 align="center" id="title">Microservice Project: Emart-app</h1>

## 🌐 Introduction
<p>Introduction:
The EMart Microservices Application represents a modern approach to software architecture, utilizing microservices to build a scalable and flexible e-commerce platform. In this project, we deployed the EMart application using Docker containers and Docker Compose, showcasing the benefits of microservices architecture in software development.</p>

<h5>🌟About</h5>
This project was developed as part of a guided project/tutorial on Udemy by Imran Teli. It serves as a practical exercise to reinforce the concepts learned during the tutorial.

## 🎯 Project Objectives
The primary objective of this project was to demonstrate the deployment of a microservices-based application using Docker containers, emphasizing scalability, flexibility, and ease of deployment.

## 💻 Built with
* Hypervisor: Oracle VM Virtual Box
* Automation: Vagrant
* Command Line Tool: Git Bash
* IDE (Optional): Visual Studio Code.

## 🏛️ Architecture Overview
The EMart application follows a microservices architecture, comprising multiple independent services deployed as containers. The architecture includes:

* Client Application (Angular): Frontend application for user interaction.

* Mart API (Node.js): Service handling business logic for products and users, utilizing MongoDB as the database.

* Books API (Java): Service managing book-related operations, backed by MySQL database.

* MongoDB Database: Used by Mart API for data storage.

* MySQL Database: Employed by Books API for data management.

![app stack](https://github.com/debasishdtt/microservice_project/assets/81139107/7d432a86-a3dc-4468-98d9-0717bc30f237)

<p align="center">Fig. 1: Architectural design of the setup</p>

<h3>Deployment Process</h3>

1.	Setup: Cloned the EMart application repository and navigated to the project directory.
2.	Docker Compose Configuration: Configured the Docker Compose YAML file to define services, including build instructions for building Docker images.
3.	Building Images: Executed the Docker Compose command to build Docker images from the provided Dockerfiles and configurations.
4.	Running Containers: Utilized Docker Compose to start containers for each microservice, ensuring all dependencies are met and services are interconnected.
5.	Verification: Checked the status of running containers and accessed the application through the browser to ensure successful deployment.
6.	Testing: Tested various functionalities of the application, including user registration, login, and product browsing, to validate the deployment.

## 🥇 Results 

The deployment of the EMart Microservices Application was successfully completed using Docker containers. Key achievements include:

* Demonstrated the deployment of a microservices-based application, showcasing the benefits of scalability, flexibility, and independent development.
* Utilized Docker containers and Docker Compose for easy management and deployment of microservices, ensuring consistency across different environments.
* Verified the functionality of the application, including user registration, login, and product browsing, to validate the deployment process.

<img width="953" alt="Screenshot_2" src="https://github.com/debasishdtt/microservice_project/assets/81139107/b2f2e27a-a9d0-42b3-8c94-1cb0dd2413a1">

<p align="center">Fig. 2: Accessing from web</p> 

## 🔚 Conslusion

The deployment of the EMart Microservices Application using Docker containers exemplifies the advantages of microservices architecture in modern software development. By breaking down the application into independent services and utilizing containers for deployment, the application achieves scalability, flexibility, and ease of management. This project serves as a practical demonstration of microservices deployment and highlights its relevance in building robust and scalable software solutions.

## 🌱 Room for Growth

While the deployment of the EMart Microservices Application represents a significant achievement in showcasing the capabilities of microservices architecture, there are several areas for potential growth and enhancement:
1.	**Scaling Infrastructure:** As the user base and traffic to the application grow, there will be a need to scale the infrastructure dynamically to handle increased load. Implementing auto-scaling mechanisms and load balancers can ensure that the application remains responsive and available under varying workloads.
2.	**Container Orchestration:** While Docker Compose provides a convenient way to manage containers locally, transitioning to a container orchestration platform such as Kubernetes can offer more advanced features for managing, scaling, and monitoring containerized applications in production environments. Kubernetes provides capabilities like service discovery, rolling updates, and automated scaling, which can enhance the resilience and scalability of the application.
3.	**Continuous Integration/Continuous Deployment (CI/CD):** Implementing CI/CD pipelines can streamline the deployment process, allowing for automated testing, build, and deployment of microservices. Integrating tools like Jenkins, GitLab CI/CD, or GitHub Actions can enable frequent and reliable releases, reducing manual intervention and improving the agility of the development process.
4.	**Microservices Refactoring:** As the application evolves and new features are added, there may be opportunities to refactor existing microservices for better performance, scalability, or maintainability. Decomposing monolithic services further into smaller, more specialized microservices can improve isolation, facilitate independent development, and enhance fault tolerance.
5.	**Service Monitoring and Logging:** Implementing robust monitoring and logging solutions is crucial for gaining insights into the performance and health of microservices. Integrating tools like Prometheus, Grafana, ELK Stack (Elasticsearch, Logstash, Kibana), or centralized logging platforms can help track metrics, detect anomalies, and troubleshoot issues efficiently, ensuring the reliability and stability of the application.
6.	**Security Considerations:** Enhancing the security posture of the application is paramount to safeguarding sensitive data and preventing unauthorized access. Implementing security best practices such as encryption, authentication, and authorization mechanisms, as well as conducting regular security audits and vulnerability assessments, can mitigate risks and ensure compliance with regulatory requirements.
7.	**Optimization for Cloud-Native Environment:** Leveraging cloud-native technologies and services can further optimize the application for cloud environments. Migrating to serverless computing, utilizing managed services like AWS Lambda, Azure Functions, or Google Cloud Functions, and adopting cloud-native databases such as Amazon DynamoDB or Google Cloud Spanner can reduce operational overhead and improve scalability and resilience.
In conclusion, the EMart Microservices Application has immense potential for growth and enhancement, offering opportunities to further optimize, scale, and secure the application infrastructure while delivering value to users and stakeholders. By embracing emerging technologies and best practices, the application can continue to evolve and adapt to meet the evolving needs of modern e-commerce platforms.



