# konvertilo  ![](./logo.png)
File converter and batch processor.

# Advertencia
En el caso de la herramienta para acomodar fotografias y vdeos.

Es importante tener en cuenta que esta es una herramienta en desarrollo y no conviene trabajar con la unica copia de las fotos, por lo menos hasta que no se hacen varias pruebas. Debido a que cada Cámara tiene sus propias etiquetas exif.
Por ejemplo para la fecha de captura:

## Dependencias
Segun sea la distribucion linux que se utilice las dependencias pueden variar el nombre del paquete y en la forma de instalarlos, por ejemplo el paquete pdftk que sirve para manejar archivos PDF no está disponible en el repositorio "core" de Arch pero si esta en AUR, por lo tanto para instalar dicho paquete implicara descargar fuentes y compilar   son las siguientes:

# Debian, Ubuntu, Mint y similares.
perl-image-exiftool
libav-tools
pst-utils
mdbtools
pdftk
imagemagick
tesseract-ocr
tesseract-ocr-cat
tesseract-ocr-deu
tesseract-ocr-eng
tesseract-ocr-epo
tesseract-ocr-fra
tesseract-ocr-glg
tesseract-ocr-ita
tesseract-ocr-por
tesseract-ocr-rus
tesseract-ocr-spa
libttspico-utils
mplayer

# Arch, Manjaro
perl-image-exiftool
libav-tools
pst-utils (No Existe)
mdbtools (AUR)
pdftk (AUR)
imagemagick
tesseract-ocr
tesseract-ocr-cat
tesseract-ocr-deu
tesseract-ocr-eng
tesseract-ocr-epo
tesseract-ocr-fra
tesseract-ocr-glg
tesseract-ocr-ita
tesseract-ocr-por
tesseract-ocr-rus
tesseract-ocr-spa
libttspico-utils
mplayer

### Media Create Date
Fairphone 2 jpg
Leica mov

### Date/Time Original
Fairphone 2 mp4

Nota: Si quiere ayudar a mejorar esta herramienta envie la salida de la orden bash para cada uno de sus tipos de archivo detallando si no aparece, el fabricante de la cámara y el modelo. O envie una fotografia o un video de uno o dos segundos, hechos con su cámara.

### exiftool -f -s -s fotografia.jpg > exif-fabricante-modelo.txt

El sistema de dependencias en el ide y en los paquetes .deb .rpm etc.

Atencion con los directorios y archivos con nombres que tienen espacios.


# Herramientas
## General

### Media>Arrange
* Mueve las fotografias y videos, organizandolas según su fecha de captura, a una ruta como por ejemplo:
 YYYYF/MM/YYYYMMDDHHNNSS-MARCA-MODELO-CRC32.JPEG Donde:
 YYYY es el año y la F es de fotos, la V es de videos, MM es el mes, DD es el dia, HH es la hora, NN es el minuto, SS es el segundo, MARCA es la marca de la cámara de fotos, MODELO es el modelo de la cámara de fotos y CRC32 es el codigo crc del archivo.
Es una herramienta pensada para las fotos y los videos que hacemos con las camaras, no para los medios transmitidos por sistemas de chats, ya que estos les quitan todos los metadatos.

### File-Rename
Renombrador de archivos

### File-Check
Verificador de nombre de archivo

## JPEG

### JPEG>Email
Crea copias reducidas en un directorio temporal y las adjunta en un nuevo email.

### JPEG>GIFEmail
* Crea un archivo GIF y lo adjunta en un nuevo email.

### JPEG>Copy-Reduced-Color
Crea una copia reducida en la misma ubicación que la original

### JPEG>Copy-Reduced-Gray
Crea una copia reducida en escala de grices en la misma ubicación que la original

### JPEG>Copy-Gray
Crea una copia en escala de grices en la misma ubicación que la original

### JPEG>Square
Crea una copia reducida de proporción cuadrada en la misma ubicación que la original.

### JPEG>PDF
Crea un archivo PDF con todas	 las imagenes que se le pase.

## PNG

### PNG>Copy-Reduced-Color
Crea una copia reducida en la misma ubicación que la original

### PNG>JPEG-Copy-Reduced-Color
* Crea una copia reducida en la misma ubicación que la original

## ODT

### ODT-Thumbnail
Extractor de miniatura del documento

## ODT>EPUB
Convertir documentos ODT en documentos EPUB

## PDF

### PDF>Decrypt
* Crea una copia sin encriptar.

### PDF>Image
* Extractor de paginas en formato de imagen jpeg una imagen por página.

### PDF>Pages
Extractor de paginas en formato pdf

### PDF>OCR-Text
Extractor de paginas en formato de imagen TIF y reconocimiento optico de caracteres

### PDF>PDF-R90
* Rotar las paginas del archivo 90 grados.

## Video

### Video>Frame
Extractor de fotograma de un video


