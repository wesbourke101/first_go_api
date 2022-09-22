# TESTING

```
Just learning how to use GO and the gin frame work to make a very basic api.
```

Calls can be tested on Thunder client, postman, localhost:8080 in a terminal or browser window.

##how to run a go file

```go
go run helloworld.go
```

```go
how to use gin
use go command to install
go get -u github.com/gin-gonic/gin
import "github.com/gin-gonic/gin"
Creates a gin router with default middleware:
router := gin.Default()
other calls
router.GET("/someGet", getting)
router.POST("/somePost", posting)
router.PUT("/somePut", putting)
router.DELETE("/someDelete", deleting)
router.PATCH("/somePatch", patching)
router.HEAD("/someHead", head)
router.OPTIONS("/someOptions", options)
```

```go
post new book:: curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"
patch request to checkout a book:: curl --location --request PATCH 'localhost:8080/checkout?id=2'
patch request to return a book:: curl --location --request PATCH 'localhost:8080/return?id=2'
get request:: curl localhost:8080/books
get by id::curl localhost:8080/books/1
step one is to make api calls
```

##step two is to add some kind of SQL DB

##step three is to add a javascript, react front end.

# first_go_api

```
Wes Bourke::wesbourkeavl@gmail.com
```
