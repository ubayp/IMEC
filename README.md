#  IMEC (Intermediate Macroeconomic Excercises Calculator)

Una herramienta dinámica diseñada para el análisis y la simulación numérico del equilibrio macroeconómico y el mecanismo de transmisión de shocks fiscales y monetarios los modelos IS-LM y Mundell-Flemming con movilidad perfecta de capitales STANDARD. Ideal para la práctica y comprensión profunda de la materia.

##  Características Principales

* **Cálculo de Equilibrio Base:** Determina la Renta ($Y_e$) y el Tipo de Interés ($r_e$) iniciales.
* **Simulación de Shocks:** Permite modificar un único parámetro (autónomo, estructural o de política) para observar el nuevo equilibrio.
* **Mecanismo de Transmisión:** Proporciona un **análisis textual y secuencial (paso a paso)** del efecto causal del shock (ej: $G \uparrow \Rightarrow Y \uparrow \Rightarrow L_y \uparrow \Rightarrow r \uparrow \dots$).
* **Análisis de Política:** Calcula el ajuste necesario en una variable clave ($G_0, M/P, \dots$) para lograr los saldos objetivo (SSP = 0 o NX = 0).

##  Guía de Uso Rápida

1.  **Establecer Parámetros (Sección 1):** Introduzca los valores de los coeficientes y variables autónomas para definir la economía base.
2.  **Recalcular Equilibrio Base:** Pulse el botón para confirmar los valores iniciales de $Y_e$ y $r_e$.
3.  **Simular un Shock (Sección 3):** En los campos de "Simulación de Shocks", **solo modifique el valor de la variable que desea cambiar**. Los campos vacíos mantienen el valor base.
4.  **Analizar el Resultado (Sección 4 & 5):**
    * Compare el **% de cambio** en $Y$ y $r$.
    * Lea el análisis de **Mecanismo de Transmisión** para entender el proceso IS-LM.

##  Estructura y Mantenimiento

Este proyecto es un archivo único HTML, CSS y JavaScript.

* **Lenguajes:** HTML5, JavaScript.
* **Estilos:** [Tailwind CSS CDN](https://cdn.tailwindcss.com) (integrado en el HTML).
* **Función Clave:** `getSingleShockMechanism()` genera la explicación secuencial, clave para el valor educativo de la herramienta.

##  Integración con Moodle

La herramienta está diseñada para su uso directo en la plataforma educativa.

1.  En Moodle, cree una actividad **URL**.
2.  Pegue la URL pública del hosting.
3.  En **Apariencia**, seleccione **Incrustar (Embed)** para cargar la calculadora dentro de un *iframe* y controlar el acceso de los alumnos.

---
**Autor:** [Ubay Pérez Granja]
**Uso de IA:** Esta aplicación ha sido creada usando vibecoding en Gemini 2.5 Flash y ChatGPT5
**Versión:** 1.1 (Noviembre 2025)
