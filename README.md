# Software en Python para anlisis de fatiga en ejes escalonados
# Software de análisis de fatiga en ejes escalonados

Este proyecto consiste en el desarrollo de un software en Python para el análisis de fatiga en ejes escalonados utilizando los criterios del libro **Shigley - Mechanical Engineering Design**.

El programa permite calcular automáticamente:

- Sensibilidad a la muesca (q, q_cortante)
- Factores de concentración de esfuerzo (Kt, Kts)
- Factores de fatiga (Kf, Kfs)
- Esfuerzos normales y cortantes en la sección crítica
- Esfuerzos equivalentes de Von Mises
- Esfuerzo máximo equivalente
- Factor de seguridad de Von Mises
- Factores de diseño utilizando los criterios:
  - Goodman
  - Soderberg
  - Gerber
  - ASME Elíptico

---

# Autor

Nombre: Rodolfo Alberto Castellanos Franco  
Asignatura: Diseño de Elementos de Máquina  
Profesor: Rafael Valenzuela Rodríguez

---

# Lenguaje utilizado

Python 3

---

# Interpolación de Datos

El software utiliza **interpolación lineal** para obtener valores intermedios a partir de datos digitalizados de las gráficas del libro.

Las interpolaciones implementadas son:

- Sensibilidad a la muesca (Figura 6-20 y 6-21)
- Factor de concentración de esfuerzos en flexión (Figura A-15-9)
- Factor de concentración de esfuerzos en torsión (Figura A-15-8)

Esto permite que el programa calcule automáticamente los valores sin necesidad de leer manualmente las gráficas. 

---

# Ejecución del programa

Para ejecutar el programa:
