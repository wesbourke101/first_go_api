TESTING

> post new book:: curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"
> patch request to checkout a book:: curl --location --request PATCH 'localhost:8080/checkout?id=2'
> patch request to return a book:: curl --location --request PATCH 'localhost:8080/return?id=2'
> get request:: curl localhost:8080/books
> get by id::curl localhost:8080/books/1

# first_go_api
