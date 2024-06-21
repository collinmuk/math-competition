

```markdown
# Math Competition System

The Math Competition System is a Java-based application designed to manage math competitions, allowing participants to register, view challenges, attempt challenges, and administrators to manage challenges and participants.

## Features

- **Participant Management**: Register new participants with username, name, email, date of birth, school ID, and profile image.
- **Challenge Viewing**: Participants can view available challenges.
- **Challenge Attempt**: Participants can attempt challenges, answering multiple-choice questions.
- **Admin Dashboard**: Administrators can manage schools, challenges, and view reports.

## Technologies Used

- Java
- MySQL
- Apache Maven
- Apache POI (for Excel file handling)
- Socket Programming (for client-server communication)

## Installation

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- Apache Maven
- MySQL Server

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/collinmuk/MathCompetitionSystem.git
   cd MathCompetitionSystem
   ```

2. Import the project into IntelliJ IDEA or your preferred IDE.

3. Configure the database:
   - Create a MySQL database named `math_competition_system`.
   - Update the database connection details in `DatabaseManager.java`.

4. Build the project using Maven:
   ```bash
   mvn clean install
   ```

5. Run the server:
   ```bash
   java -classpath target/classes Server
   ```

6. Run the client:
   ```bash
   java -classpath target/classes Client
   ```

## Usage

1. Start the server application as instructed above.
2. Start the client application and follow the command-line prompts to register, view challenges, and attempt challenges.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```

### Notes:
- Ensure the GitHub repository URL (`git clone` command) matches your actual repository URL.
- Adjust database configuration and other instructions based on your project specifics.
- Customize further as per your project's structure, requirements, and any additional features or functionality.

This README template should provide a clear and structured introduction to your Math Competition System project, helping potential users and contributors understand its purpose, setup, and usage.
