



# ImageWork
  
Combina imágenes según coordenadas, convierte imágenes a PDF y encuentra las coordenadas de una imagen dentro de otra  
  
![banner](imgs/Banner_ImageWork.png)
## Como instalar este módulo
  
__Descarga__ e __instala__ el contenido en la carpeta 'modules' en la ruta de rocketbot.  



## Descripción de los comandos

### Combinar imágenes
  
Mezcla dos imágenes
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Path del archivo JPG a mezclar||Ruta/File.jpg|
|Path del segundo archivo JPG a mezclar||Ruta/File.jpg|
|Coordenadas||150, 340|
|Resultado|Variable donde se guardará True cuando finalice la combinación||

### Convertir a PDF
  
Convierte archivos JPG a PDF
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Path de la carpeta con archivos JPG||Ruta/Imagenes_JPG|
|Path y nombre del PDF||Ruta/Nuevo_Archivo.pdf|
|Resultado|Ruta donde se guardará True al finalizar el proceso (opcional)||

### Buscar imagen
  
Busca las coordenadas de una imagen contenida en otra imagen
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Path de imagen a buscar||image.JPG|
|Path de la imagen donde buscar||Image.JPG|
|Resultado|Nombre de la variable donde se guardarán las coordenadas de la imagen encontrada||

### Extraer texto
  
Extrae el texto de un área específica de una imagen
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Path del archivo JPG o PDF||JPG o PDF|
|Coordenadas||150, 340|
|Dimensiones||250x200|
|Página|||
|Resultado|Variable donde se guardará el texto extraído||

### Recortar imagen
  
Corta una imagen desde coordenadas
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Imagen de entrada JPG o PNG:||/ruta/a/imagen.png|
|Path y nombre de imagen nueva:||/ruta/a/imagenNueva.png|
|Coordenadas||x,y|
|Dimensiones||width, height|

### Rotar imagen
  
Rota una imagen en un ángulo determinado
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Imagen de entrada||ruta/a/imagen.png|
|Angulo de rotacion||-90|
|Imagen de salida||ruta/a/imagen.png|
