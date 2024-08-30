# Complain-Management-System
Complain Management System offers an environmental crimes significantly threaten wildlife, forestry, and our precious environmental  resources. The absence of a streamlined reporting and management system has hindered the  ability of Wildlife Conservation and Forest Conservation institutions to take decisive actions  against these crimes.

## Installation

### Prerequisites
- XAMPP Server (Download and install from [here](https://www.apachefriends.org/index.html))
- PHP latest
- MySQL

### Steps

1. **Clone the repository:**
   ```bash
   git clone git@github.com:YourUsername/Complain-Management-System.git

2. **Move the project folder to the XAMPP htdocs directory:**
   ```bash
   cp -r <project-folder> /path/to/xampp/htdocs/

3. **Start the XAMPP control panel:** 
- Launch the XAMPP control panel.
- Start the Apache and MySQL modules.

4. **Database Setup:**
- Open phpMyAdmin in your web browser.
- Create a new database called `cpmsphp`.
- Import the `cpmsphp.sql` file located in the project folder.

5. **Configuration:**
- Ensure your `config.php` or `db.php` file is properly configured with your MySQL credentials.

6. Access the Website:
- Open your web browser and navigate to `http://localhost/Complain-Management-System/`

## Usage 
- Use `admin-login.php` to access the admin dashboard.
- Officers can log in or register using `officer-login.php` and `officer-register.php`.
- Users can sign up and log in using `signup.php` and `index.php` respectively.
- After logging in, users can file complaints, view their profile, and manage their complaints through `profile.php` and `message.php`.

## Contributing
We welcome contributions from the community. Please follow our contribution guidelines for details on how to contribute to ComplainManagementSystem.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
```bash
Make sure to replace `git@github.com:YourUsername/Complain-Management-System.git` and `Complain-Management-System` with the appropriate values for your project.
