# Take-Home Labs: Laboratorios con Arduino Mega (ATmega2560)

## Introducción
Este repositorio contiene una serie de prácticas de laboratorio diseñadas para el autoaprendizaje y la experimentación en casa, enfocadas en la arquitectura del microcontrolador ATmega2560. Además, se empleó KiCad para el diseño de una shield personalizada, en la cual se integran tres plantas (electrónica, cinemática y de visualización) que permiten validar e implementar diferentes estrategias de control y adquisición de señales.

## Objetivo General
Desarrollar competencias en programación de sistemas embebidos utilizando la plataforma Arduino Mega, priorizando el control directo del hardware, así como la integración y validación de plantas físicas diseñadas en KiCad mediante una shield personalizada.

## Descipción de las plantas
**Planta 1**: Planta electrónica basada en el CD4066, utilizada para la conmutación y enrutamiento de señales analógicas mediante interruptores controlados digitalmente. Integra redes RC en cascada que permiten modificar la dinámica del sistema, ajustando su respuesta según las etapas activadas.
**Planta 2:** Planta electromecánica basada en un motor DC N20 con encoder de cuadratura, donde la señal PWM controla la velocidad mediante un MOSFET.
El encoder proporciona retroalimentación de posición y velocidad, permitiendo implementar sistemas de control en lazo cerrado.
**Planta 3:** Planta electrónica basada en el LM3914N, utilizada para visualizar una señal analógica mediante una barra de LEDs proporcional al nivel de voltaje.
Incorpora un filtro pasa-bajas RC que suaviza la señal de entrada (PWM), permitiendo una lectura estable y continua en la visualización.
