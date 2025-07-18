# 🏥 Medical Appointment Booking Application

A **Java 8-based** full-stack application for managing medical appointments, designed for clinics and hospitals to streamline doctor-patient scheduling. This project is structured as a **Maven project**, built using clean code principles, modular design, and is fully documented using **JavaDocs**.

---

## 🔧 Tech Stack & Tools

- **Java 8** — Core backend logic and business functionality
- **Maven** — Build and dependency management
- **Servlets & JSP** — Web layer and dynamic content rendering
- **MySQL / H2 Database** — Backend database (pluggable DB layer)
- **Tomcat** — Deployment server
- **JUnit 5** — Unit testing framework
- **JavaDocs** — API documentation
- **Log4j** — Logging
- **HTML5/CSS3 & Bootstrap** — Frontend styling
- **Git** — Version control

---

## 📌 Features

- 🩺 Patient registration and authentication
- 👨‍⚕️ Doctor registration with specialization
- 📅 Book, view, and cancel appointments
- ⏰ Real-time appointment availability check
- 🔎 Search doctors by name or specialization
- 📬 Email confirmation (Optional SMTP integration)
- 🛡️ Role-based access control: Admin, Doctor, Patient
- 📈 Admin dashboard with appointment analytics
- 📜 Full **JavaDoc** documentation for all public classes/methods

---

## 📁 Project Structure

<img width="595" height="586" alt="image" src="https://github.com/user-attachments/assets/9c7b757d-3ac1-451b-b8fc-a8c47d0a5010" />



## 🧠 Skills Demonstrated

- ✅ Strong foundation in **Java 8** (Lambda expressions, Streams, Optional)
- ✅ Proficient in **Maven** project structuring and dependency resolution
- ✅ End-to-end application architecture design using **MVC**
- ✅ Experience with **servlet-based web development**
- ✅ Ability to generate and maintain **JavaDocs**
- ✅ Hands-on with **SQL and JDBC**
- ✅ Knowledge of **testing** and **logging** best practices
- ✅ Capable of **modularizing** code and ensuring reusability
- ✅ Exposure to **deployment lifecycle** with **Apache Tomcat**

---
## 🚀 How to Run

### 🔨 Build using Maven

```bash
mvn clean install
```
## 📦 Deploy on Tomcat (WAR Deployment)
# Build the WAR file:


```bash

mvn package
```
# Copy the WAR to Tomcat's webapps directory:

```bash

cp target/medical-appointment-booking.war <TOMCAT_HOME>/webapps/
```
# Start the Tomcat server:

```bash

# Windows
catalina.bat run

# Linux/macOS
./catalina.sh run
```

# Open in browser:

```bash

http://localhost:8080/medical-appointment-booking
```
📖 JavaDoc

Auto-generated JavaDocs are available at:

```bash

target/site/apidocs
```
To generate JavaDocs manually, run:

```bash

mvn javadoc:javadoc
```
🧪 Testing
Unit tests are written using JUnit 5

To run all tests:

```bash

mvn test
```
# 🛠 Sample Endpoints / Pages

```
| URL                     | Description                      |
|-------------------------|----------------------------------|
| /login.jsp              | User Login Page                  |
| /register.jsp           | Patient Registration             |
| /doctor-dashboard.jsp   | Doctor’s Appointment Dashboard   |
| /admin-panel.jsp        | Admin Overview                   |
| /appointment/book       | Appointment Booking Servlet      |
```

# 🤝 Contributing
Feel free to fork the project and submit pull requests.
Make sure your code passes all tests and includes proper JavaDocs.

# 📝 License
This project is licensed under the MIT License.
See the LICENSE file for more details.



