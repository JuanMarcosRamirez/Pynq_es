# Pynq_es: tutorial para el uso del entorno de productividad Pynq (Pynq-Z2)

## Hardware requerido

* La placa Zynq-Z2
* Ordenador con un navegador compatible (Chrome, Firefox)
* Cable de Ethernet
* Cable de Micro USB
* Memoria Micro SD con la distribución de Linux precargada

## Configuración del hardware

En la imagen mostrada a continuación, se puede observar una representación del kit de desarrollo Zynq-Z2 con indicadores de los elementos de hardware necesarios para trabajar con el entorno de productividad Pynq.

![Demo image](https://github.com/JuanMarcosRamirez/Pynq_es/blob/main/images/pynqz2_setup.png?raw=true "Board setting")

1. Configure el jumper de arranque (**Boot**) en la posición SD. Esta selección le permitirá arrancar la tarjeta desde la memoria Micro SD. El kit de desarrollo contiene una memoria Micro SD con una distribución de Ubuntu pre-cargada. En sesiones avanzadas veremos cómo pre-cargar la imagen de Linux en una memoria Micro SD.

2. Configure el jumper de alimentación (**Power**) en la posición USB. Esta opción le permite alimentar la placa desde el ordenador mediante el cable Micro USB. También puede alimentar la placa usando un regulador de 12V. En ese caso, debe ubicar el jumper en la posición REG.

3. Inserte la memoria Micro SD con la imagen de Linux pre-cargada en el slot Micro SD ubicado en la parte posterior de la placa.

4. Conecte el puerto de Ethernet a un router local.

5. Encienda la placa y verifique la secuencia de arranque descrita a continuación. 

## Secuencia de arranque

1. Deslize el interruptor de alimentación a la posición ON para encender la placa.

2. Se encenderá el LED rojo para confirmar que la placa está encendida.

3. Luego de unos segundos, se encenderá un LED amarillo que indica que el dispositivo Zynq está operando.

4. Luego de aproximadamente un minuto, titilarán LEDs azules y los LEDs amarillos de la placa. Luego, se apagarán los LEDs azules y los LEDs amarillos se mantendrán encendidos.

5. El sistema operativo ha arrancado y está listo para usarse.