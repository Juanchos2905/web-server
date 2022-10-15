# web-server
Este repositorio contiene un servidor web que sirve contenido HTML, JavaScript, CSS y otras cosas más.



##Librerías utilizadas:
Dotenv: En resumidas cuentas, nos permite definir tantos entornos necesitemos.
Express: Permite ejecutar el código en el lado del servidor y generar aplicaciones web de forma altamente optimizada.
Hbs: Mantiene separados el código y la vista. Permite generar HTML a partir de objetos con datos en formato JSON.

## Fotos:
 A continuación, se encuentra los directorios y archivos usados con su respectiva imagen. 
 
 ![capture1](https://user-images.githubusercontent.com/105325621/196010420-8d55822e-1a85-428e-b389-b222006383b2.png)
 
## Pasos para culminar el proyecto.
### paso 1: 
Iniciamos proyecto con:

npm init -y.

y trabajaremos con:

nodemon.


### Paso 2:
Request & response.
Funcionan gracias a la librería express.

![caputereExpress](https://user-images.githubusercontent.com/105325621/196010659-c495a2cc-d539-4a90-99db-483a5b88e532.png)



### Paso 3:
Instalación de express para el paso anterior:

npm i express.



### Paso 4:
Sirviendo contenido estático.

![contenidoStatic](https://user-images.githubusercontent.com/105325621/196010946-e33b31db-46c0-4051-ba02-19281f35ddc0.png)


### Paso 5:
Sirviendo un sitio web completo.

Utilizamos un template para agilizar la creación de una página.



### Paso 6:
Implementando Handlebars.

Así va quedando la página con el template descargado.

![hbs](https://user-images.githubusercontent.com/105325621/196011040-2c0e03b4-58a3-487f-9aeb-beb1f7641929.png)

Su funcionalidad fue la siguiente:

![hbsFun](https://user-images.githubusercontent.com/105325621/196011105-29b51666-96a2-48f0-b68d-365e08658f01.png)



### Paso 7:
Argumentos desde el controlador.


### Paso 8:
Usamos parcials con HBS:

Con esto conseguimos quitar generic.html e index.html 

### Paso 9:
Preparando la app para subirla a un hosting:

Se sube mediante un puerto disponible, en este caso usaremos el Puerto = 3018

### Paso 10:
Desplegando la app en Heroku.

Heroku es una plataforma como servicio (PaaS) de computación en la nube.

Así queda:
![Final](https://user-images.githubusercontent.com/105325621/196011361-1a2322f3-5a34-461d-a500-5f246e3dbec8.png)

