Product Backend Project 🛒

This project aims to use basic CRUD operations to create, show, update, and delete products.

The projects aims to show basics of REST API, handling exception Project uses Java as main tech and Spring Boot Framework. As Database H2 Database is used for database purposes. Swagger UI is used for visualizing and testing our API endpoints.
------------------------------------------------------------------------------------------------------------

Tech Stack 💻

I. Java 17+ 

II. Spring Boot 

III. Spring Web 

IV. Spring Data JPA

V. H2 Database 

VI. Swagger / Springdoc OpenAPI

------------------------------------------------------------------------------------------------------------

🔗 Features - API Endpoints 

Create - POST "/" - to Create Product with createProduct method. It takes the request body and return a new Response if there is no problem. 

<img width="1421" height="306" alt="Screenshot 2025-12-08 at 01 14 52" src="https://github.com/user-attachments/assets/9a6ff7bd-67be-4a3a-b1cb-51ac583a42af" />

Get - GET "/{id}" - to get specific product by id. if there is no product with specific id, it will return us a ProductNotFound Exception. 

<img width="1422" height="931" alt="Screenshot 2025-12-08 at 01 15 49" src="https://github.com/user-attachments/assets/ee2795ae-d959-40ec-80aa-6be5f988bd22" />


Update - PUT "{id}" - We are getting specific product and update it. We are getting new product details from RequestBody as JSON. 

<img width="1276" height="1007" alt="Screenshot 2025-12-08 at 01 16 29" src="https://github.com/user-attachments/assets/dda86180-3727-48a8-bb82-098b40077e1d" />

<img width="1275" height="520" alt="Screenshot 2025-12-08 at 01 16 54" src="https://github.com/user-attachments/assets/46ab81ce-949f-40d6-b2ed-11fce8bb938c" />



Get - GET "/" - We are listing all the products that we have. Delete - DELETE "/{id}" - We are getting specific product and delete it from our Database.

<img width="1275" height="520" alt="Screenshot 2025-12-08 at 01 16 54" src="https://github.com/user-attachments/assets/9e74611d-a249-4815-bf64-705b53f033df" />

Delete - DELETE "/{id}" - to delete the specified product by id. If there is no product with specific id, it will return us a ProductNotFound Exception.  

<img width="1273" height="562" alt="Screenshot 2025-12-08 at 01 17 12" src="https://github.com/user-attachments/assets/e9b42bbc-89f7-46d7-9f7d-4c7fdde645c5" />

<img width="1272" height="445" alt="Screenshot 2025-12-08 at 01 17 26" src="https://github.com/user-attachments/assets/d9d315ea-a8f6-48ed-b2c2-36b336509de0" />




------------------------------------------------------------------------------------------------------------

❌ Exception Handling


When specific ID product is not found, the program throws ProductNotFoundException.

<img width="1412" height="922" alt="Screenshot 2025-12-08 at 01 15 38" src="https://github.com/user-attachments/assets/16f24476-7858-4782-a828-659639298a03" />


------------------------------------------------------------------------------------------------------------

📄 Example JSON Request Bodies

Create - POST

{

"name" : "Example Product Name"

}

<img width="1421" height="306" alt="Screenshot 2025-12-08 at 01 14 52" src="https://github.com/user-attachments/assets/9a6ff7bd-67be-4a3a-b1cb-51ac583a42af" />

------------------------

Update - PUT

{

"name" : "New Product Name",

"id" : productID

}

<img width="1276" height="1007" alt="Screenshot 2025-12-08 at 01 16 29" src="https://github.com/user-attachments/assets/dda86180-3727-48a8-bb82-098b40077e1d" />

<img width="1275" height="520" alt="Screenshot 2025-12-08 at 01 16 54" src="https://github.com/user-attachments/assets/46ab81ce-949f-40d6-b2ed-11fce8bb938c" />


------------------------------------------------------------------------------------------------------------

How to Clone the Project i) Clone the repository git clone https://github.com/Aliyev7M/VistulaProject2
