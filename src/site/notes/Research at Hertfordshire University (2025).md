---
{"dg-publish":true,"permalink":"/research-at-hertfordshire-university-2025/"}
---

![[Pasted image 20260127001944.png](https://youtu.be/PO_Oujd9IJE?si=YZsR1_sa_URyOwzR)


<div class="carousel-container">
  <div class="carousel-track">
    <img src="imagenes/IMG_7831.jpg" alt="Imagen 1">
    <img src="imagenes/IMG_7822.jpg" alt="Imagen 2">
    <img src="imagenes/IMG_7820.jpg" alt="Imagen 3">
    <img src="imagenes/IMG_7770.jpg" alt="Imagen 4">
    <img src="imagenes/IMG_7582.jpg" alt="Imagen 5">
    <img src="imagenes/IMG_7187.jpg" alt="Imagen 6">
    <img src="imagenes/IMG_7099.jpg" alt="Imagen 7">
    <img src="imagenes/IMG_6684.jpg" alt="Imagen 8">
    <img src="imagenes/IMG_6561.jpg" alt="Imagen 9">
    <img src="imagenes/IMG_6559.jpg" alt="Imagen 10">
    <img src="imagenes/IMG_6558.jpg" alt="Imagen 11">
    <img src="imagenes/IMG_7753.jpg" alt="Imagen 12">
    <!-- Duplicado para loop infinito -->
    <img src="imagenes/IMG_7831.jpg" alt="Imagen 1">
    <img src="imagenes/IMG_7822.jpg" alt="Imagen 2">
    <img src="imagenes/IMG_7820.jpg" alt="Imagen 3">
    <img src="imagenes/IMG_7770.jpg" alt="Imagen 4">
    <img src="imagenes/IMG_7582.jpg" alt="Imagen 5">
    <img src="imagenes/IMG_7187.jpg" alt="Imagen 6">
    <img src="imagenes/IMG_7099.jpg" alt="Imagen 7">
    <img src="imagenes/IMG_6684.jpg" alt="Imagen 8">
    <img src="imagenes/IMG_6561.jpg" alt="Imagen 9">
    <img src="imagenes/IMG_6559.jpg" alt="Imagen 10">
    <img src="imagenes/IMG_6558.jpg" alt="Imagen 11">
    <img src="imagenes/IMG_7753.jpg" alt="Imagen 12">
  </div>
</div>

<style>
.carousel-container {
  overflow: hidden;
  width: 100%;
  margin: 20px 0;
  border-radius: 10px;
}

.carousel-track {
  display: flex;
  animation: scroll 30s linear infinite;
  width: fit-content;
}

.carousel-track img {
  height: 300px;
  width: auto;
  object-fit: cover;
  margin-right: 15px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

@keyframes scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-50%);
  }
}

.carousel-track:hover {
  animation-play-state: paused;
}
</style>

This exploratory mindset translated directly into my academic pursuits during my exchange semester in the latter half of 2025, when I worked alongside the research team at the XR Lab in the University of Hertfordshire. I relocated to Hatfield as the inaugural participant in a new "research and professional exchange" program, which presented unique challenges given the absence of predetermined structure or established protocols. Despite the initial uncertainty and limited guidance, I navigated the ambiguity of the position and developed a substantive research project from conception through near-completion. Between September and mid-November, I independently conceptualized and executed "Creation and Comparative of a Gesticular-Based Controller on Drone Tele-Operations," a project examining human-machine interfaces in unmanned aerial vehicle control. The work involved developing a VR simulation environment in Unity that enabled drone operation through both conventional controllers and novel finger-tracking technology, implementing PID control algorithms to transform biometric finger-position data into precise flight commands. While time constraints prevented completion of the full scientific paper within the 2025 calendar year, the project represents a significant contribution to research on intuitive control systems and accessibility in drone teleoperation.

The technical implementation of this project required comprehensive integration of multiple software systems and development frameworks. Working within Unity's game engine, I utilized the XR Interaction Toolkit alongside its open-source extension, XR Hands, which employs infrared camera tracking to create three-dimensional skeletal representations of hand movements. The primary innovation involved bypassing traditional gesture recognition, which relies on discrete hand positions and suffers from limited precision, in favor of continuous finger-curl measurements mapped directly to drone control axes. This approach converted real-time biometric data into thrust, yaw, pitch, and roll commands through a unified processing pipeline that maintained consistency between gesticular and conventional control inputs. The system architecture incorporated custom middleware managers to coordinate interactions between the physical hardware, virtual environment, and physics simulation, ultimately producing a responsive control scheme that reduced the cognitive load typically associated with multi-axis vehicle operation.

The experimental validation phase involved designing eight progressively challenging obstacle courses to evaluate controller performance and user adaptation. These courses tested fundamental drone piloting skills, forward movement, altitude control, directional changes, and precision navigation, in scenarios of increasing complexity, culminating in tasks requiring navigation through moving obstacles. Preliminary testing with a small cohort of participants from engineering disciplines revealed that while conventional controllers maintained advantages in completion time and crash frequency for complex tasks, the gesticular interface approached comparable performance levels in simpler scenarios. The data suggested that responsiveness and intuitiveness of finger-based control could benefit routine operations, though the technology's sensitivity and the physical demands of sustained hand positioning indicated areas requiring refinement before professional implementation would be viable.

The research experience in Hertfordshire provided valuable exposure to the current landscape of European mechanical engineering and robotics development, particularly regarding security protocols and software implementation standards. Through collaborations with academics and industry professionals in these fields, I gained practical insights into the methodologies and compliance frameworks that define contemporary European engineering practice. These interactions illuminated the substantial differences in regulatory approaches, cybersecurity considerations, and software verification processes compared to those prevalent in North American contexts. This international perspective has proven invaluable in understanding how regional requirements and cultural approaches shape technical development, and has significantly broadened my comprehension of the global engineering ecosystem beyond theoretical academic knowledge.