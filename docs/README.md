# Cyber-Core

Este proyecto representa el trabajo en conjunto de tres jóvenes que comparten la pasión por la robótica. Con Python y Arduino, desarrollamos un robot autónomo para la competencia de la WRO Futuros Ingenieros. Aquí guardamos no solo nuestro código, sino también la experiencia, los aprendizajes y los retos que vivimos como equipo. Cada línea de programación, cada cable conectado y cada pieza ajustada representa horas de esfuerzo y dedicación, pero también momentos de alegría, descubrimiento y crecimiento personal.

Integrantes:
-
* Eleazar Abisaí Pacheco Oliva 
* Stefany Andrea Tobar de Paz 
* Sergio Andrés Carrera Canel

Misión:

Nuestra misión es demostrar que la tecnología no es solo algo complicado que usan las grandes empresas, sino una herramienta que nosotros, como estudiantes, también podemos crear y aprovechar para resolver problemas reales. Queremos que nuestro proyecto muestre que con creatividad, dedicación y trabajo en equipo es posible transformar ideas en algo útil y funcional.

No buscamos únicamente construir un robot, sino aprender en el proceso, inspirar a otros jóvenes a interesarse por la ciencia y la ingeniería, y demostrar que la innovación está al alcance de todos si se combina disciplina con pasión.

Visión:

Nuestra visión es llegar a un punto donde proyectos como el nuestro no se queden únicamente en una maqueta escolar, sino que puedan evolucionar hasta convertirse en soluciones que impacten positivamente en la vida diaria de las personas. Nos imaginamos un futuro donde los jóvenes tengamos más espacios para experimentar y compartir nuestras ideas, sin miedo a equivocarnos, porque de los errores también nacen avances importantes.

Queremos que lo que hoy empieza como un reto académico, en el futuro inspire a más generaciones a atreverse a pensar distinto y a usar la tecnología como una aliada para construir un mundo más eficiente, justo y sostenible.

Componentes del Proyecto

En el desarrollo de nuestro proyecto de robótica, fue fundamental contar con un conjunto de herramientas y dispositivos que permitieran llevar a cabo el diseño, la construcción y el funcionamiento del robot autónomo. Cada elemento utilizado cumple un papel específico dentro del sistema, aportando desde la parte estructural hasta la lógica de control y la interacción con el entorno.

Lista de componentes actuales:
-
*Raspberry Pi 5 → cerebro principal del robot, encargado de procesar datos en tiempo real, coordinar sensores y ejecutar algoritmos de navegación autónoma.

*Arduino UNO con Shield Elegoo → intermediario entre la Raspberry y los motores/servos, permite controlar la velocidad y dirección de manera precisa.

*Motor DC de 12V → provee la tracción necesaria para las llantas traseras, permitiendo que el robot avance, retroceda y ajuste velocidad según el terreno y obstáculos.

*Servomotor → controla la dirección del eje delantero, esencial para realizar giros precisos y mantener la trayectoria.

*Cámara (ELEGOO ESP32-S3 CAM V1.0 o webcam) → permite detectar obstáculos y diferenciar colores, fundamental para la navegación autónoma.

*Batería ELEGOO 7.4V → fuente principal de energía para todos los componentes, optimizada para ofrecer duración suficiente durante pruebas y competencias.

*3 sensores ultrasónicos → detectan obstáculos en el frente y los laterales, contribuyendo a la toma de decisiones en tiempo real.

*Chasis del carrito → estructura física que soporta todos los componentes, adaptada mediante piezas impresas en 3D para asegurar estabilidad y distribución de peso.

*Piezas impresas en 3D → sirven para fijar la electrónica y la batería al chasis, además de facilitar el ensamblaje y la protección de componentes sensibles.

*Cada componente fue seleccionado con cuidado, evaluando su compatibilidad, eficiencia y facilidad de integración. La elección de una Raspberry Pi 5 se debió a su capacidad de procesamiento superior, permitiendo ejecutar algoritmos más complejos de visión por computadora. Los sensores ultrasónicos fueron calibrados para detectar obstáculos a diferentes distancias, mientras que el servomotor y el motor DC garantizaron un movimiento fluido y seguro.

Bitácora del Proyecto:
-
08 de Enero del 2025

Comenzamos desarmando un carrito de control remoto para aprovechar el chasis de la parte trasera. Definimos los componentes que necesitaríamos y comenzamos la programación base para el control del vehículo, estableciendo la estructura del código en Python para la Raspberry Pi.

22 de Enero del 2025

Realizamos avances en la programación, implementando las primeras funciones para el movimiento del motor y la gestión de energía. Definimos el modelo de control remoto que se integrará y comenzamos pruebas iniciales de comunicación entre la Raspberry y el Arduino.

10 de Marzo del 2025

Imprimimos en 3D las piezas principales: la base superior e inferior que sostendrán la batería y las placas electrónicas. Ensamblamos estas piezas para asegurarnos de que encajaran correctamente en el chasis, confirmando la compatibilidad física del diseño.

15 de Abril del 2025

Verificamos la estabilidad del chasis y ajustamos el diseño de las piezas impresas para mejorar la distribución del peso. Continuamos avanzando en la lógica de control y planificamos la integración de la cámara para la detección de obstáculos.

28 de Mayo del 2025

Pedimos el tren delantero y la placa Raspberry en la tienda electrónica. Investigamos los controladores necesarios para motores y sistema de visión, evaluando distintas librerías y algoritmos para procesamiento de imágenes.

20 de Junio del 2025

Recibimos el tren delantero y comenzamos a implementarlo en el chasis. Ajustamos las piezas impresas para asegurar un buen acople y verificamos la alineación de las ruedas delanteras con los sensores de proximidad.

10 de Julio del 2025

Recibimos la Raspberry Pi e iniciamos la configuración del sistema operativo, instalación de librerías necesarias y pruebas de comunicación con Arduino. Implementamos la cámara para detección de obstáculos y comenzamos a probar algoritmos de filtrado de color para identificar objetos rojos y verdes.

25 de Julio del 2025

Finalizamos la integración física de todos los componentes: chasis, tren delantero, placa, batería, cámara y sensores ultrasónicos. Realizamos pruebas básicas de encendido y verificación de alimentación. Fue un momento muy gratificante porque finalmente vimos nuestro robot completo.

11 - 25 de Agosto del 2025

Iniciamos pruebas de funcionamiento del prototipo, evaluando control manual y autonomía básica. Ajustamos parámetros en el código para mejorar la estabilidad y precisión de movimientos. Detectamos interferencias en las señales de los ultrasonidos y calibramos sus lecturas.

26 de Agosto del 2025

Realizamos pruebas de detección de obstáculos en distintos escenarios y condiciones de luz. Optimización del código para reducir la latencia entre la captura de imagen por la cámara y la ejecución de movimientos por motores y servos.

27 de Agosto del 2025

Probamos la detección del cubo rojo, ajustando filtros HSV y rangos de color. Logramos que el robot diferenciara correctamente entre rojo y naranja, evitando errores en la navegación.

28 de Agosto del 2025

Iniciamos pruebas para detección de obstáculos verdes. Se implementaron ajustes en el balance de blancos y filtros de suavizado de imagen, mejorando la confiabilidad del sistema de visión.

Retos, Aprendizajes y Crecimiento:
-
Uno de los retos más significativos fue integrar todos los componentes en un mismo sistema funcional. No solo debíamos preocuparnos por la programación, sino también por la compatibilidad de hardware, alimentación y distribución de peso. Cada fallo fue una oportunidad de aprendizaje: calibrar sensores, corregir errores de código y mejorar el diseño físico.

El trabajo en equipo fue esencial. Hubo momentos de frustración cuando nada funcionaba, pero la comunicación constante y la división de tareas nos permitió superar esos obstáculos. Aprendimos que cada integrante aporta algo único: ideas, creatividad, paciencia y resolución de problemas.

Más allá de lo técnico, el proyecto nos enseñó valores importantes: perseverancia, organización, paciencia y la importancia de la documentación. Cada prueba, cada ajuste y cada línea de código reflejan nuestro esfuerzo y crecimiento como estudiantes y como equipo.

Impacto y Proyecciones Futuras:
-
Aunque nuestro robot es hoy un prototipo, lo vemos como la base para futuros proyectos más complejos. Imaginamos sistemas autónomos capaces de colaborar en logística, seguridad o asistencia en emergencias. Queremos que este proyecto inspire a otros jóvenes a explorar la robótica, mostrando que con esfuerzo y creatividad es posible transformar ideas en soluciones reales.

Cyber-Core no solo será recordado como un robot de competencia, sino como un ejemplo de innovación, perseverancia y trabajo en equipo, demostrando que la tecnología está al alcance de quienes se atreven a aprender y crear.
