---
{"dg-publish":true,"permalink":"/self-control-robot/"}
---

Fifth semester's final project for Dr. Alfonso Ávila's class on advanced embedded systems. For the class challenge we had to implement at least two or three different interfaces that could control two DC motors and a Servomotor to follow a certain route. We chose to control our cart through UART and Hardcoding (CAN) interfaces, making a system as denoted in the graphic below that uses different mechanical  sensors (ESC, IMU) to gather data from the motors and about the vehicle's movement in order to correct its own course while it runs. The missing interface, that was developed but we didn't have enough time to polish, was a "GPS" simulated through a camera in the ceiling and the connection to a NRF sensor that using computer vision calculated the position of the vehicle inside a certain range. 

> [Embedded MCUs Repository](https://github.com/CEJ2-Robotics/JO1_Embedded)
> [Electronics Repository](https://github.com/CEJ2-Robotics/JO1_Electronics)
> [Control Repository ](https://github.com/CEJ2-Robotics/JO1_Control.git)

---

<iframe width="560" height="315" src="https://youtu.be/gFDlEiFDrms" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

>Final Model

![EFD0A410-362B-4D2D-864B-83AA590E23E9_1_105_c.jpeg](/img/user/imagenes/EFD0A410-362B-4D2D-864B-83AA590E23E9_1_105_c.jpeg)

---

> [Research Paper](https://docs.google.com/document/d/1-Lp5cSIEmAinlWhfnXFWSenTsRBmVe9RvbURuot7qUM/edit?tab=t.0)
![Pasted image 20250212103157.png](/img/user/imagenes/Pasted%20image%2020250212103157.png)

---

> Final 3D Model For the designed PCB and fabricated/tuned PCB

| ![Pasted image 20250212021356.png](/img/user/imagenes/Pasted%20image%2020250212021356.png) | ![Pasted image 20250212021414.png](/img/user/imagenes/Pasted%20image%2020250212021414.png) |
| ------------------------------------ | ------------------------------------ |

![Pasted image 20250212021442.png](/img/user/imagenes/Pasted%20image%2020250212021442.png)