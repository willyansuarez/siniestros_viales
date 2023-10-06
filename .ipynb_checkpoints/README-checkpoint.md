# siniestros_viales
2do proyecto individual para bootcamp Soy Henry

**Proyecto de Análisis de Siniestros Viales en la Ciudad Autónoma de Buenos Aires - Años 2016 al 2021**  
Este proyecto tiene como objetivo analizar los siniestros viales ocurridos en la Ciudad Autónoma de Buenos Aires, con el fin de obtener información valiosa que pueda contribuir a mejorar la seguridad vial en la ciudad.

**Descripción del proyecto**  
El proyecto se enfoca en recopilar y analizar datos relacionados con los siniestros viales, incluyendo información sobre la ubicación, fecha, hora, tipo de siniestro, vehículos involucrados, condiciones climáticas, entre otros factores relevantes. Utilizando técnicas de análisis de datos, se buscará identificar patrones, tendencias y posibles causas de los siniestros viales, con el objetivo de proponer medidas preventivas y de mitigación.

**Estructura del repositorio**  
**datasets/:** Carpeta que contiene los conjuntos de datos utilizados en el análisis.  
**diccionarios de datos/:** Carpeta que contiene los diccionarios de los datos utilizados para el análisis de datos.  
**informe/:** Carpeta con el informe en formato pdf y odt.  
**EDA.ipynb:** Notebook que contiene los pasos realizados para el análisis.  
**README.md:** Archivo con la descripción del proyecto.  

**Librerías utilizadas**  
* Pandas
* Plotly
* Openpyxl (para cargar los datos en xlsx o xls) igual se proporcionan los .csv
* Jupyter Lab

**Instrucciones de instalación** 
* Clona este repositorio en tu máquina local.
* Instala las dependencias necesarias utilizando el archivo requirements.txt.
* pip install -r requirements.txt

Se procede a pasar los archivos xlsx a csv, para esto simplemente abra los archivos con su hoja de cálculo y guarde como .csv, en este caso se hizo con libreoffice calc versión: 7.4.6.2.  
Puede también usar la librería openpyxl para cargar directamente los archivos xlsx, si los archivos contienen varias hojas, solo cargará la primera por defecto, para cargar otras hojas deberá especificarla en los parámetros de carga.

**Cómo utilizar** 
Abre el notebook EDA.ipynb en Jupyter Notebook o Jupyter Lab.
Sigue las instrucciones detalladas en el notebook para cargar los datos, realizar el análisis y obtener los resultados.

**Contribuciones**  
¡Las contribuciones son bienvenidas! Si deseas colaborar en este proyecto, asegúrate de seguir las siguientes pautas:

**Contacto**  
Si tienes alguna pregunta o sugerencia sobre este proyecto, no dudes en ponerte en contacto conmigo a través de mi dirección de correo electrónico o mediante el sistema de issues de GitHub.  
Correo: willyanjosesuarez@gmail.com

¡Gracias por tu interés en este proyecto! Espero que sea de utilidad para mejorar la seguridad vial en la Ciudad Autónoma de Buenos Aires.
