# BookStore-Ecommerce
BookStore Ecommerce with Admin Panel and Database

### Complete E-Commerce - Java, Spring, Hibernate & MySQL

This is a project about building a E-Commerce website using modern Java Full Stack technologies. Specifically, it's about building an online bookstore. 

It's about bookstore, but the modules developed in the course is similar for all E-Commerce website. Those modules contains:


- User Signup and Login

- User profile management

- Product Management

- Shopping Cart 

- Order checkout and order history

- Automatic email confirmation


Those modules are the basics for pretty much any E-Commerce website.

From the architecture perspective, the system is divided into two parts - Bookstore and AdminPortal. Bookstore is the front-end website that customer will be using for submitting orders while AdminPortal is used for administration purpose. Presumably they will be running on two servers. The good side is the two apps are decoupled in some way so that they can be managed separately. The drawback would be that we need to maintain two copies of the code.

As this is a full stack development project, we will develop the code for both front-end and backend. A considerable amount of work will be on developing the front-end code using HTML, CSS, Javascript, Thymeleaf, bootstrap and etc. Thymeleaf is the latest Java template engine, which is supposed to replace previous JSP way (JSP is discontinued but is still being used out there) and it is the official template engine backed by Spring Framework, though it's not the only one you can choose. The backend side will be using latest Spring technologies - Spring Boot, Spring Security, Spring Data, Hibernate and etc. Then, we will have MySQL as database. MySQL is powerful and free to use and serves as a good database candidate in plenty of commercial apps out there.

