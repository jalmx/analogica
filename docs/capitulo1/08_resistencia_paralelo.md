# Resistencias en conexión Paralelo

Cuando dos o más resistencias se conectan individualmente entre dos puntos distintos, están en paralelo entre sí.

![conexion paralelo](../assets/Antologia.pdf-178.opt.png)

> Si existe más de una trayectoria (rama) para la corriente entre dos puntos distintos, y si el voltaje entre dichos puntos también aparece a través de cada una de las ramas, entonces existe un circuito en paralelo entre esos dos puntos.

**==Las resistencias en paralelo es la suma de sus inversos en un inverso==**, es decir; se realiza la suma del inverso de todas las resistencias y una vez se tenga, a esa suma total se aplica un inverso.

![paralelo](../assets/Antologia.pdf-184.opt.png)

Como se muestra en la imagen, tenemos 3 resistencias, en los extremos tenemos conectado un lado de R1, R2 y R3, y por el otro lado igual, en estos extremos se lee su valor total; es decir:

$$R_T= \frac{1}{\frac{1}{R_1}+ \frac{1}{R_2} + \frac{1}{R_3}} = \frac{1}{\frac{1}{100 \Omega}+ \frac{1}{47 \Omega} + \frac{1}{22\Omega}}$$

$$R_T=13.03 \Omega$$

Este valor de resistencia también se conoce como **resistencia equivalente o total.**

**La fórmula para la resistencia equivalente en paralelo es:**

> $$R_T= \frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_3}+\frac{1}{R_4}+ ... + \frac{1}{R_n}}$$

Aplicaremos esta fórmula en los circuitos que se muestran:

![paralelo](../assets/Antologia.pdf-194.opt.png)

$$R_T= \frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_3}+\frac{1}{R_4}} = \frac{1}{\frac{1}{1k\Omega}+\frac{1}{1k\Omega}+\frac{1}{1k\Omega}+\frac{1}{1k\Omega}}$$

$$R_T = 250 \Omega$$

El circuito equivalente seria:

![equivalente](../assets/Antologia.pdf-202.opt.png)

!!! Tip
    Siempre el valor de la resistencia total en paralelo debe ser mucho menor que la resistencia más pequeña en el circuito.


## Ejemplos

!!! example Ejercicio
    **1. Obtener la resistencia total del siguiente circuito** <br>
    **Diagrama** <br>
    ![diagrama](../assets/Antologia.pdf-207.opt.png) <br>
    **Calculo:** <br>
    $$R_T= \frac{1}{\frac{1}{R_1}+ \frac{1}{R_2} } = \frac{1}{\frac{1}{100 \Omega}+ \frac{1}{470 \Omega}}$$
    $$R_T=82.45 \Omega$$

!!! example Ejercicio
    **2. Obtener la resistencia total del siguiente circuito** <br>
    **Diagrama** <br>
    ![diagrama](../assets/Antologia.pdf-211.opt.png) <br>
    **Calculo:** <br>

!!! example Ejercicio
    **3. Obtener la resistencia total del siguiente circuito** <br>
    **Diagrama** <br>
    ![diagrama](../assets/Antologia.pdf-212.opt.png) <br>
    **Calculo:** <br>

## Ejercicios

!!! example Ejercicio
    **1. Obtener la resistencia total del siguiente circuito** <br>
    **Diagrama** <br>
    ![diagrama](../assets/Antologia.pdf-213.opt.png) <br>
    **Calculo:** <br>

!!! example Ejercicio
    **2. Obtener la resistencia total del siguiente circuito** <br>
    **Diagrama** <br>
    ![diagrama](../assets/Antologia.pdf-214.opt.png) <br>
    **Calculo:** <br>
