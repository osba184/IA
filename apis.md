# 1 POST https://jsonplaceholder.typicode.com/posts
{
  "title": "foo",
  "body": "bar",
  "userId": 1
}

{
    "name": "Óscar",
    "body": "Regitrio API"
    "id": 19
}

# 2 POST https://jsonplaceholder.typicode.com/users
[
    {
        "id": 1,
        "name": "Leanne Graham",
        "username": "Bret",
        "email": "Sincere@april.biz",
        "address": {
            "street": "Kulas Light",
            "suite": "Apt. 556",
            "city": "Gwenborough",
            "zipcode": "92998-3874",
            "geo": {
                "lat": "-37.3159",
                "lng": "81.1496"
            }
        },
        "phone": "1-770-736-8031 x56442",
        "website": "hildegard.org",
        "company": {
            "name": "Romaguera-Crona",
            "catchPhrase": "Multi-layered client-server neural-net",
            "bs": "harness real-time e-markets"
        }
    },]

[
    {
        "id": 10,
        "name": "Oscar BAllester",
        "username": "muflay",
        "email": "muflay@hotmal.com",
        "address": {
            "street": "Kulas Light",
            "suite": "Apt. 556",
            "city": "Gwenborough",
            "zipcode": "92998-3874",
            "geo": {
                "lat": "-37.3159",
                "lng": "81.1496"
            }
        },
        "phone": "1-770-736-8031 x56442",
        "website": "hildegard.org",
        "company": {
            "name": "Romaguera-Crona",
            "catchPhrase": "Multi-layered client-server neural-net",
            "bs": "harness real-time e-markets"
        }
    },]


# 3 POST https://reqres.in/api

{
"name": "morpheus",
"job": "leader"
}

{
"name": "Oscar Ballester",
"job": "Desarrollador Junior"
}

# 4 POST https://jsonplaceholder.typicode.com/comments
{
"name": "John Doe",
"email": "john@example.com",
"body": "Comentario de prueba"
}

{
"name": "Oscar Ballester",
"email": "oscar@mail.com",
"body": "Comentario modificado para la práctica"
}

# 5 POST https://jsonplaceholder.typicode.com/albums
{
"title": "quidem molestiae enim"
}

{
"title": "Álbum Práctica APIs"
}

# 6 POST https://jsonplaceholder.typicode.com/photos
{
"title": "accusamus",
"url": "https://via.placeholder.com/600",
"thumbnailUrl": "https://via.placeholder.com/150"
}

{
"title": "Foto prueba",
"url": "https://example.com/foto1.jpg",
"thumbnailUrl": "https://example.com/thumb1.jpg"
}

# 7 POST https://jsonplaceholder.typicode.com/todos

{
"title": "delectus aut autem",
"completed": false
}

{
"title": "Finalizar práctica CRUD",
"completed": false
}

# 8 POST https://fakestoreapi.com/products 
{
"title": "Test Product",
"price": 13.5
}

{
"title": "Portátil HP",
"price": 899.99
}

# 9 POST https://dummyjson.com/products/add

{
"title": "BMW Pencil"
}

{
"title": "Monitor MSI"
}

# 10 POST https://dummyjson.com/users/add

{

"firstName": "Terry",
"lastName": "Medhurst"
}

{
"firstName": "Oscar",
"lastName": "Ballester"
}

# 1 GET https://jsonplaceholder.typicode.com/posts/1

{
"id": 1
}

{
"id": 5
}

# 2 GET https://jsonplaceholder.typicode.com/posts/2

{
"id": 2
}

{
"id": 7
}

# 3 GET https://jsonplaceholder.typicode.com/comments/1

{
"id": 1
}

{
"id": 3
}

# 4 GET https://jsonplaceholder.typicode.com/albums/1

{
"id": 1
}

{
"id": 1
}

# 5 GET https://jsonplaceholder.typicode.com/photos/1

{
"id": 1
}

{
"id": 15
}

# 6 GET https://jsonplaceholder.typicode.com/todos/1

{
"id": 1
}

{
"id": 16
}

# 7 GET https://jsonplaceholder.typicode.com/users/1

{
"id": 1
}

{
"id": 2
}

# 8 GET https://reqres.in/api/users/2

{
"id": 2
}

{
"id": 20
}

# 9 GET https://fakestoreapi.com/products/1

{
"id": 1
}

{
"id": 20
}

# 10 GET https://dummyjson.com/users/1

{
"id": 1
}

{
"id": 9
}

# 1 PUT https://jsonplaceholder.typicode.com/todos
[
    {
        "userId": 1,
        "id": 1,
        "title": "delectus aut autem",
        "completed": false
    },
]

[
    {
        "userId": 10,
        "id": 1,
        "title": "Dayly",
        "completed": true
    },
]

# 2 PUT https://jsonplaceholder.typicode.com/posts/1

{
"title": "foo",
"body": "bar"
}

{
    "id": 1,
    "title": "Actualizado",
    "body": "Contenido nuevo",
    "userId": 1
}


# 3 PUT https://jsonplaceholder.typicode.com/posts/2

{
"title": "post",
"body": "text"
}

{
"title": "Segundo post actualizado",
"body": "Nuevo contenido"
}

# 4 PUT https://jsonplaceholder.typicode.com/users/1 

{
"name": "Leanne Graham"
}

{
"name": "Oscar Actualizado"
}

# 5 PUT https://jsonplaceholder.typicode.com/todos/1

{
"completed": false
}

{
"completed": TRUE
}

# 6 PUT https://reqres.in/api/users/2

{
"name": "morpheus",
"job": "leader"
}

{
"name": "Oscar",
"job": "Camarero"
}

# 7 PUT https://fakestoreapi.com/products/1

{
"title": "Product"
}

{
"title": "PORTATIL HP"
}

# 8 PUT https://fakestoreapi.com/users/1

{
"email": "user@test.com"
}

{
"email": "inetum@prueba.com"
}

# 9 PATCH https://jsonplaceholder.typicode.com/comments/1

{
"body": "Comentario"
}

{
"body": "ACTUALIZADO EL Comentario"
}

# 10 PATCH https://dummyjson.com/products/1

{
"title": "Product"
}

{
"title": "MONITOR ZOWIE"
}

# 1 DELETE https://dummyjson.com/users/1


# 2 DELETE https://fakestoreapi.com/products/1


# 4 DELETE https://reqres.in/api/users/2


# 5 DELETE https://jsonplaceholder.typicode.com/users/1


# 6 DELETE https://jsonplaceholder.typicode.com/todos/1


# 7 DELETE https://jsonplaceholder.typicode.com/photos/1


# 8 DELETE https://jsonplaceholder.typicode.com/albums/1


# 9 DELETE https://jsonplaceholder.typicode.com/comments/1


# 10 DELETE https://jsonplaceholder.typicode.com/posts/2