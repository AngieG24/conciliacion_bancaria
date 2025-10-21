💰 Proyecto: Conciliación Bancaria Automatizada
📖 Descripción

Este proyecto implementa una herramienta de conciliación bancaria automatizada, diseñada para comparar y cruzar información entre extractos bancarios y auxiliares contables.

La aplicación permite subir archivos en formato Excel, estandarizar su estructura, aplicar reglas de cruce y descargar un reporte conciliado con formato contable.
El desarrollo combina la potencia de pandas para la manipulación de datos, openpyxl para el formato en Excel y Streamlit como interfaz interactiva.

🎯 Objetivo general

Desarrollar una aplicación que automatice el proceso de conciliación bancaria, mejorando la eficiencia y precisión en el control contable.

📌 Objetivos específicos

- Implementar un sistema de transformación de datos adaptable a diferentes fuentes contables.
- Aplicar reglas lógicas que permitan identificar coincidencias exactas o aproximadas entre los registros.
- Generar un archivo Excel con resultados conciliados y no conciliados, resaltando visualmente las diferencias.
- Brindar una interfaz sencilla para usuarios del área contable sin necesidad de conocimientos técnicos.

🧠 Tecnologías utilizadas

- Python 3.11+
- Streamlit – Interfaz de usuario interactiva.
- pandas – Limpieza y transformación de datos.
- openpyxl – Formato y exportación de archivos Excel.
- re – Expresiones regulares para limpieza de texto.

⚙️ Estructura del proyecto
conciliacion_bancaria/
│
├── app.py                    # Código principal del proyecto
├── README.md                 # Documentación del proyecto
├── requirements.txt          # Dependencias del entorno
└── conciliacion.xlsx         # Archivo resultante (se genera automáticamente)

🚀 Cómo ejecutar el proyecto

1. Clona el repositorio o descarga los archivos del proyecto:
git clone https://github.com/tuusuario/conciliacion-bancaria.git

2. Instala las dependencias necesarias:
pip install -r requirements.txt

3. Ejecuta la aplicación en Streamlit:
streamlit run app.py

4. Carga los archivos de Extracto y Auxiliar en formato .xlsx y descarga el reporte conciliado.

📊 Ejemplo de resultado

- El archivo descargado (conciliacion.xlsx) incluye:
- Registros conciliados y no conciliados.
- Formato numérico contable.
- Filas del tipo Extracto resaltadas en color azul.
- Separador entre registros conciliados y pendientes.

👩‍💼 Autora

Angie Galindo
Contadora Pública | Analista de Datos
💡 Apasionada por la automatización de procesos contables mediante Python y herramientas de análisis de datos.
📫 LinkedIn: 💰 Proyecto: Conciliación Bancaria Automatizada
📖 Descripción

Este proyecto implementa una herramienta de conciliación bancaria automatizada, diseñada para comparar y cruzar información entre extractos bancarios y auxiliares contables.

La aplicación permite subir archivos en formato Excel, estandarizar su estructura, aplicar reglas de cruce y descargar un reporte conciliado con formato contable.
El desarrollo combina la potencia de pandas para la manipulación de datos, openpyxl para el formato en Excel y Streamlit como interfaz interactiva.

🎯 Objetivo general

Desarrollar una aplicación que automatice el proceso de conciliación bancaria, mejorando la eficiencia y precisión en el control contable.

📌 Objetivos específicos

Implementar un sistema de transformación de datos adaptable a diferentes fuentes contables.

Aplicar reglas lógicas que permitan identificar coincidencias exactas o aproximadas entre los registros.

Generar un archivo Excel con resultados conciliados y no conciliados, resaltando visualmente las diferencias.

Brindar una interfaz sencilla para usuarios del área contable sin necesidad de conocimientos técnicos.

🧠 Tecnologías utilizadas

Python 3.11+

Streamlit – Interfaz de usuario interactiva.

pandas – Limpieza y transformación de datos.

openpyxl – Formato y exportación de archivos Excel.

re – Expresiones regulares para limpieza de texto.

⚙️ Estructura del proyecto
conciliacion_bancaria/
│
├── app.py                    # Código principal del proyecto
├── README.md                 # Documentación del proyecto
├── requirements.txt          # Dependencias del entorno
└── conciliacion.xlsx         # Archivo resultante (se genera automáticamente)

🚀 Cómo ejecutar el proyecto

Clona el repositorio o descarga los archivos del proyecto:

git clone https://github.com/tuusuario/conciliacion-bancaria.git


Instala las dependencias necesarias:

pip install -r requirements.txt


Ejecuta la aplicación en Streamlit:

streamlit run app.py


Carga los archivos de Extracto y Auxiliar en formato .xlsx y descarga el reporte conciliado.

📊 Ejemplo de resultado

El archivo descargado (conciliacion.xlsx) incluye:

Registros conciliados y no conciliados.

Formato numérico contable.

Filas del tipo Extracto resaltadas en color azul.

Separador entre registros conciliados y pendientes.

👩‍💼 Autora

Angie Galindo
Contadora Pública | Analista de Datos
💡 Apasionada por la automatización de procesos contables mediante Python y herramientas de análisis de datos.
📫 LinkedIn: https://www.linkedin.com/in/angielorenagalindo/
