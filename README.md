# Todo App con React Testing Library

Bienvenido a la aplicación en React Todo App, una aplicación desarrollada en React siguiendo el tutorial de The Net Ninja en su video "React Testing Library" (v=7dTTFW7yACQ&list=PL4cUxeGkcC9gm4_-5UsNmLqMosM-dzuvQ). Esta aplicación te permite escribir tareas por hacer y luego renderizarlas en una lista. Ha sido exhaustivamente probada utilizando la librería de React Testing Library para garantizar su correcto funcionamiento.

## Características principales

- Escribir tareas por hacer en un input
- Renderizar tareas en una lista
- Cambios de estilos cuando se selecciona una tarea
- Contador con el número de tareas por completar
- Navegación en el menú
- Simulación de peticiones a una API mediante mocks
- Test realizados

## En esta aplicación se han realizado una amplia variedad de tests para comprobar el correcto renderizado y funcionamiento de los siguientes componentes:

- Header (renderizado y lógica de Mostrar texto que se le pasa por props)
- Input de búsqueda
- Botones
- Listas (pruebas para ver el correcto funcionamiento de la cantidad de followers en followerlist)
- Lógica de la aplicación (ejemplo: guardado de información escrita en un input, borrado de contenido de un input después de dar al botón, cambio de información dependiendo la página en la que estemos)
- Estilos y cambios de estilos
- Contador de tareas por completar
- Peticiones a una API mediante mocks
- En los tests, hemos usado describe blocks para organizar los tests y hacerlos más legibles, fireEvent para simular interacciones de usuarios, Integration Tests para comprobar la correcta comunicación entre los componentes y FindBy y FindAllBy para hacer tests asíncronos.

Cómo correr la aplicación

Para correr la aplicación, primero debes clonar este repositorio en tu computadora. Luego, debes abrir una terminal y navegar hasta el directorio de la aplicación. Finalmente, debes ejecutar el siguiente comando:

Copy code

```npm install```
Después de instalar las dependencias, puedes correr la aplicación ejecutando el siguiente comando:

sql
Copy code
```npm start```

## Conclusión

En conclusión, esta aplicación Todo App ha sido cuidadosamente diseñada para ser fácil de usar y ha sido exhaustivamente probada para garantizar su correcto funcionamiento y renderizado. Esperamos que te resulte útil y fácil
