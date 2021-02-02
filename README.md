POST: http://localhost:51502/api/Clientes
BODY->RAW//JSON:
{
    "id": 1,
    "nombre": "Victor",
    "apellido": "Alfonso",
    "direccion": "Reus",
    "dni": 12345
}

GET: http://localhost:51502/api/Clientes

PUT: http://localhost:51502/api/Clientes/1
BODY->RAW//JSON:
{
    "nombre": "Víctor Alonso",
    "apellido": "Alfonso Martí"
}

GET_ID: http://localhost:51502/api/Clientes/1

DELETE: http://localhost:51502/api/Clientes/1
