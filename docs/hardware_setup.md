 Conexiones Arduino UNO (Elegoo)
 Servomotor dirección
Pin Arduino	Componente	Notas
D10	Servo dirección	Pulso PWM, centrado en 111°
 Motores DC (Driver integrado en DeviceDriverSet_Motor)

Conexión al shield/controlador del kit ELEGOO.

Manejado desde la librería DeviceDriverSet_Motor.

No requiere asignar pines manualmente (los maneja la librería).

 Sensores ultrasónicos
Pin Arduino	Componente	Función
D13	US Derecho - TRIG	Disparo
D12	US Derecho - ECHO	Recepción
A0	US Izquierdo - TRIG	Disparo
A1	US Izquierdo - ECHO	Recepción
A2	US Frontal - TRIG	Disparo
A5	US Frontal - ECHO	Recepción
 Botón de activación
Pin Arduino	Componente	Función
D2	Botón de inicio	Activa/desactiva los motores
 Comunicación Serial

USB-B del Arduino ↔ USB-A de Raspberry.

Velocidad: 115200 baudios.

 Resumen general
Pin Arduino	Conexión
D10	Servo dirección
D13	Ultrasonido derecho TRIG
D12	Ultrasonido derecho ECHO
A0	Ultrasonido izquierdo TRIG
A1	Ultrasonido izquierdo ECHO
A2	Ultrasonido frontal TRIG
A5	Ultrasonido frontal ECHO
D2	Botón de activación motores
USB-B	Comunicación serial con Raspberry
