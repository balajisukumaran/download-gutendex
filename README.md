# Bulk Download Project Gutenberg Books

## About

This Java console application enables users to bulk download books from the Project Gutenberg collection via the Gutendex API (https://gutendex.com/). It is streamlined for ease of use and designed for efficient bulk downloading.

## Getting Started

Follow these instructions to set up and run the application on your local machine for development and operational purposes.

### Prerequisites

- Java JDK 8 or higher installed on your machine
- Access to the command line interface

### Setup

1. **Clone the Repository**

    Clone the project repository to your local machine using the following command:
    ```bash
    git clone https://yourrepositorylink.com/project.git
    ```
    Replace `https://yourrepositorylink.com/project.git` with the actual URL of your repository.

2. **Navigate to the Project Directory**

    Change to the project directory where the `pom.xml` file is located:
    ```bash
    cd path-to-project
    ```
    Replace `path-to-project` with the actual path to your project directory.

3. **Modify Constants**

    Modify the `Constants.java` file with the necessary configuration:
    ```plaintext
    src/main/java/org/example/Constants.java
    ```
    Open this file in your text editor or IDE and configure the necessary constants such as API keys or download parameters.

4. **Clean and Package the Application**

    Clean and package the application using Maven Wrapper:
    ```bash
    .\mvnw.cmd clean package
    ```

5. **Execute the Packaged JAR**

    Run the packaged JAR file:
    ```bash
    java -jar target/gutendex-1.0-SNAPSHOT.jar
    ```

## Usage

Execute the JAR file to begin the bulk download process. The application will interface with the Gutendex API and download books according to the specifications in `Constants.java`.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Clone your fork to your local machine:
    ```bash
    git clone https://github.com/your-username/project.git
    ```
3. Create a new feature branch:
    ```bash
    git checkout -b my-new-feature
    ```
4. Make your changes.
5. Commit your changes with a clear commit message:
    ```bash
    git commit -m "Add some feature"
    ```
6. Push the changes to your fork:
    ```bash
    git push origin my-new-feature
    ```
7. Submit a pull request to the upstream repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
