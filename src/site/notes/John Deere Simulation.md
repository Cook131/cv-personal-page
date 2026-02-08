---
{"dg-publish":true,"permalink":"/john-deere-simulation/"}
---

During my first semesters at Tecnológico de Monterrey, after transferring to the Monterrey campus, I had the opportunity to meet many talented people and collaborate on several projects with industry partners. One of my favorites (and one of the most technically different) was the **John Deere Tractor Simulator**.

The main objective of this project was to establish a direct and reliable communication protocol between an FPGA microcontroller and a custom-built simulation developed in **Unity**.

![JD-Sim2.gif](/img/user/imagenes/JD-Sim2.gif)

As shown in these GIFs, the early stages of the project looked very different from the final result. Before moving to the FPGA implementation, we carried out several experimental iterations as part of our development process. These early prototypes used a Raspberry Pi, potentiometers and digital keyboards for control input, and a simple LCD display for feedback.

![preJD-Sim.gif](/img/user/imagenes/preJD-Sim.gif)

My primary role in the project was developing the simulation environment in Unity, leveraging my prior experience in game development from high school workshops. In addition, I contributed to designing the communication protocol using Verilog; what I can only describe as a somewhat archaic but effective bridge between hardware and software.

We mapped the IMU signal from the microcontroller to act as a steering wheel, while the onboard switches were used for throttle and brake control. To improve usability, we also implemented mouse-based input on the PC to fine-tune throttle and brake response, alongside other enhancements such as background music and adjustable render distance.

![JD-Sim1.gif](/img/user/imagenes/JD-Sim1.gif)

Overall, this project provided hands-on experience in hardware–software integration, real-time communication, and interactive simulation development, reinforcing my interest in embedded systems, robotics, and human–machine interfaces.