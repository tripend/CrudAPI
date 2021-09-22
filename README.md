CrudAPI

A Crud API made using Spring Boot

Tested in Postman:

    Create: Make a POST request using a JSON body to http://127.0.0.1:8080/api/v1/todo
            with the following format:
            {
                "title": "<some title>",
                "description": "<description for title>",
                "todoStatus": "<COMPLETED/NOT_COMPLETED>"
            }

    Read: Make a GET request to http://127.0.0.1:8080/api/v1/todo for all todos
        and a GET request to  http://127.0.0.1:8080/api/v1/todo/<id> for specific todo

    Update: Make a PUT request to  http://127.0.0.1:8080/api/v1/todo/<id> with a JSON
            body to update the old parameters:
            {
                "title": "<new title>",
                "description": "<new description>",
                "todoStatus": "<new status>"
            }

    Delete: Make a DELETE request to http://127.0.0.1:8080/api/v1/todo/<id> to delete the 
            specific id.

        
By default, the API comes loaded with two todos.
