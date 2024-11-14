## Objetivo:
Desarrollo de microservicio Rest básico para obtener la información de una lista de productos o un producto concreto a traves de su identificador único

## Sobre mi participacion y Logros:
He desarrollado en su totalidad este microservicio con Spring Boot y MySQL. Esto me ha ayudado a conseguir:

1. Conocimientos sólidos en microservicios.
2. Aprender a configurar y realizar peticiones Restful.
3. Integrar todo esto con una BBDD SQL real.
4. Ofrecer ejemplo de desrrollo a otros programadores.

## Funcionamiento del microservicio
Se ha implementado dos peticiones GET en el micro. En la primera de ellas se solicita la lista completa de la base de datos. Sin embargo, en la segunda se le pasa un parámetro con @PathVariable el cuál contiene el "id" del producto. ESte "id" se usa para realizar la busqueda en la base de datos y traernos la informacion. Estos resultados están testeados con Postman, lo único que hacemos es indicar el tipo de petición, en nuestro caso GET y la Url programada en el controlador. Al enviar la petición Postman muestra el resultado devuelto por el microservicio.
