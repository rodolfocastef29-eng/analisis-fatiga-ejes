# Software en Python para análisis de fatiga en ejes escalonados

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
    
# Objetivo

Desarrollar una herramienta computacional que permita realizar el análisis de
fatiga en ejes escalonados de forma rápida y precisa, evitando errores en la
lectura manual de gráficas y facilitando el estudio de diferentes condiciones
de carga.
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

El software utiliza **interpolación lineal** para obtener valores intermedios a partir de datos digitalizados de las gráficas del libro Shigley, J. E., Budynas, R. G., & Nisbett, J. K.
Mechanical Engineering Design.

Las interpolaciones implementadas son:

- Sensibilidad a la muesca (Figura 6-20 y 6-21)
- Factor de concentración de esfuerzos en flexión (Figura A-15-9)
- Factor de concentración de esfuerzos en torsión (Figura A-15-8)

Esto permite que el programa calcule automáticamente los valores sin necesidad de leer manualmente las gráficas. 

---

# Ejecución del programa

Para ejecutar el programa:

1. Clonar el repositorio
2. Abrir el archivo principal en Python
3. Ejecutar el código
4. Seleccionar las unidades de medida deseadas
5. 

El programa solicitará los datos de entrada y calculará automáticamente
los resultados del análisis de fatiga.

# Resultados

El software calcula los siguientes parámetros:

a) Sensibilidad a la muesca  
b) Factores de concentración de esfuerzo  
c) Factores de fatiga  
d) Esfuerzos en la sección crítica  
e) Esfuerzos equivalentes de Von Mises  
f) Esfuerzo máximo equivalente  
g) Factor de seguridad de Von Mises  
h) Factores de seguridad por criterios de fatiga

# Licencia

Este proyecto se distribuye con fines educativos.
