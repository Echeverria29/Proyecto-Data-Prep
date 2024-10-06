# Proyecto de Descarga y Preparación de Datos para Data Prep
Este proyecto tiene como objetivo descargar, descomprimir y procesar archivos desde una página web pública, convertir los archivos de texto a formato CSV y prepararlos para ser limpiados en Data Prep, una herramienta visual de procesamiento de datos.
![](https://github.com/Echeverria29/Proyecto-de-Descarga-y-Preparaci-n-de-Datos-para-Data-Prep/blob/main/dataprep.png)
# Descripción del Proyecto 🚀
El proyecto descarga archivos desde una página web utilizando requests y BeautifulSoup, descomprime el contenido en el escritorio local y convierte archivos de texto a formato CSV para un análisis más fácil. Luego, se eliminan los archivos temporales, dejando solo los archivos necesarios para su posterior procesamiento en Data Prep.

# Arquitectura de la Solución 🏗️
Requests: Utilizado para realizar solicitudes HTTP y descargar archivos.
BeautifulSoup: Para extraer enlaces de descarga desde la página web.
Pandas: Utilizado para la conversión de archivos de texto a CSV.
OS y ZipFile: Para el manejo de archivos locales y descompresión.
Archivos de Código
Función: function_data3_local
Esta función realiza una solicitud GET a una página web de transporte público, extrae el enlace del archivo ZIP, lo descarga y descomprime en el directorio especificado. Además, convierte los archivos de texto descargados a formato CSV.

# Pre-requisitos 📋
Python 3.x: Para ejecutar el código y utilizar las bibliotecas necesarias.
Pandas: Para manipulación de datos.
Requests: Para descargar archivos desde la web.
BeautifulSoup: Para realizar scraping de la página web.
ZipFile: Para manejar archivos comprimidos.
# Instalación 🔧
Asegúrate de tener instaladas las bibliotecas necesarias ejecutando:
bash
Copiar código
pip install pandas requests beautifulsoup4
Configura las rutas locales donde se descargarán y guardarán los archivos CSV y TXT.

# Ejecución del Proyecto ⚙️
Descargar y Descomprimir: Ejecuta la función function_data3_local para descargar el archivo ZIP desde la página web, descomprimir los archivos y convertir los archivos de texto a formato CSV.

# Preparar Archivos para Data Prep:
Los archivos resultantes estarán listos para ser cargados y limpiados utilizando la herramienta visual Data Prep.

# Objetivo Final 🎯
El objetivo de este proyecto es preparar los datos descargados para su limpieza y procesamiento utilizando Data Prep, una herramienta visual que facilita la depuración y transformación de datos, asegurando que los datos estén en el formato correcto (CSV) y listos para el análisis.

# Construido con 🛠️
Pandas - Para manipulación de datos y conversión de archivos de texto a CSV.
Requests - Para manejar las solicitudes HTTP.
BeautifulSoup - Para extraer enlaces y realizar scraping de páginas web.
OS y ZipFile - Para manejo de archivos y descompresión de archivos ZIP.
# Autor ✒️
Orlando Echeverría Hernández
Expresiones de Gratitud 🎁
Comparte este proyecto con otros.
