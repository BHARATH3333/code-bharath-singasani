--create sample maven project for spring boot application in Java.
--add dependency spring-boot-starter-web and H2 database.

--create Model Class for the Following JSON
[
{
"id": "1",
"name": "Laptop",
"description": "A high-performance laptop suitable for gaming and work.",
"price": 1200.00
},
{
"id": "2",
"name": "Smartphone",
"description": "A latest-generation smartphone with a large display and powerful camera.",
"price": 800.00
},
{
"id": "3",
"name": "Wireless Headphones",
"description": "Noise-cancelling wireless headphones with long battery life.",
"price": 200.00
},
{
"id": "4",
"name": "Smartwatch",
"description": "A smartwatch with fitness tracking and customizable watch faces.",
"price": 150.00
},
{
"id": "5",
"name": "Tablet",
"description": "A lightweight tablet with a sharp display, ideal for reading and browsing.",
"price": 300.00
}
]

--Perform CRUD operations using REST Controller
--GET, PUT, POST, DELETE using the annotations
• GET /api/items: Retrieve all items.
• GET /api/items/{id}: Retrieve an item by its ID.
• POST /api/items: Create a new item.
• PUT /api/items/{id}: Update an existing item.
• DELETE /api/items/{id}: Delete an item

--Add Exception handling
--Display the data In the table format on UI
--Add Test Cases
1.Write the test cases for the GET, POST, PUT and DELETE operations
2.Include edge cases and null conditions
3.Run the test cases

