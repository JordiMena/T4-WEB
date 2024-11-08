# T4-WEB
Tarea 4 - Asignacion 1 - 🎯 Registro de Series, Películas o Libros y Personajes

Objetivo: El objetivo de esta práctica es aplicar conceptos clave de comunicación entre componentes, enrutamiento, manejo de formularios y validación en Blazor, así como integrar Entity Framework Core para la persistencia de datos. Los estudiantes desarrollarán una aplicación que permita registrar series, películas o libros, y sus personajes asociados.

📋 Instrucciones:
1️⃣ Registro de Series, Películas o Libros usando SQLITE:
Crea una página para registrar series, películas o libros con los siguientes campos:
Nombre (texto).
País (texto).
Idioma (texto).
Foto URL (enlace a una imagen).
Resumen (área de texto para describir la serie/película/libro).
2️⃣ Registro de Personajes:
Crea una página para registrar personajes asociados a una serie, película o libro, con los siguientes campos:
Nombre (texto).
Apodo (texto).
Raza (texto).
Foto URL (enlace a una imagen).
Edad (número).
Poder Característico (texto).
El estudiante deberá seleccionar la serie, película o libro al que pertenece el personaje.
3️⃣ Enrutamiento y Navegación:
Implementa el enrutamiento en Blazor para permitir la navegación entre las páginas de registro de series/películas/libros y de personajes.
Asegúrate de que las URLs sean dinámicas, de modo que la página de un personaje contenga el ID de la serie/película/libro a la que está asociado.
4️⃣Persistencia de Datos con Entity Framework Core:
Implementa Entity Framework Core para la persistencia de datos.
Crea modelos para Series/Películas/Libros y Personajes, con las correspondientes relaciones entre ellos.
Implementa las migraciones necesarias y asegúrate de que los datos se guarden en una base de datos.
Desarrolla las operaciones CRUD (Crear, Leer, Actualizar, Borrar) para gestionar tanto las series/películas/libros como los personajes.
