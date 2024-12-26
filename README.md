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
## Demonstartion Video 
- **https://drive.google.com/file/d/1iEDCNORDlHuyZCgx2IQwMc3D3HekdNmp/view?usp=sharing**

## 🔧 Technologies & Tools Used

### Frontend:
- React.js![th](https://github.com/user-attachments/assets/76f1e264-33f8-4c54-bfe9-b200e327ab60)

- Tailwind CSS ![th](https://github.com/user-attachments/assets/3b246c27-4196-4d90-93aa-13841ce0da22)

- JavaScript![th](https://github.com/user-attachments/assets/9a83aee6-714d-481d-b1de-903ac3162d77)


### Backend:
- Node.js![th](https://github.com/user-attachments/assets/01a86069-887a-4e8b-9958-df20c7204b4e)

- Express.js![th](https://github.com/user-attachments/assets/8d5a816b-d7ff-4f47-ae1a-9d42dc62fbb7)


### Database:
- MySQL![th](https://github.com/user-attachments/assets/20b57241-3439-4433-80c4-c5252baba4c4)

### Tools:
- Git & GitHub
- Postman
- MySQL Workbench
- VS Code
![WhatsApp Image 2024-07-01 at 10 19 20_cad5ba29](https://github.com/user-attachments/assets/54b3931c-58d8-4190-8c08-60593dafd8c1)

---

## 📊 Database Design

### ER Diagram

![WhatsApp Image 2024-06-23 at 22 04 37_fe81ccd2](https://github.com/user-attachments/assets/63b5bd88-0f19-49fc-a15b-bba6f0677fc8)


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
![Homepage Screenshot](https://github.com/user-attachments/assets/9220d228-d278-4492-9c98-3e04f4b5821b)

![HomePage](https://github.com/user-attachments/assets/cb6a3b31-278c-4aa4-b3ab-6d282ab55fa0)


### ProfilePage:
![Profile]  (https://github.com/user-attachments/assets/0c6263d0-eb4c-4766-9b87-a3cc3327967e)


### Admin Dashboard:

![WhatsApp Image 2024-09-19 at 18 39 04_f8159ac1](https://github.com/user-attachments/assets/4faeccbe-ecc1-44fc-ba37-9c178d9cb9c9)

![t](path/to/admin-dashboard-screenshot.png) <!-- Replace with actual image path -->

![Admin Dashboard Screensho](https://github.com/user-attachments/assets/ebf68abd-a7e4-4399-a2b6-83ebcd6822e4)

![WhatsApp Image 2024-09-19 at 18 39 05_dfbce714](https://github.com/user-attachments/assets/e3a054a3-ad42-4821-952c-b4a7f83ed9ba)
![WhatsApp Image 2024-09-19 at 18 39 04_1045c74e](https://github.com/user-attachments/assets/135060bc-6fe0-4a4d-a28e-61ae08fba966)




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

This internship has been a transformative learning experience, solidifying my passion for web development and equipping us with essential skills for future projects. We look forward to applying these insights to new challenges and making a positive impact in the field of technology.

---

## 📜 License

This project is licensed under the MITAOE License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Connect with Me

Feel free to reach out for collaboration or to learn more about the project:

- **Email**: [shivghyar538@gmail.com](mailto:shivghyar538@gmail.com)
- **GitHub**: [GitHub Profile](https://github.com/shiv-1540)
- **Linkdein**: [Linkdein Profile](https://www.linkedin.com/in/shivshankar-ghyar-870972289)
