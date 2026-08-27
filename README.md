# Dobla-ropa Automatizado

Este repositorio contiene el código fuente y la documentación recuperada de un prototipo de máquina automática para doblar ropa. Fue desarrollado en el año 2019 como proyecto académico dentro del Instituto Politécnico Nacional (IPN).

## Contexto Académico
*   **Institución:** CECyT 3 "Estanislao Ramírez Ruiz" (IPN)
*   **Carrera:** Técnico en Sistemas Digitales
*   **Turno:** Vespertino
*   **Año de desarrollo:** 2019

## Descripción del Proyecto
El objetivo del proyecto consistió en diseñar, estructurar y programar un dispositivo capaz de automatizar el doblado de prendas de vestir mediante secuencias de movimiento precisas. El control central del sistema se realizó mediante un microcontrolador de la familia PIC programado íntegramente en lenguaje ensamblador.

## Tecnologías y Hardware Utilizado
*   **Microcontrolador:** PIC16F886.
*   **Lenguaje:** Ensamblador (Assembly).
*   **Actuadores:** 4 Servomotores TowerPro MG995 (Controlados por señales PWM).
*   **Materiales Estructurales:** Placa de MDF (base) y Plástico corrugado (mecanismo de doblez).
*   **Software de Diseño:** Proteus (para simulación electrónica y diseño de PCB).

## Lógica de Funcionamiento
El sistema incorpora un menú de selección de hardware (a través de un DipSwitch) que permite al usuario definir el tipo de rutina a ejecutar según la prenda. El flujo de operación es el siguiente:
1.  **Calibración:** Inicialización de todos los servomotores a una posición base de 0°.
2.  **Selección:** Recepción de instrucciones de hardware para determinar la secuencia (Ej: rutina para camisas o pantalones).
3.  **Ejecución:** El microcontrolador PIC16F886 genera y transmite las señales PWM correspondientes a cada servomotor, basándose en subrutinas de tiempo programadas para ejecutar los ángulos precisos de doblez y entrega de la prenda.

## Demostración en Video
Puedes ver el prototipo en funcionamiento a través del siguiente enlace:
[Ver demostración en YouTube](https://youtube.com/shorts/RzOltCBL1s8?si=hA6UC8u_4JbiyqMI)

*(Nota: Este repositorio documenta un trabajo escolar recuperado; el material refleja las metodologías y herramientas utilizadas en el momento de su creación).*
