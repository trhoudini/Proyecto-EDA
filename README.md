🧠 Proyecto EDA con Python

📖 Descripción del Proyecto

Este proyecto forma parte del módulo de Python for Data y tiene como objetivo aplicar técnicas de análisis exploratorio de datos (EDA) sobre dos conjuntos de datos provenientes del sector bancario.

•	bank-additional_limpio.csv: Datos de campañas de marketing telefónico de una entidad financiera portuguesa.

•	customer-details_multihoja.xlsx: Información sobre características demográficas y comportamiento digital de los clientes, divididos por año de alta (2012, 2013 y 2014).

El propósito es comprender mejor el perfil de los clientes, los factores que influyen en su comportamiento, y extraer conclusiones relevantes para la toma de decisiones comerciales o de marketing.

Principales técnicas aplicadas:

•	Transformación y limpieza de datos con Pandas.

•	Visualización con Matplotlib y Seaborn.

•	Análisis estadístico descriptivo (media, mediana, desviación estándar, cuartiles, mínimos y máximos).

•	Segmentaciones con groupb y filtros condicionales.

•	Comparación multianual


📁 Estructura del Proyecto

├── data/                                                                    # Carpeta de datos

│   ├── output/                                                          # Datos procesados / limpios

│   │   ├── bank-additional_limpio.csv

│   │   └── customer-details_multihoja.xlsx

│   └── raw/                                                                  # Datos originales sin procesar

│   │   ├── bank-additional.csv

│   │   └── customer-details.xlsx

│

├── notebook/                                                           # Notebooks Jupyter con el análisis

│   ├── 01-Analisis_preliminar_bank.ipynb           # Análisis exploratorio inicial - banco

│   ├── 01-Analisis_preliminar_customer.ipynb   # Análisis exploratorio inicial - clientes

│   ├── 02-Limpieza_bank.ipynb                             # Limpieza de datos - banco

│   ├── 02-Limpieza_customer.ipynb                     # Limpieza de datos - clientes

│   ├── 03-EDA_bank.ipynb                                     # Análisis EDA final - banco

│   └── 03-EDA_customer.ipynb                               # Análisis EDA final - clientes

│

├── src/                                                                      # Código fuente de apoyo

│   └── soporte.py                                                      # Funciones reutilizables o utilidades

│

├── .gitignore                                                           # Archivos y carpetas ignorados por Git

├── DataProject_ Proyecto EDA con Python   # Documento de explicación del proyecto

├── README.md                                                    # Descripción completa del proyecto

└── Subir archivo GitHub.docx                              # Instrucciones para subir a GitHub


🛠 Instalación y Requisitos

Este proyecto está desarrollado en Python desde Visual Studio Code (VSCode). Para ello, se requiere instalar la extensión de Python para ejecutar el código Python dentro del programa.

Se requiere instalar los siguientes paquetes:

•	pip install pandas matplotlib seaborn openpyxl para ejecutar archivos xlsx.

•	import pandas as pd


📊 Resultados y Conclusiones

-	 bank-additional_limpio.csv
  
•	Análisis de variables demográficas: edad, estado civil, ocupación, educación.

•	Estudio de campañas de marketing: duración de llamadas, número de contactos, método de contacto.

•	Variables macroeconómicas: euribor, tasa de empleo, confianza del consumidor.

•	Análisis de la variable objetivo y: contratación del depósito bancario.

•	Visualización de correlaciones, distribuciones y patrones por segmento.

Conclusiones destacadas:

•	Clientes más jóvenes y sin hipotecas muestran mayor probabilidad de contratación.

•	Llamadas más largas y menos frecuentes tienden a ser más efectivas.

•	El canal de contacto tiene impacto: cellular fue más exitoso que telephone.

•	La tasa de éxito fue baja en general (~11%), por lo que se identifican oportunidades de mejora en targeting.

-	 customer-details_multihoja.xlsx
  
•	Análisis independiente de los años 2012, 2013 y 2014.

•	Estudio de ingresos, número de hijos, número de adolescentes, visitas web mensuales y fecha de alta del cliente.

•	Análisis de la distribución de ingresos por número de niños en el hogar, ingresos promedio por número de visitas web, altas de clientes por mes y visitas web según mes de captación.

Comparativa entre años:

Variable	2012	2013	2014

N.º Clientes	20.115	8.965	14.090

Ingreso Promedio	≈ 93.000 €	≈ 93.000 €	≈ 94.000 €

Visitas Web / mes	Media: 16.54	  Igual	Ligeramente mayor

Antigüedad promedio	Más antiguos	Más recientes	Intermedios

Conclusiones destacadas:

•	Perfil estable a lo largo de los años.

•	No se observa una relación clara entre ingresos y visitas web.

•	Los clientes con más hijos no necesariamente tienen mayores ingresos ni son más activos digitalmente.

•	Segmentar por antigüedad puede ser más útil que segmentar por ingresos.


🔄 Próximos Pasos

•	Profundizar en análisis predictivos (modelos de clasificación).

•	Usar técnicas de segmentación avanzada (clustering).

•	Integrar ambos datasets para cruzar comportamiento y conversión.


🤝 Contribuciones

Si te interesa mejorar o extender este proyecto, las contribuciones son bienvenidas.


✒ Autor

Autor: Francisco Troyano Martínez.  

Contacto: troyano1406@gmail.com .

GitHub: https://github.com/trhoudini .

Proyecto realizado como parte del módulo de Python for Data en el programa de formación de Data Analytics.
