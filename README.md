Product Backend Project
This project aims to use basic CRUD operations to create, show, update, and delete products. The projects aims to show basics of REST API, handling exception Project uses Java as main tech and Spring Boot Framework. As Database H2 Database is used for database purposes.
Swagger UI is used for visualizing and testing our API endpoints.

Tech Stack
Java 17+
Spring Boot
Spring Web
Spring Data JPA
H2 Database
Swagger / Springdoc OpenAPI

Features - API Endpoints
Create -    POST "/" - to Create Product with createProduct method. It takes the request body and return a new Response if there is no problem.
Get -       GET "/{id}" - to get specific product by id. if there is no product with specific id, it will return us a ProductNotFound Exception.
Update -    PUT "{id}" - We are getting specific product and update it. We are getting new product details from RequestBody as JSON.
Get -       GET "/" - We are listing all the products that we have.
Delete -    DELETE "/{id}" - We are getting specific product and delete it from our Database.


How to Run the Project
i) Clone the repository
git clone <repository-url>

Then :
1)Navigate into the project
cd product-backend
or
2)Run it from IDE



Run Spring Boot

mvn spring-boot:run
