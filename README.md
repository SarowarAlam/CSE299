
```markdown
# Isolation Centre Management System (ICMS)

## Project Overview
The **Isolation Centre Management System** (ICMS) is a comprehensive web application designed to simplify the management of isolation centers. It offers user-friendly interfaces for administrators, staff, and patients to efficiently manage operations, patient records, and daily tasks. The platform ensures a seamless experience with robust backend functionality and a modern, responsive frontend.

---

## Features

### Admin Panel
- **User Management**: Add, update, and delete users such as staff or patients.
- **Dashboard**: Monitor isolation center activities, generate reports, and view summaries.
- **Task Assignment**: Assign tasks to staff members and track their progress.

### Staff Panel
- **Patient Management**: Update patient records, manage check-ins, and view health updates.
- **Daily Logs**: Record daily observations and updates for assigned patients.
- **Notifications**: Receive task assignments and important alerts.

### Patient Portal
- **Self-Check-In**: Patients can register themselves upon arrival.
- **Health Tracking**: View personalized health updates and isolation details.
- **Support Requests**: Submit requests for assistance or resources.

---

## File Structure

### Frontend
- `index.html`: Main landing page of the application.
- `Admin_Login.html`: Admin-specific login interface.
- `Userprofile.html`: Profile page for patients and staff.
- `assets/css/`: Contains stylesheets for responsive and modern designs.
- `assets/js/`: Contains JavaScript for interactivity and form validations.

### Backend
- `admin/`: PHP scripts for admin functionalities like user and task management.
- `vendor/`: Contains third-party libraries and plugins.
- `config/`: Configuration files for database connections and system settings.

### Database
- `database.sql`: SQL file for initializing the database schema and tables.
- Includes tables for users, patients, logs, and task assignments.

---

## Installation and Setup

### Prerequisites
- **Web Server**: Apache, Nginx, or equivalent.
- **PHP**: Version 7.4 or higher.
- **MySQL**: Version 5.7 or higher.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Isolation-Centre.git
   cd Isolation-Centre
   ```
2. Import the database:
   - Open your database management tool (e.g., phpMyAdmin).
   - Import the `database.sql` file located in the project root.

3. Configure the application:
   - Navigate to the `config/` folder and update `config.php` with your database credentials.

4. Start the application:
   - For local development:
     ```bash
     php -S localhost:8000
     ```
   - For deployment, upload files to a web server.

---

## Screenshots

### Admin Dashboard
![Admin Dashboard](path/to/screenshot/admin-dashboard.png)

### Staff Panel
![Staff Panel](path/to/screenshot/staff-panel.png)

### Patient Portal
![Patient Portal](path/to/screenshot/patient-portal.png)

---

## Technologies Used

### Frontend
- **HTML5**: Semantic and accessible markup.
- **CSS3**: Modern, responsive stylesheets.
- **JavaScript**: Client-side interactivity and validations.
- **Bootstrap**: Responsive framework for consistent styling.

### Backend
- **PHP**: Server-side logic and database handling.
- **MySQL**: Database for storing and managing application data.

### Libraries and Plugins
- **jQuery**: Simplified DOM manipulation.
- **Toastr.js**: Notifications and alerts.
- **SweetAlert**: Enhanced modal dialogs.
- **Select2**: Improved dropdowns.

---

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request for review.

---

## Contact
If you have any questions or need further assistance, please feel free to contact:

- **Name**: Sarowar Alam
- **Email**: sarowaralam40@gmail.com
- **GitHub**: [https://github.com/your-username](https://github.com/SarowarAlam)


