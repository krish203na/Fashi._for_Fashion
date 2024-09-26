
# Fashi: eCommerce Website for Fashion Enthusiasts

<img
        src="/Screenshot.png"
      />

Fashi is a dynamic and scalable eCommerce platform designed to provide a seamless, minimalistic shopping experience tailored for fashion lovers. This full-stack Java application showcases my proficiency in building end-to-end web solutions, integrating robust backend logic with a clean, responsive frontend design.

## Table of Contents
1. [Features](#features)
   - [Customer Features](#customer-features)
2. [Technologies Used](#technologies-used)
   - [Frontend](#frontend)
   - [Backend](#backend)
   - [Database](#database)
   - [Others](#others)
3. [Setup and Installation](#setup-and-installation)
   - [Prerequisites](#prerequisites)
   - [Steps](#steps)
      - [Backend Setup](#backend-setup)
      - [Frontend Setup](#frontend-setup)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [Contact](#contact)

## Features

### Customer Features
- **User Authentication**:  
  Secure user registration, login, and logout functionality, enabling personalized user sessions.
  
- **Home Page**:  
  A visually appealing landing page featuring the latest and most popular fashion items, alongside easy-to-navigate product categories.
  
- **Product Browsing**:  
  Explore products categorized by type (e.g., clothing, accessories). Users can filter by price range, popularity, or other custom filters.

- **Product Details**:  
  Each product page contains high-quality images, a detailed description, price information, available sizes/colors, and stock status.

- **Search System**:  
  A powerful and user-friendly search functionality that allows customers to quickly find products based on keywords, categories, or price.

- **Shopping Cart**:  
  Add items to the cart, remove unwanted products, or update item quantities. Cart status is maintained across sessions.

- **Dedicated Cart Page**:  
  A single page where customers can review and manage all their selected products before proceeding to checkout.

- **Checkout Process**:  
  A minimalistic and straightforward checkout experience where customers can enter shipping details and payment information securely.

- **Minimalistic Design**:  
  A clean, intuitive interface focusing on providing an easy, distraction-free shopping experience. The design is fully responsive, ensuring smooth navigation on any device.

## Technologies Used

### Frontend
- **HTML5, CSS3**:  
  For structuring and styling the web pages, ensuring responsiveness and cross-browser compatibility.
  
- **JavaScript**:  
  Implements dynamic and interactive elements on the client side to enhance user engagement.

- **JSP (JavaServer Pages)**:  
  Used for dynamically generating HTML content with server-side Java logic, enabling smooth integration between the frontend and backend.

### Backend
- **Java**:  
  The core programming language responsible for the business logic, ensuring a stable and scalable application.

- **Servlets**:  
  Used to handle HTTP requests and responses, acting as a middle layer between the frontend (JSP) and backend logic.

- **Hibernate**:  
  Implements ORM (Object Relational Mapping), simplifying the interaction between Java objects and the MySQL database, reducing boilerplate SQL code.

### Database
- **MySQL**:  
  A robust relational database used to store all application data, including user information, product details, and order history.

### Others
- **Git**:  
  Version control to manage code changes efficiently and enable collaboration.

- **Apache Tomcat**:  
  A servlet container that deploys the Java-based web application, serving dynamic content.

- **Maven**:  
  Used for project build automation and dependency management.

## Setup and Installation

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Tomcat (or any other servlet container)
- MySQL
- Git
- Maven (optional, for build automation)

### Steps

#### Backend Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/krish203na/Fashi._for_Fashion.git
   cd Fashi._for_Fashion
   ```

2. **Configure the Database:**
   - Create a new MySQL database (e.g., `fashi_db`).
   - Update the `hibernate.cfg.xml` file with your MySQL database credentials:

     ```xml
     <property name="hibernate.connection.url">jdbc:mysql://localhost:3306/fashi_db</property>
     <property name="hibernate.connection.username">your_username</property>
     <property name="hibernate.connection.password">your_password</property>
     ```

3. **Build the Project:**
   - Use your preferred IDE (Eclipse, IntelliJ) or Maven from the command line to build the project.

   ```bash
   mvn clean install
   ```

4. **Deploy to Servlet Container:**
   - Deploy the generated `.war` file to Apache Tomcat or any other servlet container:

     ```bash
     <path-to-tomcat>/webapps
     ```

#### Frontend Setup

- The frontend is integrated with JSP pages, served directly by the servlet container. No additional setup is required beyond backend deployment.

### Access the Application
1. Start Apache Tomcat or your servlet container.
2. Open your web browser and navigate to:

   ```url
   http://localhost:8080/Fashi
   ```

## Usage

1. **Register/Login**:  
   Create a new user account or log in with an existing one to access personalized features.
   
2. **Browse Products**:  
   Explore a wide range of products listed under various categories, and filter results based on your preferences.
   
3. **Add to Cart**:  
   Add any desired items to the cart and manage them before making a purchase.
   
4. **Checkout**:  
   Proceed to the checkout page, fill in the necessary shipping and payment information, and place your order.

## Contributing

Contributions are always welcome to improve Fashi! To contribute:

1. **Fork** the repository from GitHub:  
   [Fashi._for_Fashion GitHub Repo](https://github.com/krish203na/Fashi._for_Fashion.git)
   
2. Create a **new branch** with your changes:
   
   ```bash
   git checkout -b my-new-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add some feature"
   ```

4. Push to the branch:

   ```bash
   git push origin my-new-feature
   ```

5. Submit a **pull request**, ensuring your changes adhere to the project's coding standards and include proper documentation.

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out:

- **Email**: [krishla203@gmail.com](mailto:krishla203@gmail.com)
- **LinkedIn**: [Krishna](https://www.linkedin.com/in/krishna-panchal-5426aa271)
