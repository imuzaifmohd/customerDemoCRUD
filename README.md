# customerDemoWebApiPart2_withEntityFramework

# Customer Demo CRUD App

![image](https://github.com/user-attachments/assets/030c68ea-37dc-459a-9d20-1f4d14cb6174)

This project is made using .NET Core. It is built to perform CRUD operations while being connected to a database using Entity Framework, and follows the Repository Pattern for better code structure and maintainability.

## 🛠️ Technologies Used

- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- Repository Pattern
- Swagger (for API testing)
- GitHub for version control

## 📂 Project Structure
customerDemoCRUD/
│

├── Controllers/ # API Controllers

├── Models/ # Data models

├── Repositories/ # Repository interfaces and implementations

├── Data/ # DbContext and EF Core setup

├── Program.cs # Application startup

└── README.md # Project documentation


## 🔁 CRUD Operations

The API supports the following operations on customers:

- **Create** a new customer  
- **Read** customer(s) by ID or list  
- **Update** existing customer details  
- **Delete** a customer

## 🔧 How to Run

1. **Clone the repo**  
   ```bash
   git clone https://github.com/imuzaifmohd/customerDemoCRUD.git

2. Open in Visual Studio or VS Code

3. Update connection string in appsettings.json

"ConnectionStrings": {
  "DefaultConnection": "Your-Database-Connection-String"
}

4. Run migrations (if applicable)
sample:
Add-Migration "Initial Migration"
update-database


6. Run the application

7. Access Swagger UI at:

https://localhost:<port>/swagger

🧱 Repository Pattern
This project uses the Repository Pattern to abstract data access logic and keep controllers clean.

🙋‍♂️ Author
Mohd Uzaif


Feel free to fork or contribute!

---

Let me know if you want to include screenshots, sample API responses, or database schema.


