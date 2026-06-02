# Employee Registration & Login System

A simple Flask web application that allows employees to register and log in using their Employee ID and password. User information is stored in a local text file (`biodata.txt`) using JSON format.

## 🚀 Features

- Employee Registration
- Employee Login Authentication
- JSON-based Data Storage
- Welcome Page After Successful Login
- Lightweight and Easy to Understand
- Beginner-Friendly Flask Project

## 🛠️ Technologies Used

- Python 3
- Flask
- JSON
- HTML

## 📁 Project Structure

```text
Employee-Registration-Login/
│
├── app.py
├── biodata.txt
├── templates/
│   └── welcome.html
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/employee-registration-login.git
cd employee-registration-login
```

### Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install flask
```

## ▶️ Running the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 📝 Registration

The application collects the following details:

- Name
- Age
- Gender
- Employee ID
- Password

The data is stored in `biodata.txt` as JSON records.

Example:

```json
{
  "Name": "John Doe",
  "Age": "25",
  "Gender": "Male",
  "Employee ID": "EMP001",
  "Password": "password123"
}
```

## 🔐 Login

Users can log in using:

- Employee ID
- Password

The application validates credentials from `biodata.txt` and redirects valid users to the welcome page.

## 📌 Routes

| Route | Method | Description |
|---------|---------|-------------|
| `/sign` | POST | Register a new employee |
| `/login` | POST | Login with Employee ID and Password |

## ⚠️ Security Note

This project is intended for educational purposes only.

Current limitations:

- Passwords are stored in plain text.
- No database integration.
- No session management.

For production use, implement:

- Password hashing using `werkzeug.security`
- Database storage (SQLite, MySQL, PostgreSQL)
- Session management
- CSRF protection
- Input validation

## 🔮 Future Enhancements

- Database Integration
- Password Encryption
- Employee ID Uniqueness Validation
- User Sessions
- Logout Functionality
- Admin Dashboard
- Profile Management

## 🤝 Contributing

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## ⭐ Support

If you found this project useful, please consider giving it a star on GitHub.
