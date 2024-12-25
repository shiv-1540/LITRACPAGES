# LITARCPAGES

A Functional Blog Posting Website developed during our Full Stack Development Internship at MIT Academy of Engineering, Alandi, Pune (23rd June to 10th August 2024) as part of the Super30 Batch under the mentorship of Jayesh Raut Sir.

---

## 🚀 Project Overview

LITARCPAGES is a comprehensive blogging platform designed with the following functionalities:

- **User Interaction**: View, create, and edit posts.
- **Publisher Controls**: Manage posts—create, update, or delete them.
- **Admin Dashboard**: Enable/disable users, manage user roles, and handle post visibility.

---

## 💻 Key Features

1. **User Authentication and Profile Management**
2. **Post Creation and Publishing Functionality**
3. **Admin Panel for Managing Users and Content**
4. **Real-time Updates for Seamless Content Management**

---

## 🔧 Technologies & Tools Used

### Frontend:
- React.js
- HTML5
- CSS3
- JavaScript

### Backend:
- Node.js
- Express.js

### Database:
- MySQL

### Tools:
- Git & GitHub
- Postman
- MySQL Workbench
- VS Code

---

## 📊 Database Design

### ER Diagram

![Database ER Diagram](path/to/er-diagram.png) <!-- Replace with the actual image path -->

### Table Schema

#### Users Table:
| Field         | Type         | Description                     |
|---------------|--------------|---------------------------------|
| id            | INT          | Primary key, Auto Increment     |
| name          | VARCHAR(255) | User’s full name               |
| email         | VARCHAR(255) | Unique email address            |
| password      | VARCHAR(255) | Encrypted password              |
| role          | ENUM         | User roles: [user, publisher]   |
| is_active     | BOOLEAN      | Status of user account          |

#### Posts Table:
| Field         | Type         | Description                     |
|---------------|--------------|---------------------------------|
| id            | INT          | Primary key, Auto Increment     |
| title         | VARCHAR(255) | Title of the post               |
| content       | TEXT         | Content of the post             |
| created_at    | DATETIME     | Timestamp of creation           |
| updated_at    | DATETIME     | Timestamp of last update        |
| author_id     | INT          | Foreign key, references Users   |

---

## 🌐 Screenshots

### Homepage:
![Homepage Screenshot](path/to/homepage-screenshot.png) <!-- Replace with actual image path -->

### Admin Dashboard:
![Admin Dashboard Screenshot](path/to/admin-dashboard-screenshot.png) <!-- Replace with actual image path -->

---

## 👨‍💻 What We Learned

- Comprehensive full-stack development experience.
- Enhanced skills in collaborative teamwork and project management.
- Familiarity with tools like Postman and MySQL Workbench.
- A deeper understanding of web development principles, from frontend to backend integration.

---

## 🙏 Acknowledgments

A heartfelt thanks to:

- **Jayesh Raut Sir**: For his invaluable mentorship.
- **CORE-DECIMAL SOLUTIONS**: For providing this amazing opportunity.
- **Faculty Members**: Dr. Amar Panchal (PhD), Dr. Anuradha Pawar, Dr. Shitalkumar A. Jain, and others from MIT Academy of Engineering.
- **Team Members**: Vaishnavi Kedar, Sayuj Singh, Utkarsh Shirbhate, and Bhavesh Jadhav—your dedication and collaboration made this project a success!

---

## 🌟 Conclusion

This internship has been a transformative learning experience, solidifying our passion for web development and equipping us with essential skills for future projects. We look forward to applying these insights to new challenges and making a positive impact in the field of technology.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Connect with Us

Feel free to reach out for collaboration or to learn more about the project:

- **Email**: [shivshankar.ghyar@example.com](mailto:shivshankar.ghyar@example.com)
- **GitHub**: [GitHub Profile](https://github.com/ShivshankarGhyar) <!-- Replace with actual GitHub profile URL -->
