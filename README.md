# Expense Tracker(Spring Boot+MySQL)

This is a full-stack Expense Tracker web application built using Spring Boot and MySQL.  
I developed this project to practice backend development, user authentication, and database integration.
The application allows users to register, log in securely, and manage their personal expenses.  
Each user can view only their own expenses, ensuring proper data separation.
# Features

- User Registration and Login
- Password encryption using BCrypt
- Add and delete expenses
- Expense categorization(Food,Travel,Bills,etc)
- User-specific expense tracking
- Real-time total calculation
- Pie chart visualization using Chart.js
- Logout functionality
# Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Spring Security(BCrypt)
- MySQL
- HTML,CSS,JavaScript
- Chart.js
  # Project Structure

- `model-> Entity classes(User,Expense)
- `repository→ JPA repositories
- `controller-> REST APIs
- `static-> Frontend files(login,dashboard)
- `application.properties-> Database configuration
- 
#  How to Run the Project
1. Install MySQL and create a database
2. Update `application.properties` with your MySQL username and password
3. Run the project
4. Open in browser
5. http://localhost:8081/login.html




