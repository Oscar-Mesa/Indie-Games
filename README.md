## Ejecución del proyecto
1. Clonar el repositorio en tu máquina.  
2. Instalar las dependencias desde el archivo `requirements.txt` con el comando:

   ```
   pip install -r requirements.txt
    ```
   Una vez instaladas las dependencias, ejecutar el proyecto con:
   ```
    python manage.py runserver
   ```

    Acceder al link que brinda la terminal.

## Funcionalidades del sitio

### Página de inicio: 
muestra tarjetas de los tres videojuegos más populares.

<img width="944" height="482" alt="inicio" src="https://github.com/user-attachments/assets/e4e5c5a6-2ecc-4ba2-ba6e-df6f0bbfcf00" />  

---

### Novedades: 
sección con todos los juegos agregados en formato de tarjetas.

<img width="948" height="477" alt="inicio inferior" src="https://github.com/user-attachments/assets/ae3add7d-c5d0-4b86-af2e-af72fa266d90" />

---

### Filtros por motor de videojuegos: 
Unity y RPGMaker, para realizar búsquedas más específicas.

<img width="936" height="477" alt="sección unity" src="https://github.com/user-attachments/assets/e51fa70f-f40a-4ae7-aa6c-716299e54d59" />

<img width="943" height="473" alt="sección rpg maker" src="https://github.com/user-attachments/assets/2bd77829-fad9-492c-95e0-8e687e0984d6" />

---

### Cada tarjeta incluye:
Sección de detalle.

Link externo para descargar el juego.


<img width="948" height="481" alt="detalle juegos" src="https://github.com/user-attachments/assets/9b335d22-941c-4751-8432-4ffe61554ff5" />

---


### Pie de página: 
incluye información relevante.

<img width="948" height="209" alt="footer" src="https://github.com/user-attachments/assets/dfbff063-9048-4894-b169-14b4c5e87aea" />

---

### Política de acceso y descarga.


<img width="945" height="476" alt="politicas" src="https://github.com/user-attachments/assets/53804563-6a99-4be7-82d3-39e2701271a2" />

---

### Panel administrativo

En la parte administrativa se usa el gestor por defecto de Django.

<p align="center">
  <img width="960" height="340" alt="inicio administración" src="https://github.com/user-attachments/assets/1defcd56-586c-45cf-ab26-c544b764ddf1" />
</p>

---

Para ingresar, usar el link que brinda la terminal y añadir /admin.
 ```
Ejemplo: http://127.0.0.1:8000/admin

Usuario ya creado:

Usuario: usuario

Contraseña: desarrolloweb
```
### Inserción de juegos

Es importante primero crear los motores de videojuegos.
La base de datos incluye dos: Unity y RPGMaker.

<img width="960" height="466" alt="motor administración" src="https://github.com/user-attachments/assets/e8a6513a-a526-42e4-bfe7-0b3473178366" />

---

Para insertar juegos en la tabla "Tres populares", primero deben estar insertados en la tabla de juegos.
Los nombres de los juegos registrados muestran las dimensiones de las imágenes.

Para mantener la estética de la web, se deben subir imágenes en esa resolución.

<img width="959" height="440" alt="3 populares administración" src="https://github.com/user-attachments/assets/6bca287c-2eec-4581-bfc8-2563bc3ffc8c" />

---
<img width="942" height="481" alt="ingreso juegos administración" src="https://github.com/user-attachments/assets/a9bcf285-3a98-41b7-9d38-864a740aa8c0" />

---
