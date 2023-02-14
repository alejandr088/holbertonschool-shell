#RESUMEN Y DEFINICIONES DE EJERCICIO 26

tail -n +2: este comando imprime todas las líneas de la entrada excepto la primera línea (la cabecera), que se omite usando el argumento -n +2.
sort: este comando ordena alfabéticamente las líneas de la entrada.
cut -f1: este comando elimina todas las columnas de la entrada excepto la primera columna, separada por tabulaciones.
uniq -c: este comando cuenta cuántas veces aparece cada línea de la entrada y las agrupa.
sort -g -r: este comando ordena numéricamente las líneas de la entrada en orden descendente.
head -11: este comando imprime las primeras 11 líneas de la entrada.
tr -s " ": este comando comprime los espacios en blanco consecutivos de la entrada en un solo espacio.
cut -d" " -f3: este comando elimina todas las columnas de la entrada excepto la tercera columna, separada por espacios en blanco.

En resumen, este comando elimina la primera línea de la entrada, ordena alfabéticamente la entrada, elimina todas las columnas excepto la primera, cuenta cuántas veces aparece cada línea y las ordena por frecuencia en orden descendente, imprime las primeras 11 líneas, comprime los espacios en blanco consecutivos y finalmente imprime la tercera columna de cada línea.
