Actividad formativa ramo fullstacks 3 
Se solicita crear un CRUD de un microservicio en spring boot con coneccion a base de datos de oracle y pruebas con postman
********************************************************************************************
Configuracion:
La wallet debe estar descomprimida y ubicada en C:/ para la conexión a la base de datos.
********************************************************************************************
Diccionario Endpoints Disponibles postman
Registrar Libro
Metodo: Post
URL: http://localhost:8080/libros
Json a enviar: 
{
    "titulo": "Dragon Ball Z",
    "año": 1967,
    "autor": "Toriyama",
    "genero": "Seinen"
}
//Crear un nuevo libro en la base de datos 
********************************************************************************************

Eliminar Libro
Metodo Delete
URL: http://localhost:8080/libros/1
// Eliminamos libro , el ID debe ser el numero de la base de datos identificador que queremos eliminar 
********************************************************************************************

Mirar todos los libros en base de datos
Metodo: Get
URL http://localhost:8080/libros
// entrega la lista de todos los libros registrado
********************************************************************************************
Obtener un libro por ID
URL http://localhost:8080/libros/1
obtenemos la informacion espeficica del libro que tenemos asocionado al identificador unico {id}

********************************************************************************************
Actualizar un libro
Metodo: Put
http://localhost:8080/libros/1
Json 
{
    "titulo": "Dragon Ball GT",
    "año": 1996,
    "autor": "Akira Toriyama",
    "genero": "Seinen"
}
//actualizamos la informacion del libro dependiendo de su indentificador unico {id}
********************************************************************************************
Obtener Libros por autor (queda pendiente me falto tiempo pero esta todo listo metodo,jpa, etc solo falta el endpoint 
Metodo:Get
URL : a determinar
Trae la informacion del libro segun el autor 


 







 


 
