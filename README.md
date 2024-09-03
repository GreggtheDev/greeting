
# Greetings Application

This is a simple Spring Boot application that serves a "Hello, World!" message through a REST endpoint.

## Project Overview

The project includes the following components:

- **`GreetingsApplication`**: The main entry point for the Spring Boot application.
- **`GreetingController`**: A REST controller that defines a single endpoint `/greeting` which returns a simple greeting message.

## Prerequisites

To run this application, ensure you have the following installed on your system:

- **Java Development Kit (JDK) 17** or later
- **Apache Maven 3.6.0** or later

### Installation of Prerequisites

- **Java Installation**:
  ```bash
  brew install openjdk@17
  export PATH="/usr/local/opt/openjdk@17/bin:$PATH"
  ```

- **Maven Installation**:
  ```bash
  brew install maven
  ```

## How to Run the Program

### Using an IDE (e.g., IntelliJ, Eclipse)

1. **Clone the repository** (if applicable) or download the project files.
2. **Open the project** in your preferred Java IDE.
3. **Build the project** (your IDE should handle this automatically if configured correctly).
4. **Run the `GreetingsApplication` class** directly from the IDE.
5. **Access the greeting**:
   - Open a web browser.
   - Visit `http://localhost:8080/greeting`.
   - You should see the message: `Hello, World!`.

### Using the Command Line

1. **Navigate to the project directory**:
    ```bash
    cd greetings-app
    ```
2. **Build and run the application** using Maven:
    ```bash
    mvn spring-boot:run
    ```
3. **Access the greeting**:
   - Open a web browser or use a `curl` command:
     ```bash
     curl http://localhost:8080/greeting
     ```
   - You should receive the response: `Hello, World!`.

## Project Structure

```plaintext
greetings-app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── greetings/
│   │   │               ├── GreetingsApplication.java
│   │   │               └── GreetingController.java
│   │   └── resources/
│   │       └── application.properties
├── pom.xml
└── README.md
```

## Technologies Used

- **Java 17**
- **Spring Boot 3.1.3**
- **Maven**

## Conclusion

This project demonstrates the basic setup of a Spring Boot application, including the creation of a RESTful web service. It's a starting point for more complex Spring Boot applications.
