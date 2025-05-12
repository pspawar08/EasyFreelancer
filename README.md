# EasyFreelancer

**Freelancer and Company Connection Platform**  
*A traditional Spring MVC-based web application for connecting freelancers with companies.*

## 🛠 Tech Stack

- **Framework**: Spring MVC (non-Spring Boot)  
- **View Layer**: JSP (JavaServer Pages)  
- **Database**: PostgreSQL  
- **Build Tool**: Maven  
- **Deployment**: Apache Tomcat  

## 📌 Overview

**EasyFreelancer** is a monolithic web platform designed to streamline the hiring process by connecting freelancers with companies. It offers functionalities such as profile creation, job posting, job search, and freelancer hiring through a user-friendly JSP interface.

### 🔧 Key Contributions

- Developed a monolithic web platform connecting freelancers with companies, allowing freelancers to create profiles, search for jobs, and apply for projects, with an easy-to-use interface built using JSP.
- Implemented company registration, job posting, and freelancer hiring functionalities, streamlining the hiring process and reducing hiring time.
- Utilized Spring MVC for backend development and integrated PostgreSQL for managing job listings and user profiles.

## ✨ Features

- Freelancer and company registration
- Job posting and management
- Freelancer job search and application
- JSP-based views served through Spring MVC controllers
- PostgreSQL integration for persistent data management
- XML-based Spring configuration via `web.xml` and `dispatcher-servlet.xml`

## ⚙️ Getting Started

### Prerequisites

- Java 8 or later  
- Apache Tomcat (8.x or 9.x recommended)  
- PostgreSQL  
- Maven

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/easyfreelancer.git
   cd easyfreelancer
   
2. **Configure PostgreSQL**
   - Create a database named EasyFreelancer
   - Update the JDBC URL, username and password in your Spring configuration
    
3. **Build the project**
   ```bash
   mvn clean package
4. **Deploy to Tomcat
   - Copy teh genrated WAR file into the webapps folder of your Tomcat server
  
5. **Access the application**
   - Open a browser and navigate to:
     (http://localhost:8080/easyfreelancer/)
