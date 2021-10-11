## A RESTapi in Go with Gin framework

//get all albums
``
curl http://localhost:8080/albums
``
//get specific album
``
curl http://localhost:8080/albums/4
``

//post:
``
curl http://localhost:8080/albums --include --header "Content-Type: application/json" --request "POST" --data '{"id": "4","title": "The Modern Sound of Blaha Lind","artist": "Blaha Lind","price": 66.99}'
``