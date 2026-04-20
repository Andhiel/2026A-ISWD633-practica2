# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Como sucedió con la practica anterior, no tenia ningun conocimiento previo sobre docker tan practicos como ahora, por lo que tuve que investigar y aprender sobre docker y sus conceptos basicos, en bases distribuidas conocer todo esto hubiera sido fenomenal y super util.
Considero que es una herramienta que se de previsualiar en materias como bases de datos y sistemas distribuidos o anteriores, y ahora simplemente enfocarse en sus aplicaciones.

Consultar: Cómo se gestionan datos confidenciales con los secretos de Docker (Docker Secrets).

Docker secrets son archivos que se crean en el sistema de archivos del host y se montan en los contenedores como volúmenes.
Los cuales podemos usarlos para almacenar información sensible como contraseñas, claves API, etc.
Para gestionarlos se puede usar el comando `docker secret create <nombre> <archivo>` y luego usarlos en los contenedores con el flag `--secret <nombre>`.
