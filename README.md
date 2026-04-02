<div align="center">

# 📋 Contact Manager

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6DB33F&center=true&vCenter=true&width=500&lines=Manage+Your+Contacts+Seamlessly;Secure+%7C+Responsive+%7C+Fast" alt="Typing SVG" />

<br/>

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)

<br/>

![GitHub repo size](https://img.shields.io/github/repo-size/shubhamborate25/ContactManager?color=6DB33F&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/shubhamborate25/ContactManager?color=ED8B00&style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/shubhamborate25/ContactManager?style=flat-square&color=yellow)
![GitHub forks](https://img.shields.io/github/forks/shubhamborate25/ContactManager?style=flat-square&color=blue)
![License](https://img.shields.io/badge/License-MIT-red?style=flat-square)

</div>

---

## 🌟 Overview

**Contact Manager** is a full-stack, responsive web application built with **Spring Boot** that lets users securely manage their personal contacts. It features a clean UI, role-based authentication, image uploads, smart search, and paginated contact lists — all in one place.

> 💡 Built to demonstrate real-world Spring Boot capabilities including Spring Security, Hibernate ORM, Thymeleaf templating, and MySQL integration.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔐 **Secure Auth** | User registration & login powered by Spring Security |
| 📇 **Contact CRUD** | Add, view, update, and delete contacts with ease |
| 🖼️ **Profile Pictures** | Upload and display a photo for each contact |
| 📄 **Pagination** | Smooth navigation through large contact lists |
| 🔍 **Search & Filter** | Quickly find contacts by name or details |
| 📱 **Responsive UI** | Fully optimized for mobile, tablet, and desktop |
| ⚡ **Dynamic Views** | Thymeleaf-powered server-side rendering |

---

## 🛠️ Tech Stack

### Backend
- ☕ **Java** — Core language
- 🌱 **Spring Boot** — Application framework
- 🔒 **Spring Security** — Authentication & authorization
- 🗄️ **Hibernate / JPA** — ORM & database management

### Frontend
- 🍃 **Thymeleaf** — Server-side templating engine
- 🎨 **Bootstrap 5** — Responsive UI components
- 💅 **HTML5 / CSS3 / JavaScript** — Core web technologies

### Database
- 🐬 **MySQL** — Relational database

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Java 17+
- Maven 3.x
- MySQL 8.x

### Installation
```bash
# 1. Clone the repository
git clone https://github.com/shubhamborate25/ContactManager.git
cd ContactManager

# 2. Configure your database in src/main/resources/application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/contact_manager
spring.datasource.username=your_username
spring.datasource.password=your_password

# 3. Build and run
mvn spring-boot:run
```

> 🌐 Open your browser and visit: `http://localhost:8080`

---

## 📁 Project Structure
```
ContactManager/
├── src/
│   ├── main/
│   │   ├── java/com/contactmanager/
│   │   │   ├── controller/       # MVC Controllers
│   │   │   ├── model/            # Entity classes
│   │   │   ├── repository/       # JPA Repositories
│   │   │   ├── service/          # Business logic
│   │   │   └── config/           # Spring Security config
│   │   └── resources/
│   │       ├── templates/        # Thymeleaf HTML templates
│   │       ├── static/           # CSS, JS, images
│   │       └── application.properties
├── pom.xml
└── README.md
```

---

## 🔗 Links

<div align="center">

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shubhamborate25/ContactManager)
[![Issues](https://img.shields.io/badge/Report_Bug-EA4335?style=for-the-badge&logo=bugsnag&logoColor=white)](https://github.com/shubhamborate25/ContactManager/issues)
[![Pull Requests](https://img.shields.io/badge/Contribute-6DB33F?style=for-the-badge&logo=git&logoColor=white)](https://github.com/shubhamborate25/ContactManager/pulls)

</div>

---

## 🤝 Contributing

Contributions are always welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with ❤️ by **[Shubham Borate](https://github.com/shubhamborate25)**

⭐ If you found this project helpful, please give it a star!

</div>
