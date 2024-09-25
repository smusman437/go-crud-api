GO CURD API:

Run the application:

Run the application from the terminal:

```go run main.go```
You should see the output:

Server is running on http://localhost:8080
You can now perform CRUD operations using tools like curl or Postman:

Create an item:

```curl -X POST http://localhost:8080/items -H "Content-Type: application/json" -d '{"name": "Laptop", "price": 1200}'```
Get all items:

```curl http://localhost:8080/items```
Get an item by ID:

```curl http://localhost:8080/items/1```
Update an item:

```curl -X PUT http://localhost:8080/items/1 -H "Content-Type: application/json" -d '{"name": "Updated Laptop", "price": 1000}'```
Delete an item:

```curl -X DELETE http://localhost:8080/items/1```

