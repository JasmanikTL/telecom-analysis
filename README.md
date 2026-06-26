# 📊 Proyecto 6 – Análisis de una empresa de telecomunicaciones (ConnectaTel)

## Descripción

Este proyecto desarrolla un análisis exploratorio de datos (EDA) sobre el comportamiento de los clientes de **ConnectaTel**, una empresa de telecomunicaciones con operaciones en Latinoamérica.

A partir de información sobre planes, clientes y registros de uso de llamadas y mensajes, se realizó un proceso completo de exploración, limpieza, análisis estadístico, visualización y segmentación de clientes con el propósito de identificar patrones de consumo, detectar valores atípicos y generar recomendaciones que apoyen la toma de decisiones del negocio.

---

# 🎯 Objetivo del proyecto

Analizar el comportamiento de los clientes de ConnectaTel mediante técnicas de análisis exploratorio de datos para:

- Identificar patrones de uso de llamadas y mensajes.
- Detectar problemas de calidad en los datos.
- Encontrar valores atípicos (outliers).
- Segmentar a los clientes según su nivel de uso y grupo de edad.
- Generar recomendaciones comerciales basadas en los resultados obtenidos.

---

# 📁 Datasets utilizados

El proyecto utiliza tres conjuntos de datos:

| Dataset | Descripción |
|----------|-------------|
| **plans.csv** | Información de los planes disponibles, incluyendo precio mensual, minutos, mensajes y GB incluidos. |
| **users_latam.csv** | Información de los clientes, como edad, ciudad, fecha de registro, plan contratado y fecha de cancelación. |
| **usage.csv** | Registros históricos del uso de llamadas y mensajes de cada usuario. |

---

# 🛠️ Herramientas utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📈 Etapas del análisis

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Carga y exploración de los datasets.
2. Identificación de problemas de calidad de los datos.
3. Limpieza de datos y tratamiento de valores inválidos.
4. Análisis estadístico descriptivo.
5. Visualización de distribuciones y detección de valores atípicos mediante Boxplots.
6. Segmentación de clientes por:
   - Nivel de uso.
   - Grupo de edad.
7. Elaboración de insights ejecutivos y recomendaciones para el negocio.

---

# 📌 Principales resultados

- Se identificaron valores inválidos en la variable **edad**, ciudades desconocidas y fechas fuera del periodo de análisis.
- Los valores nulos en las variables **duration** y **length** corresponden al tipo de actividad (llamada o mensaje), por lo que representan el comportamiento esperado del dataset.
- La mayoría de los clientes pertenece al segmento de **Uso medio**.
- El grupo de edad predominante corresponde a los **Adultos (30–59 años)**.
- Las variables relacionadas con el consumo presentan distribuciones sesgadas hacia la derecha y algunos valores atípicos, los cuales representan usuarios con consumos elevados y fueron conservados para el análisis.

---

# 💡 Recomendaciones

- Diseñar planes específicos para usuarios con alto consumo de llamadas y mensajes.
- Crear promociones dirigidas a usuarios con bajo nivel de uso para incentivar un mayor consumo.
- Mantener una oferta competitiva para los usuarios de uso medio, ya que representan la mayor parte de la base de clientes.
- Aprovechar la segmentación por edad para desarrollar campañas comerciales dirigidas principalmente al segmento de adultos.

---

# 📂 Estructura del proyecto

```text
telecom-analysis/
│
├── README.md
├── sprint7-final-project.ipynb
└── datasets/
    ├── plans.csv
    ├── users_latam.csv
    └── usage.csv
```

---

# ▶️ Cómo ejecutar el proyecto

## Opción 1: Jupyter Notebook

1. Clonar el repositorio:

```bash
git clone https://github.com/JasmanikTL/telecom-analysis.git
```

2. Entrar al proyecto:

```bash
cd telecom-analysis
```

3. Instalar las dependencias:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Abrir el notebook:

```bash
jupyter notebook
```

5. Ejecutar todas las celdas en orden.

---

## Opción 2: Google Colab

1. Descargar el repositorio o clonarlo desde GitHub.
2. Subir el notebook a Google Colab.
3. Subir la carpeta **datasets** al entorno de Colab.
4. Verificar que las rutas de lectura de los archivos correspondan a la ubicación de los datasets.
5. Ejecutar todas las celdas del notebook.

---

# 🔄 Guía de reproducción

Para reproducir correctamente el análisis:

1. Mantener la estructura de carpetas mostrada anteriormente.
2. Verificar que los archivos **plans.csv**, **users_latam.csv** y **usage.csv** se encuentren dentro de la carpeta **datasets**.
3. Ejecutar el notebook desde la primera hasta la última celda sin omitir pasos.

---

# 👤 Autor

**Jasmanik**

Estudiante del programa de **Análisis de datos de TripleTen**.

GitHub: https://github.com/JasmanikTL
