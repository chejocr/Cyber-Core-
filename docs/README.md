# Cyber-Core

This project represents the collaborative work of three young students who share a passion for robotics. With Python and Arduino, we developed an autonomous robot for the WRO Future Engineers competition. Here we store not only our code but also the experiences, lessons, and challenges we faced as a team. Every line of code, every wire connected, and every part assembled represents hours of effort and dedication, but also moments of joy, discovery, and personal growth.

Team Members:

* Eleazar Abisaí Pacheco Oliva 
* Stefany Andrea Tobar de Paz 
* Sergio Andrés Carrera Canel

Mission
-
Our mission is to demonstrate that technology is not just something complex used by large companies, but a tool that we, as students, can also create and leverage to solve real problems. We want our project to show that with creativity, dedication, and teamwork, it is possible to transform ideas into something useful and functional.

We are not only aiming to build a robot, but to learn throughout the process, inspire other young people to take interest in science and engineering, and prove that innovation is within everyone’s reach when discipline is combined with passion.

Vision
-
Our vision is to reach a point where projects like ours do not remain just as a school prototype, but can evolve into solutions that positively impact people’s daily lives. We imagine a future where young people have more spaces to experiment and share ideas without the fear of making mistakes, because progress often comes from errors.

We want what today begins as an academic challenge to inspire future generations to dare to think differently and to use technology as an ally to build a more efficient, fair, and sustainable world.

Project Components
-
In the development of our robotics project, it was essential to have a set of tools and devices that allowed us to design, build, and operate the autonomous robot. Each element plays a specific role in the system, contributing from the structural part to the control logic and interaction with the environment.

Current components list:
-
* Raspberry Pi 5 → main brain of the robot, responsible for real-time data processing, coordinating sensors, and executing autonomous navigation algorithms.

* Arduino UNO with Elegoo Shield → intermediary between the Raspberry Pi and motors/servos, allowing precise speed and direction control.

* 12V DC Motor → provides traction for the rear wheels, enabling the robot to move forward, backward, and adjust speed depending on terrain and obstacles.

* Servo motor → controls the steering of the front axle, essential for precise turns and maintaining trajectory.

* Camera (ELEGOO ESP32-S3 CAM V1.0 or webcam) → enables obstacle detection and color differentiation, essential for autonomous navigation.

* ELEGOO 7.4V Battery → main power source for all components, optimized for sufficient duration during tests and competitions.

* 3 ultrasonic sensors → detect obstacles in front and on the sides, contributing to real-time decision-making.

* Car chassis → physical structure that supports all components, adapted with 3D printed parts to ensure stability and weight distribution.

* 3D printed parts → used to secure electronics and the battery to the chassis, as well as to facilitate assembly and protect sensitive components.

Each component was carefully chosen, considering compatibility, efficiency, and ease of integration. The Raspberry Pi 5 was selected for its superior processing power, enabling the execution of more complex computer vision algorithms. Ultrasonic sensors were calibrated to detect obstacles at different distances, while the servo and DC motor ensured smooth and safe movement.

Project Log
-
January 8, 2025
We began by disassembling a remote-control car to reuse the rear chassis. We defined the components we would need and started the base programming for vehicle control, setting up the code structure in Python for the Raspberry Pi.

January 22, 2025
Progressed with programming, implementing the first motor movement and energy management functions. Defined the remote-control model to be integrated and started initial communication tests between the Raspberry Pi and Arduino.

March 10, 2025
3D printed the main parts: the upper and lower bases to hold the battery and electronic boards. Assembled them to ensure proper fit on the chassis, confirming physical compatibility.

April 15, 2025
Verified chassis stability and adjusted printed part designs to improve weight distribution. Continued advancing in control logic and planned camera integration for obstacle detection.

May 28, 2025
Ordered the front axle and the Raspberry Pi board from the electronics store. Researched motor controllers and vision system requirements, evaluating libraries and algorithms for image processing.

June 20, 2025
Received the front axle and began integrating it into the chassis. Adjusted printed parts for proper fitting and verified wheel alignment with proximity sensors.

July 10, 2025
Received the Raspberry Pi and started OS setup, library installation, and communication tests with Arduino. Integrated the camera for obstacle detection and began testing color filtering algorithms to identify red and green objects.

July 25, 2025
Completed physical integration of all components: chassis, front axle, board, battery, camera, and ultrasonic sensors. Ran basic power-on and supply verification tests. It was very rewarding to finally see the robot assembled.

August 11–25, 2025
Started prototype functionality tests, evaluating manual control and basic autonomy. Adjusted code parameters to improve movement stability and accuracy. Detected ultrasonic signal interference and calibrated sensor readings.

August 26, 2025
Conducted obstacle detection tests in different scenarios and lighting conditions. Optimized code to reduce latency between camera image capture and motor/servo movement execution.

August 27, 2025
Tested red cube detection, adjusting HSV filters and color ranges. The robot successfully distinguished between red and orange, avoiding navigation errors.

August 28, 2025
Began testing green obstacle detection. Implemented adjustments in white balance and image smoothing filters, improving vision system reliability.

Challenges, Learning, and Growth
-
 
One of the biggest challenges was integrating all the components into a single functional system. We had to handle not only programming but also hardware compatibility, power supply, and weight distribution. Every failure became a learning opportunity: sensor calibration, code debugging, and physical design improvements.

Teamwork was essential. There were frustrating moments when nothing worked, but constant communication and task division allowed us to overcome obstacles. We learned that every member brings something unique: ideas, creativity, patience, and problem-solving.

Beyond the technical aspects, the project taught us important values: perseverance, organization, patience, and the importance of documentation. Every test, every adjustment, and every line of code reflects our effort and growth as students and as a team.

Impact and Future Projections
-

Although our robot is currently a prototype, we see it as the foundation for future, more complex projects. We envision autonomous systems capable of contributing in logistics, safety, or emergency assistance. We want this project to inspire other young people to explore robotics, showing that with effort and creativity, ideas can be transformed into real solutions.

Cyber-Core will not only be remembered as a competition robot, but as an example of innovation, perseverance, and teamwork, proving that technology is within the reach of those who dare to learn and create
