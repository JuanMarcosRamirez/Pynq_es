# Pynq_es: tutorial para el uso del entorno de productividad Pynq (Pynq-Z2)

## Hardware requerido

* La placa Zynq-Z2
* Ordenador con un navegador compatible (Chrome, Firefox)
* Cable de Ethernet
* Cable de Micro USB
* Memoria Micro SD con la distribución de Linux precargada

## Configuración de la placa

En la imagen mostrada a continuación, se puede observar una representación del kit de desarrollo Zynq-Z2 con indicadores de los elementos de hardware necesarios para trabajar con el entorno de productividad Pynq.

![Demo image](https://github.com/JuanMarcosRamirez/Pynq_es/blob/main/images/pynqz2_setup.png?raw=true "Board setting")

1. Configure el jumper de arranque (*Boot*) en la posición SD. Esta selección le permitirá arrancar la tarjeta desde la memoria Micro SD. La tarjeta trae una memoria Micro SD con una distribución de Ubuntu pre-cargada. En sesiones avanzadas veremos cómo pre-cargar la imagen de Linux en una memoria Micro SD para este entorno de desarrollo.

2. Configure el jumper de alimentación (*Power*) en la posición USB. Esta opción le permite alimentar la placa desde el ordenador mediante el cable Micro USB. También puede alimentar la placa usando un regulador de 12V. En ese caso, ubique el jumper en la posición REG.

3. Inserte la memoria Micro SD con la imagen de Linux pre-cargada en el slot Micro SD ubicado en la parte posterior de la placa.

4. Conecte el puerto de Ethernet a una salida de un router local.

5. Encienda la placa y verifique la secuencia de arranque detallada a continuación.  