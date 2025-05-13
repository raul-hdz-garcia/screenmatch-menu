# Buscar información sobre series y sus temporadas y episodios

**Tecnologías utilizadas**
- Java
- Spring Boot
- PostgreSQL

**Descripción del proyecto** </br>
Al ejecutar el programa se muestra el siguiente menú inicial: </br>
![image](https://github.com/user-attachments/assets/c7655abe-0301-4f80-8cc9-66a33ec56f5f)

Opción 1 - Buscar series </br>
Esta opción requiere ingresar el nombre de una serie para buscar sus datos.
Este proyecto consume la API https://www.omdbapi.com/ cada vez que busca una serie y guarda los datos en una base de datos local en PostgreSQL.
Luego se muestra el resultado de la búsqueda:
![image](https://github.com/user-attachments/assets/fe99c137-ef82-441c-9ae1-850a9fd7363d)

Opción 3 - Mostrar series buscadas </br>
Muestra las series que han sido buscadas y guardadas en la base de datos:
![image](https://github.com/user-attachments/assets/b9be7d04-8f57-4d36-b14b-5cdc0172b54b)

Opción 2 - Buscar episodios </br>
Muestra las series que han sido buscadas y guardadas en la base de datos. </br>
Se selecciona una de las series y se muestran los episodios de la serie ordenados por temporada: </br>
![image](https://github.com/user-attachments/assets/15d0d500-9b20-402a-bbbb-7287054ebcef)

Opción 4 - Buscar series por título </br>
Busca una serie dentro de las guardadas en la base de datos. </br>
Si la serie aún no ha sido guardada, se muestra este resultado: </br>
![image](https://github.com/user-attachments/assets/7510c86b-c182-44e6-b382-bc8a6d070ce9)

En cambio si la serie ya ha sido guardada, se muestra este resutlado: </br>
![image](https://github.com/user-attachments/assets/3ea425a7-1672-4288-a576-38efd7fb735b)

Opción 5 - Top 5 mejores series </br>
Muestra las 5 series guardadas en la base de datos local con la evaluación más alta ordenadas de mayor a menor: </br>
![image](https://github.com/user-attachments/assets/7ec08174-232e-43fc-a562-d7a9b550b77d)

Opción 6 - Buscar series por categoría </br>
Muestra las series guardadas del género seleccionado: </br>
![image](https://github.com/user-attachments/assets/bfcf9ef3-e2d4-432d-a748-c93ca1ab7bed)

Opción 7 - Filtrar series </br>
Se muestran las series que cumplen con el número mínimo de temporadas y la calificación mínima indicados por el usuario: </br>
![image](https://github.com/user-attachments/assets/5bf407b8-69ee-4350-a3ba-07979714a6a3)

Opción 8 - Buscar episodios por título </br>
Se busca dentro de los episodios de las series guardadas y se muestran los datos del episodio cuyo título contine el texto especificado por el usuario: </br>
![image](https://github.com/user-attachments/assets/8256f00f-19ae-4ce5-b32e-df09eeab31aa)

Opción 9 - Top 5 episodios por serie </br>
El usuario selecciona una serie guardada y se muestran los 5 episodios de la serie con evaluación más alta ordenados de mayor a menor: </br>
![image](https://github.com/user-attachments/assets/68baaca0-5272-4ea4-9c6a-c6d2d4e84659)

La opción 0 termina la ejecución del programa.
