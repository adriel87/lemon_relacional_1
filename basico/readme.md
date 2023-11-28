# El modelo ER

para el ejercicio propuesto he pensado que con las siguientes tablas podria cumplir con los requisitos:

- curso, guardamos informacion como el titulo y la descripcion del curso
- leccion, un curso esta formado por una o mas lecciones
- autor, informacion referente al autor desde su nombre a su biografia
- mediaDocument, aqui guardaremos tanto articulos como videos creados o no por el autor. Importante no guardamos en si el fichero guardamos la localizacion del mismo, una URL

## las relaciones

- curso_autor

con esta relacion podemos indicar todos los autores de un curso o los cursos en los que participan un determinado autor

- curso_leccion

las lecciones pertenecientes a un curso, es posible que una misma leccion se pueda impartir en varios cursos, algo como `conceptos basicos de git`

- leccion_mediadocument

para relacionar las lecciones con los archivos que necesitemos tanto de video como articulos