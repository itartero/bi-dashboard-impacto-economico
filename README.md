# 📊 Dashboard de Inteligencia de Negocio: Impacto Económico y Eficiencia Operativa (Circular Getafe)

![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/BI-Data_Storytelling-orange?style=for-the-badge)

Este proyecto consiste en el diseño, desarrollo e implementación de un sistema centralizado de Business Intelligence (BI) para el Taller Regional de Circularidad de Getafe. A través de cuadros de mando interactivos construidos en Looker Studio, este sistema transforma datos brutos operativos en insights estratégicos, permitiendo monitorizar tanto el impacto económico del modelo de economía circular como el rendimiento técnico del equipo.

---

## 🎯 Objetivos del Proyecto

1. **Cuantificar el Impacto Económico:** Medir en tiempo real el valor económico recuperado mediante el reacondicionamiento técnico de maquinaria y productos de segunda vida.
2. **Optimizar la Capacidad Operativa:** Monitorizar las desviaciones entre los Tiempos Teóricos (TT) de reparación y los tiempos reales para maximizar la productividad.
3. **Control de Empleabilidad:** Visualizar los niveles de ocupación, eficiencia y disponibilidad del personal técnico para una asignación óptima de recursos.

---

## 🛠️ Stack Tecnológico y Flujo de Datos (ETL)

El proyecto implementa un flujo de datos limpio y automatizado enfocado en la integridad del dato:
* **Origen de Datos:** Conexión directa al ecosistema transaccional de AppSheet e ingesta desde hojas de cálculo estructuradas.
* **Procesamiento e Integración (ETL):** Limpieza, tipado y transformación de datos brutos utilizando lógicas de agregación de datos para unificar variables temporales y económicas.
* **Visualización (Front-end):** Despliegue de dashboards analíticos interactivos mediante **Looker Studio** y **Tableau**.

---

## 📊 Arquitectura del Cuadro de Mando (Estructura de Vistas)

El dashboard está diseñado bajo principios de *Data Storytelling*, permitiendo una navegación intuitiva desde métricas ejecutivas macro hasta detalles operativos micro:

### 1. Vista Ejecutiva: Impacto Económico
* **Métricas Core:** Valor total de productos reacondicionados puestos a la venta (€), tasa de circularidad global e ingresos generados por los servicios del taller.
* **Análisis de Origen:** Desglose del impacto económico clasificado por la tienda de origen (transferencias al taller regional), facilitando la consultoría técnica a los puntos de venta.

### 2. Vista Operativa: Tiempos Teóricos (TT) y Eficiencia
* **Análisis de Desviaciones:** Gráficos analíticos que comparan de forma dinámica el Tiempo Teórico estandarizado de reparación frente al tiempo real invertido por categoría de producto (Ciclismo, Nutrición, Electrónica, etc.).
* **Detección de Cuellos de Botella:** Alertas visuales para identificar retrasos en el flujo de trabajo debido a la fase de "Espera de Piezas".

### 3. Vista de Recursos Humanos: Matriz de Empleabilidad
* Monitorización en tiempo real de los niveles de actividad y saturación de los colaboradores del taller.
* Análisis de tendencias mensuales de capacidad técnica para anticipar necesidades de personal en picos de demanda estacional.

---

## 📸 Capturas del Dashboard e Insights Visuales

*(Nota: Los datos y gráficos presentados a continuación han sido anonimizados, ofuscados o modificados con datos ficticios para cumplir con las políticas de confidencialidad de la organización).*

### Panel de Control de Impacto Económico (€)
> <img width="1083" height="810" alt="image" src="https://github.com/user-attachments/assets/9aab722c-63f7-4270-9029-650d423546a6" />
*Gráficos de barras y KPIs acumulados que muestran el valor recuperado por el taller regional.*

--

## 🚀 Conclusión y Valor de Negocio
Este sistema de Business Intelligence ha sustituido la gestión intuitiva por una **cultura dirigida por datos (Data-Driven)** en el taller de circularidad. Al dar visibilidad clara al impacto financiero y a la eficiencia del equipo, la estrategía ha optimizado la toma de decisiones, validando el retorno de inversión del modelo circular de Decathlon.
