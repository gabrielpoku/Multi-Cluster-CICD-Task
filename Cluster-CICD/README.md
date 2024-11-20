## Task Master Pro Application Deployed

![architecture drawio](https://github.com/user-attachments/assets/6876bd31-d665-4abb-bfb9-569d10e03aee)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Task Master Pro is a task management application built using Java. It provides robust features to help users create, manage, and track tasks. This project aims to demonstrate best practices in Java development, including project structure, coding standards, and documentation.

## Features

- Create, update, and delete tasks
- Mark tasks as complete or incomplete
- User authentication and authorization

## Installation

### Prerequisites

- Java Development Kit (JDK) 17 or later
- Apache Maven 3.6.0 or later
- A database (H2)

### Steps

1. Clone the repository:

    ```sh
    git clone https://github.com/MaryamMairaj123/Multi-Cluster-Mega-CICD-Task-Master-Pro.git
    cd Multi-Cluster-Mega-CICD-Task-Master-Pro
    ```

2. Configure the database:

    Update the `application.properties` file with your database configuration.

3. Build the project:

    ```sh
    mvn clean install
    ```

4. Run the application:

    ```sh
    mvn spring-boot:run
    ```

## Usage

Once the application runs, you can access it at `http://localhost:8080`. You can use the web interface to manage your tasks.

### Endpoints

- `/tasks` - View and manage tasks
- `/tasks/{id}` - View, update, or delete a specific task
- `/login` - User login
- `/register` - User registration

## Contributing

We welcome contributions to improve Task Master Pro. If you have a feature request, bug report, or improvement suggestion, please open an issue or submit a pull request.

### Steps to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

maryammairaj53@gmail.com, 

https://www.linkedin.com/in/maryam-mairaj-0161a2176/ 

Happy coding!
