# TP-SPD
Repositorio con los primeros tres trabajos prácticos de electrónica con Arduino. Material de estudio para el próximo examen. Incluye códigos y esquemas.



# Parcial domiciliario parte 1
Diseño de un contador de 0 a 99 utilizando dos displays de 7 segmentos y tres botones para controlar la cuenta. 
Se implemento la técnica de multiplexación para mostrar los dígitos en los displays. 

![parcial parte 1](https://github.com/VGdC15/TP-SPD/assets/113645765/e7d6d22f-b325-4864-9c15-7ac781413378)

# Enlace al proyecto de Tinkercard
<https://www.tinkercad.com/things/gKMpLNjDH0g>



# Parcial domiciliario parte 2
Se sustituyen los botones por un interruptor deslizante (switch) de dos posiciones.
Dependiendo de la posición del interruptor, el display muestra o bien el contador (como
en la Parte 1) o los números primos en el rango de 0 a 99.

![parcial parte 2](https://github.com/VGdC15/TP-SPD/assets/113645765/912a4fd1-83e7-45c6-aff9-83262130a2a2)

# Investigación de componente adicional
-Motor de cc
Un motor de corriente continua (CC) es un dispositivo que convierte la energía eléctrica en energía mecánica. Se compone de un estator y un rotor y opera según el principio de la ley de Lorentz, que establece que un conductor que transporta corriente en presencia de un campo magnético experimenta una fuerza. Esta fuerza hace que el rotor gire, lo que a su vez produce movimiento mecánico.
Funcionamiento:

Los motores de corriente continua funcionan con una corriente que fluye en una dirección específica a través de un conjunto de bobinas, generando un campo magnético. La interacción entre este campo magnético y un campo magnético fijo en el estator produce un par motor que impulsa el movimiento del rotor.

# Enlace al proyecto de Tinkercard
<https://www.tinkercad.com/things/fnFg3GUNil5>



# Parcial domiciliario parte 3
Se grega un componente adicional que afecta el funcionamiento del proyecto.
El elemento implementado es una fotoresistencia

![parcial parte 3](https://github.com/VGdC15/TP-SPD/assets/113645765/04b7a855-f723-49c9-8bef-5cf6f092cf82)

# Investigación de componente adicional
Una fotoresistencia, también conocida como LDR (del inglés Light Dependent Resistor) es un componente electrónico cuya resistencia varía en función de la intensidad de luz que recibe. Bajo una iluminación intensa, la resistencia disminuye, mientras que en la oscuridad su resistencia aumenta. Es un tipo de sensor muy común y se utiliza para detectar la intensidad lumínica en su entorno.

En este proyecto, la fotoresistencia está conectada al pin A0. Se utiliza para medir la intensidad de luz ambiental. La lectura de la fotoresistencia se mapea a un valor de brillo para el LED rojo conectado al pin 5. Esto significa que el brillo del LED rojo variará en función de la cantidad de luz presente en el entorno. Si la temperatura supera el umbral definido, el LED rojo se encenderá con una intensidad que dependerá de la lectura de la fotoresistencia, lo que puede proporcionar una indicación visual de la intensidad de luz en condiciones de alta temperatura.

En resumen, la fotoresistencia se utiliza en este proyecto para regular la intensidad del LED rojo en función de la luz ambiente y la temperatura medida. Esto puede resultar útil en diversas aplicaciones, como sistemas de control ambiental o sistemas de monitoreo que requieren una retroalimentación visual basada en la intensidad lumínica y la temperatura.

# Enlace al proyecto de Tinkercard
<https://www.tinkercad.com/things/gFWkpXJAQOI>



