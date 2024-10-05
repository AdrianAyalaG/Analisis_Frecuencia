19 / 09 / 2024
# Analisis en Frecuencia y Diagramas de Bode
El análisis en frecuencia es un método utilizado para examinar cómo un sistema responde a señales sinusoidales de diferentes frecuencias. Su objetivo es comprender el comportamiento del sistema en el dominio de la frecuencia, en lugar de analizar su evolución en el tiempo [1].
El diagrama de Bode proporciona una visión clara del funcionamiento y comportamiento de un sistema físico, ofreciendo información clave sobre su estabilidad. Esto es fundamental para el diseño de controladores eficientes en los procesos pertinentes. Además, permite identificar las zonas óptimas de operación y destacar las áreas donde es necesario evitar dinámicas no deseadas. [2]




## 1. Analisis en Frecuencia
- Una forma de estudiar los sistemas dinámicos es observar cómo responde la salida cuando se varía la frecuencia en la entrada.
- La señal seno \( R = A \sin(\omega kT + \theta) \) se aplica bajo el supuesto de que el sistema tiene un comportamiento lineal.
- No tener cambios en la frecuencia
-----
## Cambios
* Salida sinusoidal con amplitud proporcional
* Armonicos igual frecuencia que a la entreda
* Variaciones en amplitud y frecuencia
* Angulo de Fase y Amplitud -> Comportamiento a los cambios

-> Señal sinusoidal -> Representación en fasores -> Frecuencia constante y solamente representa la señal en términos de amplitud y fase.

---
Masa:
 $$x_{(t)} = M_{o}Cos(\omega + \Theta_{0})$$

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
[2]	S. A. Castaño Giraldo, “Diagrama de Bode”, Control Automático Educación, 05-oct-2019. [En línea]. Disponible en: https://controlautomaticoeducacion.com/control-realimentado/1-diagrama-de-bode/. [Consultado: 05-oct-2024].

