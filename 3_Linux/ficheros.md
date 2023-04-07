```
cat 
```
Muestra el contenido completo de un archivo. Por ejemplo, cat archivo muestra todo el contenido del archivo "archivo".
```
less
```
Muestra el contenido de un archivo de manera paginada, permitiendo al usuario avanzar y retroceder por el contenido. Por ejemplo, less archivo muestra el contenido del archivo "archivo" página por página.
```
head
``` 
Muestra las primeras líneas de un archivo. Por ejemplo, head -n 10 archivo muestra las primeras 10 líneas del archivo "archivo".
```
tail
``` 
Muestra las últimas líneas de un archivo. Por ejemplo, tail -n 5 archivo muestra las últimas 5 líneas del archivo "archivo".
```
grep
```
Busca patrones de texto en un archivo. Por ejemplo, grep "patrón" archivo busca el "patrón" en el archivo "archivo".
```
wc
```
Cuenta el número de líneas, palabras y caracteres en un archivo. Por ejemplo, wc archivo muestra el número de líneas, palabras y caracteres en el archivo "archivo".
```
sort
```
Ordena las líneas de un archivo en orden alfabético o numérico. Por ejemplo, sort archivo ordena las líneas del archivo "archivo" en orden alfabético.
```
cut
``` 
Extrae una sección de cada línea de un archivo. Por ejemplo, cut -d ":" -f 1 archivo extrae la primera columna de datos separados por ":" en el archivo "archivo".
```
awk 
```
Busca y procesa patrones en un archivo. Por ejemplo, awk '/patrón/ {print $2}' archivo busca el "patrón" en el archivo "archivo" y muestra la segunda columna de la línea que coincide.
```
diff 
```
Compara dos archivos línea por línea. Por ejemplo, diff archivo1 archivo2 muestra las diferencias entre los archivos "archivo1" y "archivo2".