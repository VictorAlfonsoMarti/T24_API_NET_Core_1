![alt text](https://github.com/VictorAlfonsoMarti/T24_API_NET_Core_1/blob/master/README_IMAGES/SWAGGER.JPG)

POST: http://localhost:51502/api/Clientes
BODY->RAW//JSON:
{
    "id": 1,
    "nombre": "Victor",
    "apellido": "Alfonso",
    "direccion": "Reus",
    "dni": 12345
}
![alt text](https://github.com/VictorAlfonsoMarti/T24_API_NET_Core_1/blob/master/README_IMAGES/POST.JPG)

GET: http://localhost:51502/api/Clientes
![alt text](https://github.com/VictorAlfonsoMarti/T24_API_NET_Core_1/blob/master/README_IMAGES/GET.JPG)

PUT: http://localhost:51502/api/Clientes/1
BODY->RAW//JSON:
{
    "nombre": "Víctor Alonso",
    "apellido": "Alfonso Martí"
}
![alt text](https://github.com/VictorAlfonsoMarti/T24_API_NET_Core_1/blob/master/README_IMAGES/PUT.JPG)

GET_ID: http://localhost:51502/api/Clientes/1
![alt text](https://github.com/VictorAlfonsoMarti/T24_API_NET_Core_1/blob/master/README_IMAGES/GET_ID.JPG)

DELETE: http://localhost:51502/api/Clientes/1
![alt text](https://github.com/VictorAlfonsoMarti/T24_API_NET_Core_1/blob/master/README_IMAGES/DELETE.JPG)
