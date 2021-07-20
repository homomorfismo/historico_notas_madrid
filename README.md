# Histórico de las notas de corte en Madrid
Evolución de las notas de corte en todas las universidades públicas de Madrid desde 2010 hasta 2021
 
### Bases de datos
Las notas de corte se han extraído de la [página web de la UC3M](https://www.uc3m.es/admision/notas-corte) que conserva en formato .pdf las publicaciones de todas las notas de corte desde el curso 2007/2008. A partir de estos archivos, se han generado los ficheros .csv para cada universidad. Para ello se ha usado el programa [Tabula](https://tabula.technology/) para extraer los datos de los .pdf y R para aunar todos los datos.

### Gráficos
Los gráficos de las notas se han creado en R con la libreria `ggplot2`.

### Página web
Se pueden ver los gráficos de forma más cómoda en [esta página](https://homomorfismo.github.io/historico_notas_madrid/).
