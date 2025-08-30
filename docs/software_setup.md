1️⃣ Raspberry Pi 5
🔹 Requisitos

Raspberry Pi OS (preferible 64-bit)

Python 3.10+

Pip actualizado

🔹 Instalación de librerías
sudo apt update
sudo apt install python3-pip python3-opencv -y
pip3 install numpy pyserial

🔹 Código principal

Archivo: wro_roi_color_logic.py

Configura la cámara y ROIs.

Detecta líneas, paredes y cubo rojo.

Envía comandos por serial a Arduino:

STEER:<valor>,VEL:<valor>,LINE:<0/1>

CUBO:<0/1>

Recibe datos de ultrasonido:

US:<der>,<izq>,<front>

🔹 Ejecución
python3 wro_roi_color_logic.py --show


--show opcional para abrir ventanas de depuración.

Se puede ejecutar al inicio mediante crontab o systemd si se desea automatizar.

2️⃣ Arduino UNO / Elegoo
🔹 Requisitos

IDE Arduino 1.8+

Librería DeviceDriverSet instalada (del kit ELEGOO)

🔹 Código principal

Archivo: main.ino

Controla:

Servomotor de dirección

Motores DC (velocidad y dirección)

Lectura de 3 sensores ultrasónicos

Procesa comandos serial recibidos de la Raspberry

Envía distancias de ultrasonido cada 50 ms

Botón físico para activar/desactivar motores

🔹 Cargar código

Conectar Arduino vía USB a la PC o Raspberry

Abrir main.ino en IDE Arduino

Seleccionar placa: Arduino UNO

Seleccionar puerto USB correspondiente

Subir código

3️⃣ Comunicación entre Raspberry y Arduino

Puerto serial de Arduino detectado como /dev/ttyUSB0 en Raspberry.

Baudrate: 115200

Formato de mensajes:

Raspberry → Arduino: STEER:<int>,VEL:<int>,LINE:<0/1> y CUBO:<0/1>

Arduino → Raspberry: US:<der>,<izq>,<front>

4️⃣ Depuración y pruebas

Conectar solo Raspberry y Arduino → verificar comunicación serial

Abrir Python y comprobar que recibe valores de US:

Agregar cámara y verificar que se abren las ventanas de máscara (mask_red, mask_blue, etc.)

Ajustar parámetros de HSV, STEER y velocidad según pruebas en pista
