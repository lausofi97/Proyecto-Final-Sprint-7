# Proyecto-Final-Sprint-7
# 📊 Proyecto: Análisis Exploratorio de Clientes - ConnectaTel

## 📌 Objetivo del proyecto

El objetivo de este proyecto es realizar un Análisis Exploratorio de Datos (EDA) sobre la información de clientes de ConnectaTel con el fin de identificar patrones de comportamiento, segmentar a los usuarios según su edad y nivel de uso, detectar valores atípicos y generar recomendaciones de negocio que contribuyan a mejorar la oferta de planes y la toma de decisiones comerciales.

---

## 📂 Datasets utilizados

El análisis se realizó utilizando los siguientes conjuntos de datos:

- **users.csv**: Información demográfica de los clientes (edad, ciudad, fecha de registro, plan contratado y estado del servicio).
- **calls.csv**: Historial de llamadas realizadas por los clientes.
- **messages.csv**: Registro de mensajes enviados.
- **internet.csv**: Consumo de datos móviles de los clientes.

Estos datasets fueron integrados para analizar el comportamiento de uso de los usuarios y construir segmentos de clientes.

---

## 🔎 Etapas del análisis

Durante el desarrollo del proyecto se realizaron las siguientes etapas:

1. **Carga de datos**
   - Importación de librerías.
   - Lectura de los archivos CSV.

2. **Exploración inicial**
   - Revisión de estructura, tipos de datos y dimensiones.
   - Identificación de valores faltantes y registros duplicados.

3. **Limpieza y preparación de datos**
   - Corrección de tipos de datos.
   - Tratamiento de valores faltantes.
   - Validación de la calidad de la información.

4. **Análisis Exploratorio de Datos (EDA)**
   - Estadísticos descriptivos.
   - Distribución de variables.
   - Detección de valores atípicos (outliers).
   - Visualización mediante gráficos.

5. **Segmentación de clientes**
   - Segmentación por grupos de edad.
   - Clasificación según el nivel de uso del servicio.
   - Comparación del comportamiento entre segmentos.

6. **Generación de insights**
   - Identificación de los segmentos de mayor valor.
   - Análisis de patrones de consumo.
   - Elaboración de recomendaciones para el negocio.

---

## ▶️ Cómo ejecutar el proyecto

Este proyecto fue desarrollado en **Google Colab**.

Para ejecutarlo:

1. Descargue el archivo `S7 Version-Estudiante-Project-ConnectaTel.ipynb`.
2. Abra Google Colab.
3. Seleccione **Archivo → Subir notebook**.
4. Cargue el archivo `.ipynb`.
5. Asegúrese de que los archivos CSV se encuentren en la misma carpeta o súbalos al entorno de Colab.
6. Ejecute las celdas en orden desde la primera hasta la última.

---

## 🔄 Guía de reproducción

Para reproducir completamente el análisis:

1. Clonar o descargar este repositorio.
2. Verificar que los siguientes archivos estén disponibles:
   - `users.csv`
   - `calls.csv`
   - `messages.csv`
   - `internet.csv`
   - `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
3. Abrir el notebook en Google Colab.
4. Ejecutar todas las celdas en el orden establecido.
5. Revisar las visualizaciones, tablas e insights generados al final del notebook.

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Resultados principales

El análisis permitió:

- Identificar y tratar problemas de calidad en los datos.
- Segmentar a los clientes por edad y nivel de uso.
- Detectar usuarios con patrones de consumo atípicos.
- Generar recomendaciones para optimizar la oferta de planes y fortalecer la estrategia comercial de ConnectaTel.
