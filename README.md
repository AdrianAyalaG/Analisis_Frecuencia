19 / 09 / 2024
# Análisis en Frecuencia y Diagramas de Bode
El análisis en frecuencia es un método utilizado para examinar cómo un sistema responde a señales sinusoidales de diferentes frecuencias. Su objetivo es comprender el comportamiento del sistema en el dominio de la frecuencia, en lugar de analizar su evolución en el tiempo [1].
El diagrama de Bode proporciona una visión clara del funcionamiento y comportamiento de un sistema físico, ofreciendo información clave sobre su estabilidad. Esto es fundamental para el diseño de controladores eficientes en los procesos pertinentes. Además, permite identificar las zonas óptimas de operación y destacar las áreas donde es necesario evitar dinámicas no deseadas. [2]



## 1. Analisis en Frecuencia
- Una forma de estudiar los sistemas dinámicos es observar cómo responde la salida cuando se varía la frecuencia en la entrada.
- La señal seno $$\( R = A \sin(\omega kT + \theta) \)$$ se aplica bajo el supuesto de que el sistema tiene un comportamiento lineal.
- No se deben realizar cambios en la frecuencia de entrada. Si ocurren perturbaciones, estas provocarán variaciones en la amplitud y fase de la señal de salida.
  
## ¿Qué cambios se pueden producir?
* Salida sinusoidal con amplitud proporcional.
* Armónicos igual frecuencia que a la entreda.
* Variaciones en amplitud y frecuencia.
* Ángulo de Fase y Amplitud, comportamiento a los cambios.

Para la representación matemática, las señales sinusoidales se expresan mediante fasores. Bajo la suposición de una frecuencia constante, los fasores describen la señal únicamente en términos de amplitud y fase. La entrada y salida se representa en fasores, representando el sistema como:

$$ R = A \sin(\omega kT + \theta)$$

La frecuencia constante e implicita

$$ R = A \measuredangle \varphi $$

# 💡Ejemplo

![Figura de prueba](Dom_Frec.png)

Figura 1. Dominio en frecuencia.


$$M_{o}$$, $$M_{i}$$ son magnitudes que estan representadas en el dominio de la frecuencia

Masa:

$$x_{(t)} = M_{o}Cos(\omega + \Theta_{0})$$
 

Entrada:

$$M_{i} \measuredangle_{i} \phi (\omega) $$

Salida:

$$M_{o} \measuredangle_{o} \phi (\omega) $$

La relación entre la entrada y la salida determina el sistema que transforma la señal de entrada, el cual se ve afectado por los cambios en la frecuencia.

$$\frac{M_{o} \measuredangle_{o} \phi (\omega)}{M_{i} \measuredangle_{i} \phi (\omega)} = M \measuredangle \phi(\omega) $$






---






 ---
 Dominio $$(s)$$ o $$(z)$$
 
 $$s = jw$$
 
 $$z = e^{sT}$$
 
 $$z = e^{jwT}$$
 
 En terminos de frecuencia

##  Diagramas de frecuencia
Trabaja distintos diagramas -> Analizando
 |----> Fase y amplitud 

- Depende del diagrama:
  Escala lineal
  Escala logaritmica
La mafgnitud y fase con respecto a la frecuencia

dB -> Se trabaja con Baudios (dB) -> Potencia o ganacia
Analizar rangos de frecuencia muy grandes

$$A_{dB} = 20log_{10}A$$
- Magnitud con respecto a la fase
- Coordenadas polares







##  Referencias
[1]. R. Hossain, “Control System By Norman nise Sixth Ed”, 2017.
[2]	S. A. Castaño Giraldo, “Diagrama de Bode”, Control Automático Educación, 05-oct-2019. [En línea]. Disponible en: https://controlautomaticoeducacion.com/control-realimentado/1-diagrama-de-bode/. [Consultado: 28-sep-2024].

