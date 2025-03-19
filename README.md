# MyTutor 🎓

## 📌 Project Overview
**MyTutor** is a web-based application designed to modernise Tutor and Teaching Assistant (TA) management at the **University of Cape Town (UCT)**. It streamlines the application process, improves scheduling, and enhances administrative workflows. The system is built with **Java, Vaadin, and Spring Boot**, ensuring a **scalable, modular, and secure** solution for course administrators, lecturers, and students.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/9c61fe16-fc9b-4c64-bb57-83848e639e79)
![image](https://github.com/user-attachments/assets/ecc8c74a-e201-4cb4-ad38-1e9755246fb7)
![image](https://github.com/user-attachments/assets/eda1b2a5-9bb7-4929-b564-5c96bd5f10a6)
![image](https://github.com/user-attachments/assets/7377244c-7018-4ee0-98d0-15fbb3ef8794)

### 🔹 Key Features
- 🔐 **User Roles & Authentication** - Secure login for administrators, lecturers, tutors, and students.
- 📄 **Tutor & TA Applications** - Students can apply for positions with an intuitive interface.
- 📅 **Easy-to-Use Scheduling** - Efficiently manage tutor assignments and schedules.
- ⚙️ **Robust Admin Management** - Course convenors can monitor tutor performance and allocate responsibilities.
- 🏗️ **Scalability & Modularity** - Designed for easy expansion and integration with existing UCT systems.
- 🌙 **Dark Mode Support** - Users can toggle between light and dark mode for a more comfortable viewing experience.

## 🛠️ Tech Stack
- **Java 17** - Backend logic & business rules
- **Spring Boot** - Framework for building scalable web applications
- **Vaadin** - Frontend UI framework for Java-based web applications (more on this below)
- **MySQL** - Relational database management
- **Maven** - Dependency management and build automation
- **Git & GitLab** - Version control & collaboration
- **REST APIs** - Seamless communication between frontend and backend

## 🤔 What is Vaadin?
[Vaadin](https://vaadin.com/) is a Java-based web framework that simplifies building **modern, interactive UIs** without requiring extensive JavaScript or frontend coding. Unlike traditional web frameworks that rely on HTML and JavaScript, **Vaadin allows developers to create full-stack applications using only Java**. It is particularly useful for business applications where maintainability and security are priorities.

### 🔹 Why Vaadin for MyTutor?
- **Full-stack Java development** - No need for additional frontend technologies like React or Angular.
- **Secure & Stateful UI** - Reduces security risks by managing UI state on the server side.
- **Rapid Prototyping** - Faster UI development with pre-built components and themes.
- **Excellent Integration with Spring Boot** - Seamlessly connects to backend services and databases.
- **Efficient OOP Implementation** - By leveraging Java, we ensured that **Object-Oriented Programming (OOP)** principles were efficiently applied, resulting in a modular, maintainable, and seamless UI.

## 👨‍💻 Team Members
This project was developed as part of our **Undergraduate Computer Science Capstone Project (2023)**:
- **VWSJUL003** - Julyan van der Westhuizen
- **WLLCAS004** - Cassandra Wallace
- **WLSETH003** - Ethan Wilson

## 📂 Alternative Project Repository
🔗 GitLab: [MyTutor Repository](https://gitlab.cs.uct.ac.za/capstone-elite/mytutor)

## 🏗️ Installation & Setup
### 📌 Prerequisites
Ensure you have the following installed:
- **Java 17**
- **Maven** (for dependency management)

### ⚠️ Important Note
🚫 **No active deployment**: Currently, MyTutor is not hosted online. To test the system, you will need to run it locally.

### 🧪 Test User Accounts
Use the following test accounts to explore different user roles:

| Role            | Email                        | Password |
|----------------|----------------------------|----------|
| Administrator  | testadmin@test.com         | 1234     |
| Course Convenor | johnbright@gmail.com       | 1234     |
| Teaching Assistant (TA) | smttay001@myuct.ac.za | 1234     |
| Tutor          | blesam001@myuct.ac.za      | 1234     |
| Student        | Sign up via login page     | N/A      |

🔹 **Key Role Capabilities:**
- **Course Convenors** can accept TAs and Tutors for their course.
- **TAs** can approve tutors, manage schedules, and view statistics.
- **Tutors** can view schedules and sign up for tutoring sessions.
- **Students** can sign up and apply to be tutors for courses they have completed.

### 📂 Project Structure
The project contains the following main files:
- 📄 **VWSJUL003_WLLCAS004_WLSETH003_Report.pdf** - Detailed project report and documentation.
- 📦 **VWSJUL003_WLLCAS004_WLSETH003_code.tar.gz** - Source code package.
- 📂 **Code Excerpts** - A separate folder containing most of our Java code files for easy demonstration and review. While the below installation steps remain the same, this folder allows for quick access to the actual code without needing to extract the compressed archive.

### 📥 Installation Steps
1. Clone this repository:
1. Extract the source code package:
   ```sh
   tar -xvzf VWSJUL003_WLLCAS004_WLSETH003_code.tar.gz
   cd mytutor
   ```
3. Build the project using Maven:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```
6. The local server will likely run on **port 37090**, but check the terminal output for confirmation. Access the application at:
   ```
   http://localhost:<PORT>
   ```
   (Replace `<PORT>` with the actual port displayed in the terminal.)

💡 **Note:** The installation process may take some time due to dependency resolution.

## 📑 Additional Documentation
For more details on the **design process, software architecture, and system diagrams**, refer to our project report:  
📄 **VWSJUL003_WLLCAS004_WLSETH003_Report.pdf** (included in the repository)

---

💡 **Contributions & Feedback** are welcome! If you have any suggestions or want to collaborate, feel free to reach out! 🎉
