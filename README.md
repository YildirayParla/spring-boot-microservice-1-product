# MicroService Product

### EndPoints:

### Save Product:
....

POST localhost:3333/api/product\
Authorization: Basic \
Content-Type: application/json

{\
"name":"test-1",
"price":1.2\
}

....

### Get Products
....

GET localhost:3333/api/product \
Authorization: Basic  

....

### Delete Products

....

DELETE localhost:3333/api/product/1 \
Authorization: Basic  \
....
