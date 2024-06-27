
 Project Overview
This project is a comprehensive Quiz Web Application designed to allow users to sign up, log in, take quizzes, view their answers, and compare them with the correct answers. It provides a seamless and intuitive user experience, with features ensuring secure authentication and efficient quiz management.

 Features
-User Authentication: Secure sign-up and login functionality.
- Quiz Taking: Users can take quizzes with multiple-choice questions.
- Answer Submission: Users can submit their answers and receive immediate feedback.
- Answer Review: Users can view their submitted answers and compare them with the correct answers.
- User Dashboard: Personalized dashboard showing quiz history and performance.

 Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Java (NetBeans),Tomcat Server
- Database: MySQL
- Authentication: Custom authentication with session management
- Version Control: Git, GitHub

 Installation and Setup

1. Clone the repository:
    git clone https://github.com/your-username/quiz-web-app.git
    cd quiz-web-app
2. Open the project in NetBeans:
    - Launch NetBeans IDE.
    - Open the cloned project by selecting `File > Open Project` and navigating to the project directory.
3. Set up the MySQL database:
    - Create a new database in MySQL.
    - Import the provided SQL script (`database/schema.sql`) to set up the required tables.
4. Configure the application:
    - Open the `src/main/resources/application.properties` file.
    - Update the database connection properties:
      	spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
      	spring.datasource.username=your_database_username
      	spring.datasource.password=your_database_password
5. Run the application:
    - In NetBeans, right-click on the project and select `Run`.
6. Access the application:
   	 Open your web browser and go to `http://localhost:8080`

 Usage
1. Sign Up: Create a new account by providing the necessary details.
2. Login: Use your credentials to log in to the application.
3. Take Quiz: Choose a quiz and start answering the questions.
4. Submit Answers: After completing the quiz, submit your answers.
5. View Answers: Check your answers and compare them with the correct answers.

 Acknowledgements
- Inspiration from various quiz and learning platforms.
- Community contributions and feedback.

Contact
For any inquiries or issues, please open an issue on GitHub or contact me at jayalakshmi2k3@gmail.com.
