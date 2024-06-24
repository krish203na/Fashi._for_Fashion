# Fashi. for Fashion

Fashi is a dynamic eCommerce website developed using a full stack of Java technologies, providing a seamless and minimalistic shopping experience for fashion enthusiasts. This project showcases my expertise in building robust, scalable web applications with a clean and modern design.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

### Customer Features
- **User Authentication**: Sign up, login, and logout functionalities.
- **Home Page**: A welcoming page with featured products and categories.
- **Product Browsing**: View products by categories with filtering options.
- **Product Details**: Detailed view of each product including images, description, price.
- **Search System**: Dedicated search page to find products easily.
- **Shopping Cart**: Add, remove, and update product quantities in the cart.
- **Dedicated Cart Page**: Manage all items added to the cart in one place.
- **Checkout Process**: Simple and straightforward process to place orders.
- **Minimalistic Design**: Clean and user-friendly interface for an enhanced shopping experience.

## Technologies Used

### Frontend
- **HTML5, CSS3**: For structuring and styling the web pages.
- **JavaScript**: For interactive client-side functionalities.
- **JSP (JavaServer Pages)**: For dynamically generating HTML content on the server.

### Backend
- **Java**: Core programming language for backend logic.
- **Servlets**: To handle requests and responses between the front end and the server.
- **Hibernate**: For ORM (Object Relational Mapping) to interact with the database.

### Database
- **MySQL**: Relational database for storing all application data.

### Others
- **Git**: Version control system for tracking changes and collaboration.

## Setup and Installation

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Tomcat (or any other servlet container)
- MySQL
- Git

### Steps
1. **Clone the repository**
    ```bash
    git clone https://github.com/krish203na/Fashi._for_Fashion.git
    cd Fashi._for_Fashion
    ```

2. **Backend Setup**
    - **Configure the Database**:
        - Create a MySQL database.
        - Update the `hibernate.cfg.xml` file with your MySQL database credentials.
    - **Build the Project**:
        - Compile the project using your IDE (e.g., Eclipse, IntelliJ) or using the command line.
        ```bash
        mvn clean install
        ```
    - **Deploy to Servlet Container**:
        - Deploy the generated WAR file to your servlet container (e.g., Apache Tomcat).

3. **Frontend Setup**
    - The frontend is integrated with JSP and served by the servlet container.

4. **Access the Application**
    - Open your browser and go to `http://localhost:8080/Fashi` to access the application.

## Usage

1. **Register/Login**: Create a new account or login with existing credentials.
2. **Browse Products**: Explore various products listed in different categories.
3. **Add to Cart**: Add desired products to the shopping cart.
4. **Checkout**: Proceed to checkout, fill in the required details, and place the order.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the project's coding standards and includes proper documentation.

## Contact

If you have any questions or suggestions, feel free to reach out to me:

- Email: krishla203@gmail.com
- GitHub: [krish203na](https://github.com/krish203na)
