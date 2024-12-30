# Spring Boot Bank Project with Daytona

This repository contains a sample bank application built using Spring Boot. The project demonstrates basic banking functionalities such as account creation, deposit, and withdrawal. It is pre-configured with a `devcontainer.json` file to enable a standardized development environment using Daytona.

### My Blog :-
[Integrating Daytona into Your Spring Boot Bank Application](https://dev.to/harshsinghcs/integrating-daytona-into-your-spring-boot-bank-application-312o)

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**:  
   Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  

2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/harshsinghcs/SpingBoot-BankProject-withDaytona.git

3. **Reopen in Container**:

   If using VS Code, you will be prompted to reopen the project in the dev container.

4. **Start the Application**:
   Build and run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   
✨ Features

Account Creation: Create a new bank account via REST API.
Deposit: Deposit money into an account.
Withdrawal: Withdraw money from an account.
Pre-configured Dev Container: Develop in a consistent environment using Daytona and VS Code.
Java 17 Support: The project uses Java 17 as the runtime.


## 🛠️ API Endpoints  

| HTTP Method | Endpoint                     | Description                   |
|-------------|------------------------------|-------------------------------|
| `POST`      | `/api/accounts`              | Create a new account          |
| `GET`       | `/api/accounts/{id}`         | Retrieve account details      |
| `POST`      | `/api/accounts/{id}/deposit` | Deposit money into an account |
| `POST`      | `/api/accounts/{id}/withdraw`| Withdraw money from an account|


## 📂 Project Structure  

```plaintext
src/
├── main/
│   ├── java/com/bankchor/
│   │   ├── controller/       # REST Controller
│   │   ├── entity/           # JPA Entity
│   │   ├── service/          # Business Logic
│   │   ├── repository/       # Data Access Layer
│   ├── resources/
│       ├── application.properties # Configuration

```

## 🔗 Resources  

- [Spring Boot Documentation](https://spring.io/projects/spring-boot)  
- [Daytona Documentation](https://www.daytona.io/docs/)  
- [Maven Documentation](https://maven.apache.org/guides/index.html)  
