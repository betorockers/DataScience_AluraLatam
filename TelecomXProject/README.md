# 📊 Análisis de Evasión de Clientes - Telecom X

Este proyecto analiza el comportamiento de los clientes de la empresa **Telecom X** con el objetivo de identificar patrones y factores que influyen en su decisión de **evadir** (churn) los servicios contratados.

---

## 🧠 Objetivo

Detectar los principales factores asociados a la evasión de clientes y proponer recomendaciones basadas en los hallazgos obtenidos a través del análisis exploratorio de datos.

---

## 📁 Estructura del Proyecto

- `XtelecomProjects.ipynb`: Notebook principal con todo el análisis, visualizaciones y comentarios.
- `TelecomX_diccionario.md`: Diccionario que describe cada columna en español para saber como realizar de mejor manera el analisis y esta en formato Markdown.
- `TelecomX_data.json`: Dataset base (incluido).
- `README.md`: Este archivo.

---

## 🔧 Herramientas Utilizadas

- **Lenguaje**: Python 3.x
- **Entorno**: Jupyter Notebook
- **Librerías**:
  - `pandas` y `numpy` para manipulación de datos.
  - `matplotlib` y `seaborn` para visualización.

---

## 🧼 Proceso de Análisis

1. **Carga y exploración inicial del dataset.**
2. **Limpieza y transformación:**
   - Expansión de columnas anidadas.
   - Corrección de valores faltantes o inconsistentes.
   - Estandarización de nombres de columnas.
3. **Análisis descriptivo:**
   - Estadísticas generales de gasto, antigüedad y servicios.
4. **Visualización de evasión por:**
   - Género, servicios contratados, tipo de contrato y método de pago.
   - Variables numéricas como `total_facturado`, `factura_mensual` y `tiempo_contrato`.
5. **Insights y recomendaciones para la retención de clientes.**

---

## 📈 Resultados Clave

- **Clientes con contratos mensuales y menos servicios son más propensos a evadir.**
- **La variable `total_facturado` es un buen predictor de evasión: a menor gasto, mayor probabilidad de evasión.**
- **Clientes con menor tiempo de permanencia en la empresa tienden a cancelar más.**

---

## 💡 Recomendaciones

- Incentivar contratos de mayor duración con descuentos progresivos.
- Ofrecer paquetes con servicios combinados (internet + telefonía + multilínea).
- Detectar clientes con baja permanencia y alta factura mensual como casos críticos.

---

## 🧾 Informe Final

Consulta el informe detallado en el notebook interactivo [`XtelecomProjects.ipynb`](./XtelecomProjects.ipynb).

---

## 📬 Contacto

Proyecto desarrollado como ejercicio de análisis exploratorio para estudios en ciencia de datos.  
Para consultas: **Omar Betorock Toledo** - *omar.toledus@gmail.com

