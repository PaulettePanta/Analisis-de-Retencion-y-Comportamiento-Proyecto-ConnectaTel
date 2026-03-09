# Analisis-de-Retencion-y-Comportamiento-Proyecto-ConnectaTel
🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es analizar el comportamiento de los usuarios de la empresa de telecomunicaciones ConnectaTel. A través del procesamiento y limpieza de datos, buscamos segmentar a los clientes por edad y nivel de uso para identificar patrones de consumo (llamadas y mensajes) que permitan a la gerencia tomar decisiones estratégicas sobre la oferta de planes y retención de clientes.

📊 Datasets Utilizados
El análisis se basa en la integración de dos fuentes de datos principales:

users.csv: Información demográfica de los usuarios (ID, nombre, edad, ciudad, fecha de registro y tipo de plan).

usage.csv: Registros detallados de consumo (mensajes enviados y duración de llamadas por usuario).

🛠️ Etapas del Análisis
El proyecto se desarrolló siguiendo un flujo de trabajo de ciencia de datos profesional:

Carga y Exploración: Importación de datos y primera inspección de estructuras.

Limpieza de Datos:

Tratamiento de valores sentinel (como -999 en edad y ? en ciudad).

Conversión de tipos de datos (fechas y variables numéricas).

Manejo de valores nulos e inconsistencias temporales.

Análisis Estadístico: Cálculo de medidas de tendencia central y dispersión.

Identificación de Outliers: Uso de Boxplots y método IQR para detectar usuarios con consumo extremo.

Segmentación: Creación de categorías de usuarios basadas en Edad (Joven, Adulto, Adulto Mayor) y Nivel de Uso (Bajo, Medio, Alto).

Visualización: Generación de histogramas y gráficos de barras para comunicar hallazgos
