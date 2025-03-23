
## Task-Manager-WebApp


## Overview

Simple task manager web application where users can add, update or delete tasks.



## Technologies Used
- Spring Boot 3.4.4
- Spring Data JPA
- H2 Database
- Thymeleaf


## Setup Instructions
1. **Clone the repository**:

   ```bash
   https://github.com/don99ishara/Spring-Boot-Task-Manager-WebApp.git
   cd Spring-Boot-Task-Manager-WebApp
   ```

2. **setup local h2 database config**

```
go to application.properties file

spring.datasource.url=jdbc:h2:file:your_path
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=your_username
spring.datasource.password=your_password

```


3. **To view**:

```bash
   http://localhost:8080/
   ```


4. **To check h2 Database**
```bash
   http://localhost:8080/h2-console
   ```
