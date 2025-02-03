# E-Commerce Platform

## Version 2.4.8

This project is a fully functional **E-Commerce Platform** built using **Spring Boot**. It provides an interface for both **admins** and **users**. Admins can manage products, while users can view available products and make purchases. The application is secured with **JWT Authentication** and **Role-based Access**.

---

### **Features**

- **JWT Authentication**: Secure login with token-based authentication.
- **Role-Based Access**: Different access levels for Admins and Users.
- **Product Management**: Admins can create, update, delete, and view products.
- **Persistent Data Storage**: Integrated with **MySQL** for persistent storage of product data and user information.
- **Rebased and Merged Changes**: Ensures consistency between local and remote repositories by resolving merge conflicts (as of version 2.4.8).

---

### **Tech Stack**

- **Backend**: Spring Boot
- **Database**: MySQL (Amazon RDS)
- **Security**: JWT (JSON Web Tokens)
- **Deployment**: AWS EC2
- **Version Control**: GitHub

---

### **Project Setup**

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/ishwetraj17/ecommerce-platform.git
    ```

2. **Install Dependencies**:

    Navigate to the project directory and run:

    ```bash
    mvn clean install
    ```

3. **Database Configuration**:

    Configure your MySQL database connection in the `src/main/resources/application.properties` file.

   

4. **Running the Application**:

    To run the application locally, use:

    ```bash
    mvn spring-boot:run
    ```

---

### **API Documentation**

This project includes RESTful APIs to interact with products, manage user authentication, and perform other functionalities.

1. **User Authentication**:
   - **POST /auth/login**: Login and receive a JWT token.
   - **POST /auth/register**: User registration.

2. **Product Management**:
   - **GET /products**: View all products.
   - **POST /products**: Add a new product (Admin only).
   - **PUT /products/{id}**: Update an existing product (Admin only).
   - **DELETE /products/{id}**: Delete a product (Admin only).

---

### **Contributing**

If you want to contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your branch to GitHub.
5. Open a pull request.

---

### **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Contact**

For any issues, feel free to reach out to the repository owner.

