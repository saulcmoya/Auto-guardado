Formulario Web con Auto-Guardado

Este proyecto implementa un formulario web capaz de guardar automáticamente la información introducida por el usuario, permitiendo restaurar los datos incluso después de cerrar o recargar la página.

El objetivo es demostrar el concepto de persistencia de estado en aplicaciones web, similar al comportamiento de guardado automático presente en muchas aplicaciones modernas.

Características

Guardado automático en tiempo real

Restauración de datos al recargar

Interfaz centrada y estilizada con CSS

Uso de almacenamiento local del navegador

Botón para limpiar datos guardados

Captura de pantalla
![alt text](image.png)

![alt text](image-1.png)


Tecnologías utilizadas

HTML5

CSS3

JavaScript

LocalStorage del navegador

Cómo ejecutar el proyecto

Clonar el repositorio

git clone URL_DEL_REPO

Abrir el archivo

formulario.html

Ejecutar en el navegador

No se requiere instalación adicional.

Concepto implementado

El sistema utiliza localStorage para almacenar automáticamente los valores introducidos en los campos del formulario mediante eventos input.

Al cargar la página, el script recupera los valores guardados y los restaura en los campos correspondientes.

Esto simula un mecanismo básico de:

Persistencia de estado

Recuperación de sesión

Auto-guardado en aplicaciones web