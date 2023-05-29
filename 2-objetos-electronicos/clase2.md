# clase 2

Sensores y actuadores

Miercoles 17 mayo 2023

Hoy aprenderemos:

- Señales analógicas y digitales
- Modulación por ancho de pulsos (PWM)
- Componentes eléctricos, sensores y actuadores
- Sensores de luz, sonido y proximidad
- Programación en Arduino: Condicionales, mapeo de valores

## enlaces a ejemplos de esta clase

- [ejemplos/ej_03_rgb_digital/](./ejemplos/ej_03_rgb_digital/)
- [ejemplos/ej_04_rgb_analogico/](./ejemplos/ej_04_rgb_analogico/)

## datos digitales y analógicos

Datos digitales: valores de 1 o 0, dígito binario o bit (2 posibles valores)

Datos analógicos: rangos variables, Arduino procesa datos de 0 a 1023 (2^10)

## modulación por ancho de pulsos (PWM ~)

Permite variar tiempo de una señal digital con estado alto o bajo (5V o 0V) para controlar la cantidad de corriente que se entrega a los dispositivos, emulando una señal analógica.

<img src="media/pwm.jpg" width="700">

## ejercicio 3: LED RGB y entrada digital (sensor de luz LDR)

<img src="media/ej_03_rgb_digital_ldr.jpg" width="500">

[ejemplos/ej_03_rgb_digital/](./ejemplos/ej_03_rgb_digital/)


## ejercicio 4: LED RGB y entrada analógica (sensor de sonido)

<img src="media/ej_04_rgb_analogico_sonido.jpg" width="500">

[ejemplos/ej_04_rgb_analogico/](./ejemplos/ej_04_rgb_analogico/)
