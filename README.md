# E-Learning Management System

An E-Learning Management System built using PHP and MySQL to facilitate online learning and teaching. This system allows administrators, teachers, and students to interact in a structured and efficient way.

## Features

- **User Management**
  - Admin panel to manage users (Admins, Teachers, and Students).
  - Role-based access control.

- **Course Management**
  - Teachers can create and manage courses.
  - Students can enroll in available courses.

- **Content Delivery**
  - Upload and manage course materials such as video.
  - Organized by topics and modules.

- **Assessment**
  - Quizzes and assignments.
  - Automatic grading for objective questions.

- **Communication**
  - Messaging system for teacher-student interaction.
  - Notifications for important updates.

- **Reporting**
  - Track student progress and performance.
  - Generate reports for teachers and admins.

## Technologies Used

- **Frontend**
  - HTML, CSS, JavaScript

- **Backend**
  - PHP

- **Database**
  - MySQL

- **Other Tools**
  - Bootstrap for responsive design

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/e-learning-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd e-learning-management-system
   ```

3. Import the database:
   - Create a MySQL database.
   - Import the provided SQL file located in the `database` folder.

4. Configure the application:
   - Update the `config.php` file with your database credentials:
     ```php
     <?php
     define('DB_HOST', 'localhost');
     define('DB_USER', 'your_username');
     define('DB_PASS', 'your_password');
     define('DB_NAME', 'your_database_name');
     ?>
     ```

5. Start the server:
   - If you're using XAMPP or WAMP, place the project folder in the `htdocs` directory.
   - Start Apache and MySQL services.

6. Access the application:
   - Open your browser and navigate to `http://localhost/e-learning-management-system`.

## Usage

1. **Admin**: Manage users, courses, and overall system settings.
2. **Teacher**: Create courses, upload materials, and manage assessments.
3. **Student**: Enroll in courses, access materials, and complete assessments.

## Contribution

Contributions are welcome! If you'd like to improve the project, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.



