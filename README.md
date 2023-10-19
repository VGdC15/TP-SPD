# TP-SPD
Repositorio con los primeros tres trabajos prácticos de electrónica con Arduino. Material de estudio para el próximo examen. Incluye códigos y esquemas.



# :computer: Parcial domiciliario parte 1
![parcial parte 1](https://github.com/VGdC15/TP-SPD/assets/113645765/e7d6d22f-b325-4864-9c15-7ac781413378)

# Descripción
Diseño de un contador de 0 a 99 utilizando dos displays de 7 segmentos y tres botones para controlar la cuenta. 
Se implemento la técnica de multiplexación para mostrar los dígitos en los displays. 

# :books: Concepto de Multiplexación
La multiplexación es una técnica utilizada en electrónica y telecomunicaciones que implica la combinación de múltiples señales en un único medio de transmisión o dispositivo. 
En el contexto de la electrónica digital, la multiplexación se refiere a la técnica de compartir un único recurso entre varios componentes o canales de entrada/salida. 

En el caso de pantallas de visualización de dígitos, como en los displays de 7 segmentos utilizados en el código proporcionado, la multiplexación se utiliza para controlar varios dígitos en una pantalla utilizando un número mínimo de pines. En lugar de tener un pin para cada segmento de cada dígito en la pantalla, la multiplexación permite alternar rápidamente entre los diferentes dígitos, creando la ilusión de que todos los dígitos están activos al mismo tiempo.

En el código proporcionado, la multiplexación se realiza alternando entre la visualización de los dígitos de las unidades y de las decenas en el display de 7 segmentos. 
Esto se logra controlando los pines de cada dígito y cada segmento de forma secuencial y con una frecuencia suficientemente alta para que el ojo humano perciba que todos los dígitos están encendidos al mismo tiempo. De esta manera, se logra mostrar un número de dos dígitos en un solo display utilizando únicamente dos pines para controlar los segmentos y dos pines adicionales para controlar los dígitos.

# :sparkler: Enlace al proyecto de Tinkercard
<https://www.tinkercad.com/things/gKMpLNjDH0g>


# :computer: Parcial domiciliario parte 2
![parcial parte 2](https://github.com/VGdC15/TP-SPD/assets/113645765/912a4fd1-83e7-45c6-aff9-83262130a2a2)

# Descripción
Se sustituyen los botones por un interruptor deslizante (switch) de dos posiciones.
Dependiendo de la posición del interruptor, el display muestra o bien el contador (como
en la Parte 1) o los números primos en el rango de 0 a 99.

# :books: Investigación de componente adicional
Un motor de aficionado, o un ventilador, en el contexto de Arduino se refiere a un motor eléctrico simple que se utiliza para generar flujo de aire o para crear una corriente de aire dirigida. En el proyecto proporcionado, el motor aficionado se utiliza para controlar la temperatura de un entorno. Cuando la temperatura medida por el sensor supera un umbral específico (40 grados Celsius en este caso), el motor se enciende para enfriar el ambiente.

El ventilador actúa como un componente de control de temperatura, ayudando a mantener la temperatura del entorno por debajo de un cierto nivel. Cuando la temperatura excede el umbral establecido, el motor del ventilador se activa para reducir la temperatura. Esto se logra mediante la conexión del motor aficionado a uno de los pines de salida de Arduino, permitiendo que el código encienda y apague el motor según las condiciones especificadas. De esta manera, el ventilador se convierte en un dispositivo esencial para controlar el entorno térmico de manera automática y eficiente.

# :sparkler: Enlace al proyecto de Tinkercard
<https://www.tinkercad.com/things/fnFg3GUNil5>



# :computer: Parcial domiciliario parte 3
![parcial parte 3](https://github.com/VGdC15/TP-SPD/assets/113645765/04b7a855-f723-49c9-8bef-5cf6f092cf82)

# Descripción
Se grega un componente adicional que afecta el funcionamiento del proyecto.
El elemento implementado es una fotoresistencia

# :books:  Investigación de componente adicional
Una fotoresistencia, también conocida como LDR (del inglés Light Dependent Resistor) es un componente electrónico cuya resistencia varía en función de la intensidad de luz que recibe. Bajo una iluminación intensa, la resistencia disminuye, mientras que en la oscuridad su resistencia aumenta. Es un tipo de sensor muy común y se utiliza para detectar la intensidad lumínica en su entorno.

En este proyecto, la fotoresistencia está conectada al pin A0. Se utiliza para medir la intensidad de luz ambiental. La lectura de la fotoresistencia se mapea a un valor de brillo para el LED rojo conectado al pin 5. Esto significa que el brillo del LED rojo variará en función de la cantidad de luz presente en el entorno. Si la temperatura supera el umbral definido, el LED rojo se encenderá con una intensidad que dependerá de la lectura de la fotoresistencia, lo que puede proporcionar una indicación visual de la intensidad de luz en condiciones de alta temperatura.

En resumen, la fotoresistencia se utiliza en este proyecto para regular la intensidad del LED rojo en función de la luz ambiente y la temperatura medida. Esto puede resultar útil en diversas aplicaciones, como sistemas de control ambiental o sistemas de monitoreo que requieren una retroalimentación visual basada en la intensidad lumínica y la temperatura.

# :sparkler: Enlace al proyecto de Tinkercard
<https://www.tinkercad.com/things/gFWkpXJAQOI>



