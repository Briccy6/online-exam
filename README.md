# Online Exam System

An Online Exam System built using PHP to help administer and manage online exams efficiently.

## Features
- User authentication and role management (Admin, Teacher, and Student).
- Create, edit, and delete exams and questions.
- Students can attempt exams and view results.
- Admin dashboard to oversee activity and manage users.
- Secure and scalable design.

## Technologies Used
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, and JavaScript

## Installation Guide

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Briccy6/online-exam-system.git
   cd online-exam-system
   ```

2. **Set up the database:**
   - Import the `online_exam.sql` file (included in the repository) into your MySQL database.
   - Update the database configuration in `config.php` with your database credentials.

3. **Start the server:**
   - Use XAMPP, WAMP, or any local server of your choice.
   - Place the project folder in the server's root directory (e.g., `htdocs` for XAMPP).

4. **Access the application:**
   - Open your web browser and go to `http://localhost/online-exam-system`.

## Usage
- **Admin:**
  - Manage users (create, update, delete).
  - Oversee exams and results.
- **Teacher:**
  - Create and manage exams.
  - View and grade student submissions.
- **Student:**
  - Attempt assigned exams.
  - View exam results and feedback.

## Contributing
Contributions are welcome! To contribute:
- Fork the repository.
- Create a new branch (`git checkout -b feature-name`).
- Make your changes and commit them (`git commit -m 'Add feature'`).
- Push to your branch (`git push origin feature-name`).
- Create a pull request.

## Credits
Developed by **Alain Brian**.

## License
This project is licensed under the [MIT License](LICENSE).
