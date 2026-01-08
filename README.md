# Análisis de Rentabilidad de Tarifas Prepago en Megaline

## 📌 Descripción del proyecto
Este proyecto analiza el comportamiento de los clientes de Megaline, un operador de telecomunicaciones, con el objetivo de determinar cuál de sus dos tarifas de prepago (Surf y Ultimate) genera mayores ingresos en promedio.  
El análisis se basa en datos reales de uso de llamadas, mensajes de texto e internet durante el año 2018, e incluye pruebas estadísticas para validar las conclusiones.

---

## 🎯 Objetivos
- Analizar el consumo mensual de minutos, SMS y datos de los clientes.
- Calcular los ingresos mensuales por usuario según su tarifa.
- Comparar la rentabilidad promedio de los planes Surf y Ultimate.
- Evaluar diferencias de ingresos entre regiones mediante pruebas de hipótesis.
- Proporcionar conclusiones basadas en datos para apoyar decisiones de negocio.

---

## 🗂️ Descripción de los datos
El proyecto utiliza cinco tablas principales:

- **users**: información demográfica y plan contratado por el usuario.
- **calls**: registros de llamadas y duración.
- **messages**: registros de mensajes de texto enviados.
- **internet**: uso de datos móviles por sesión.
- **plans**: detalles y costos de cada tarifa.

### Columnas clave
- `user_id`, `plan`, `city`, `age`
- `call_date`, `duration`
- `message_date`
- `mb_used`, `session_date`
- `usd_monthly_fee`, `minutes_included`, `messages_included`, `mb_per_month_included`

---

## 🧪 Metodología

1. **Exploración inicial**
   - Revisión de estructura, tipos de datos y valores ausentes.

2. **Preparación de datos**
   - Conversión de tipos de datos.
   - Corrección de errores y valores inconsistentes.
   - Cálculo mensual por usuario de:
     - Minutos utilizados
     - SMS enviados
     - Volumen de datos consumidos
     - Ingresos generados

3. **Análisis exploratorio**
   - Análisis del consumo mensual por tipo de tarifa.
   - Cálculo de media, varianza y desviación estándar.
   - Visualización de distribuciones mediante histogramas.

4. **Pruebas de hipótesis**
   - Comparación del ingreso promedio entre planes Surf y Ultimate.
   - Comparación del ingreso promedio entre usuarios de Nueva York–Nueva Jersey y otras regiones.
   - Definición de hipótesis nula y alternativa.
   - Selección y justificación del nivel de significancia (α).

---

## 🛠️ Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

## 📊 Resultados y conclusiones
El análisis permite identificar diferencias claras en el comportamiento de consumo y en los ingresos generados por cada tarifa.  
Las pruebas estadísticas respaldan las conclusiones, proporcionando evidencia sólida para apoyar decisiones estratégicas del área comercial y de marketing.

---

## 📁 Estructura del repositorio

├── notebooks/

│ └── analisis_tarifas_megaline.ipynb

├── datasets/

│ ├── megaline_calls.csv

│ ├── megaline_internet.csv

│ ├── megaline_messages.csv

│ ├── megaline_plans.csv

│ └── megaline_users.csv

├── README.md

---

## 👤 Autor
**Carlos Jaramillo**  
Analista de Datos