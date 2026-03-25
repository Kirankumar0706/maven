# Simple Maven App

This project is a simple Java application built using Maven. It demonstrates basic Java programming concepts and unit testing with JUnit.

## Project Structure

```
simple-maven-app
├── src
│   ├── main
│   │   └── java
│   │       └── App.java
│   └── test
│       └── java
│           └── AppTest.java
├── pom.xml
└── README.md
```

## Files Overview

- **src/main/java/App.java**: Contains the `App` class with a method `add(int a, int b)` that returns the sum of two integers.
  
- **src/test/java/AppTest.java**: Contains the `AppTest` class with a test method `testAdd()` that verifies the functionality of the `add` method in the `App` class.

- **pom.xml**: The Maven project configuration file that includes project metadata and dependencies, specifically JUnit for testing.

## Getting Started

### Prerequisites

- Java (JDK 8 or above)
- Maven
- Git

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Kirankumar0706/maven.git
   ```

2. Navigate to the project directory:
   ```
   cd simple-maven-app
   ```

3. Build the project using Maven:
   ```
   mvn clean install
   ```

### Running Tests

To run the tests, use the following Maven command:
```
mvn test
```

This will execute the tests defined in the `AppTest` class and provide the results in the console.

## License

This project is licensed under the MIT License.