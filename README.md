# Proyecto 6 – Análisis de una empresa de telecomunicaciones (ConnectaTel)

## Descripción

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en Latinoamérica. A partir de información de usuarios, planes y registros de uso de llamadas y mensajes, se realizó un proceso completo de exploración, limpieza, análisis estadístico y segmentación de clientes para identificar patrones de consumo y generar recomendaciones para el negocio.

---

## Objetivos

- Explorar la estructura y calidad de los datos.
- Detectar y corregir valores inválidos, sentinels y fechas fuera de rango.
- Analizar el comportamiento de uso de llamadas y mensajes por usuario.
- Identificar valores atípicos mediante el método IQR.
- Segmentar a los clientes por nivel de uso y grupo de edad.
- Generar visualizaciones e insights para apoyar la toma de decisiones.

---

## Datasets utilizados

- **plans.csv:** Información de los planes disponibles (precio, minutos, mensajes y GB incluidos).
- **users_latam.csv:** Información de los clientes (edad, ciudad, fecha de registro, plan contratado y fecha de cancelación).
- **usage.csv:** Registros históricos de llamadas y mensajes realizados por los usuarios.

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Principales hallazgos

- Se detectaron valores inválidos en la edad (`-999`), ciudades desconocidas (`?`) y fechas de registro fuera del periodo de estudio.
- Los valores nulos en llamadas y mensajes dependen del tipo de actividad, por lo que corresponden al comportamiento esperado del dataset.
- La mayoría de los clientes pertenece al grupo de **Uso medio**.
- El grupo de edad predominante corresponde a **Adultos (30–59 años)**.
- Las variables de consumo presentan distribuciones sesgadas hacia la derecha y algunos valores atípicos, los cuales representan comportamientos reales de usuarios y se conservaron para el análisis.

---

## Recomendaciones

- Diseñar planes específicos para usuarios de alto consumo.
- Crear promociones dirigidas a usuarios de bajo uso para incrementar su actividad.
- Mantener una oferta competitiva para el segmento de uso medio, que representa la mayor parte de la cartera de clientes.
- Utilizar la segmentación por edad para desarrollar campañas comerciales más focalizadas.

---

## Estructura del repositorio

```
Proyecto6_ConnectaTel/
│
├── Proyecto6_ConnectaTel.ipynb
├── README.md
└── datasets/
    ├── plans.csv
    ├── users_latam.csv
    └── usage.csv
```

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio.
2. Instalar las dependencias:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Abrir el notebook en Jupyter Notebook o Google Colab.
4. Ejecutar todas las celdas en orden.

---

## Autor

Jasmanik
Doctorado en Robótica – Universidad Tecnológica de la Mixteca
