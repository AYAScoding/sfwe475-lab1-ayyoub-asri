

Strand 1:

Method : GET
Status code : 304
Content-Type response header : application/json; charset=utf-8
What is in the body? :
 {
  "userId": 1,
  "id": 1,
  "title": "delectus aut autem",
  "completed": false
}
2-

status code is 404 not found
Error on the user side 

3- 

https://jsonplaceholder.typicode.com/todos/99999
scheme: https
host: jsonplaceholder.typicode.com
path: todos/99999 

Strach:
https://jsonplaceholder.typicode.com/todos?userId=1

query string: ?userId=1
filtering: is selecting all todos where userId = 1

POST has extra content that is submited inside the request body instead of all in the url like GET that only reads or gets existing data

Challenge:
safe to cash: since "cache-control : max-age=43200" it doesn't have soething like "no-store" or "no-cache" ( i didn't know that before search)


