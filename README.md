[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19508777&assignment_repo_type=AssignmentRepo)
# Lab04: Comunicación UART en PIC18F45K22

## Integrantes

[Diego Alexander Villabona Serna](https://github.com/alexovs71)

[Cristian Eduardo Huertas Moreno](https://github.com/Kristianx00)

## Documentación
## Introducción
Bien sabemos que la comunicacion entre microcontroladores y dispositivos externos es importante en sistemas embebidos, uno de los protocolos más utilizados para este propósito es UART. En este proyecto se emplea el Pic18f45k22, un conversor USB-UART y un PC para mantener esta comunicacion. Ademas se usa protoboard y fuente de alimentacion, esto con el fin de alimentar los componentes.
## Objetivos
-Configurar el modulo UART del pic para dar con una comunicacion asincrona.
-Transmitir datos del pic hacia un terminal serial con un conversor USB-UART.
-Implementar funciones para la transmision y recepcion.
-Observar datos transmitidos por el microcontrolador.

Para ello debemos de saber que es el UART, Pues bueno, es un protocolo de comunicación serial tipo asíncrono, entonces se usa para una transmision de datos entre microcontroladores, sensores, etc. Su funcionamiento no depende de una señal de reloj compartida, esto hace que sea mas simple y eficiente en distintas conexiones.
Tenemos que TX seria la linea de salida de datos y RX la linea de entrada.
## Materiales 
- Microcontrolador Pic18f45k22: Este sera el encargado principal del sistema pues con el se programara los datos atraves del protocolo UART.

-Conversor USB-UART cp2102: Se usa para conectar el pic a un puerto USB del pc pasando la señal UART a USB.

-Protoboard: Este, pues facilitara las conexiones entre componentes.

-Jumper: Nos facilitará de igual manera conexiones entre microcontrolador y conversor.

-Fuente de alimentación: Esta, pues se encargara de alimentarnos el pic y demás consumos requeridos.

-Computador: Este, pues nos recibirá los datos enviados desde el PIC.
## Implementación


## Diagramas

## Conclusiones
La implementacion de la comunicacion UART en el microcontrolador pib18f45k22 nos permitio establecer un canal de transmision y una recepcion de datos confiable y bastante eficiente entre el sistema y el PC. Se observo que al sier un protocolo asincrono es bastante simple y no precisa de muchas conexiones. Durante el desarrollo del proyecto se comprendio la estructura y funcionamiento, al igual que se resalto la importancia de realizar conexiones correctas entre los componentes.