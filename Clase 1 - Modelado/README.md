# Mecatrónica - Universidad de Málaga 🎓

Este repositorio contiene las prácticas y ejercicios de modelado de sistemas.

## Ejercicio 2.2: Modelado de un Condensador Electrolítico
[cite_start]Este ejercicio consiste en modelar el comportamiento de un condensador empleado en el flash de una cámara fotográfica[cite: 6, 15].

### 1. Descripción del Modelo
[cite_start]El condensador se modela considerando su capacitancia $C$ y una resistencia de fuga $R_1$ en paralelo, que representa la pérdida interna de tensión en circuito abierto[cite: 17].


**Parámetros:**
* [cite_start]**Capacitancia ($C$):** $120 \mu F$ [cite: 31]
* [cite_start]**Resistencia de fuga ($R_1$):** $1 M\Omega$ [cite: 31]

### 2. Ecuaciones Diferenciales
[cite_start]Para el sistema que incluye la batería ($V_{oc}$) y el condensador ($V_c$), la ecuación que describe su comportamiento es:

$$C \frac{dV_c}{dt} + \frac{V_c}{R_1} = i(t)$$

### 3. Resultados de Simulación (Simscape)
* **Descarga al aire:** El tiempo para bajar de $1.5V$ a $1V$ es de **48.5 segundos**[cite: 31, 46].
* [cite_start]**Carga con batería:** El condensador alcanza $1V$ en tan solo **0.035 ms**[cite: 47].
* [cite_start]**Flash de la cámara:** Con una lámpara de $R_f = 0.1 \Omega$ y $L_f = 0.01 mH$, el tiempo de encendido es de **0.04 ms**[cite: 38, 48].