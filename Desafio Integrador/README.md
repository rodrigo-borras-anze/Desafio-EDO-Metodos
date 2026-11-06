# Desafío EDO: Fondo de Ahorro Comunitario

**Materia:** INF131 (Proyecto)
**Estudiante:** Rodrigo Borras Anze

## Descripción del Modelo
Este proyecto modela el crecimiento de un fondo de ahorro comunitario destinado a reparar el techo de una sede social. Utiliza una Ecuación Diferencial Ordinaria (EDO) lineal de primer orden para proyectar el capital acumulado en el tiempo.

*   **Variable dependiente:** $A(t)$ = Capital acumulado (Bolivianos).
*   **Variable independiente:** $t$ = Tiempo (meses).
*   **Ecuación Diferencial:** $dA/dt = rA + D$
    *   $r$ = Tasa de interés continua.
    *   $D$ = Depósito constante mensual.
*   **Condición Inicial:** $A(0) = A_0$ (Capital base al inicio).

## Instrucciones de Ejecución
La simulación está construida íntegramente en HTML y JavaScript, por lo que no requiere instalación de dependencias ni entornos de desarrollo.

1.  Descarga el archivo `index.html` de este repositorio o accede al enlace de la aplicación web publicada.
2.  Abre el archivo `index.html` con cualquier navegador web moderno (Chrome, Firefox, Edge).
3.  En la interfaz gráfica, ingresa los parámetros deseados (Capital inicial, tasa de interés, depósito mensual, tamaño de paso $h$ y meses de simulación).
4.  Haz clic en el botón **"Ejecutar Simulación Numérica"**.
5.  La aplicación generará automáticamente:
    *   Una gráfica comparativa (Solución Analítica, método de Heun, y RK4).
    *   Una tabla detallada con los valores e iteraciones.
    *   El cálculo del error relativo de cada método.
