# 🧮 E-commerce Funnel & Cohort Analysis 

Este repositorio contiene un análisis del comportamiento de los usuarios de una plataforma de comercio electrónico mediante dos enfoques complementarios: Funnel Analysis y Cohort Analysis.

El análisis del funnel permite evaluar la eficiencia del proceso de compra, identificando las etapas donde los usuarios abandonan el recorrido antes de completar una transacción. Por su parte, el análisis de cohortes estudia la retención de clientes a lo largo del tiempo, permitiendo medir la fidelización y detectar patrones de recompra.

El objetivo es proporcionar información que apoye la toma de decisiones para optimizar la experiencia del usuario, aumentar la conversión y fortalecer las estrategias de retención de clientes.

El dataset `customers` contiene los datos de registrol de los clientes de la plataforma electrónica.
El dataset `events` contiene datos de comportamientos de clientes en la plataforma electrónica.
El dataset `orders` contiene datos de las ordenes de compra realizadas por los clientes en la plataforma electrónica.
El dataset `sessions` contiene datos de las sesiones registradas de interacción de los clientes en la plataforma.


## 📂 Contenido del repositorio

- `/Analisis_funnel_cohortesSQL.ipynb`
  → Notebook principal con limpieza, análisis de correlaciones y conclusiones.
- Datasets →Links a datasets trabajados

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar este notebook de las siguientes formas:

### Opción 1: Abrir en Google Colab
- Ve a Google Colab
- Haz clic en “File” > “Open notebook”
- Selecciona la pestaña “GitHub”
- Pega el enlace de este repositorio
- Abre el archivo .ipynb

### Opción 2: Ejecutar en local

- Clona este repositorio:
git clone [https://github.com/pablojbec/Analisis_Correlacional]
- Accede a la carpeta del proyecto:
- cd repositorio

- Abre Jupyter Notebook:
  - jupyter notebook
  - Selecciona el archivo .ipynb y ejecútalo

## 🔁 Guía de reproducción
Para reproducir los resultados:

- Instala las dependencias necesarias (recomendado usar entorno virtual o Anaconda):
pip install -r requirements.txt
- Asegúrate de tener los datos en la ruta correcta (ver carpeta /data si aplica)
- Ejecuta las celdas del notebook en orden, desde el inicio
- Verifica que no haya errores y que los outputs coincidan con los esperados

## 🧠 Objetivo del análisis

- Analizar el recorrido de los usuarios durante el proceso de compra.
- Calcular las tasas de conversión entre las diferentes etapas del embudo.
- Identificar los principales puntos de abandono del proceso de compra.
- Evaluar la retención mensual de clientes mediante cohortes.
- Detectar patrones de fidelización y reactivación de usuarios.
- Generar recomendaciones basadas en datos para mejorar la conversión y la retención.

## 🧩Etapas de análisis realizadas

- Exploración inicial del conjunto de datos.
- Limpieza y validación de registros.
- Identificación de eventos relevantes del proceso de compra.
- Agrupación de eventos por usuario.
- Construcción del embudo de conversión.
- Cálculo de indicadores de conversión.
- Búsqueda de la primera compra del cliente.
- Creación de la cohorte correspondiente.
- Calculo del número de meses desde la primera compra.
- Construcción de la matriz de retención.
- Calculo de los porcentajes de retención para cada cohorte.
- Interpretación de resultados.
- Elaboración de recomendaciones de negocio.
