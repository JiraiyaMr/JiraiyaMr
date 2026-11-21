# Hexi Liu

**Control Science & Engineering · Embedded Robotics**  
M.Sc. student at Wuhan University of Science and Technology, China

[Academic website](https://JiraiyaMr.github.io/) · [Email](mailto:liuhexi125@gmail.com)

I study resilient control of nonlinear networked systems, with a focus on observer design, communication attacks, time delays, and H∞ performance. Alongside research, I develop embedded control software for robotic systems using STM32 and FreeRTOS.

I am interested in research internships in control and robotics in 2027, and plan to pursue a PhD in this area.

## Research

- **Resilient networked control:** fuzzy modeling, Lyapunov–Krasovskii analysis, and LMI-based synthesis for systems with communication constraints.
- **State estimation and tracking:** observer-based H∞ control and disk-region constraints on frozen closed-loop models.
- **Robotic systems:** motion control, inertial sensing, embedded implementation, and learning-enabled control.

## Research experience

**PD observer-based H∞ tracking control with 𝒟-stability constraints**  
Graduate research · Wuhan University of Science and Technology · 2026–present  
Related manuscript: **IJRNC — Under review**

- Developed a proportional–difference observer and output-tracking controller for discrete-time interval type-2 T–S fuzzy systems with measurement-output delays and dual-channel DoS attacks.
- Derived LMI conditions for joint observer/controller synthesis, mean-square asymptotic stability, and prescribed H∞ tracking performance using Lyapunov–Krasovskii analysis and free-weighting matrices.
- Incorporated disk-region 𝒟-stability constraints on the characteristic roots of corresponding frozen closed-loop models.
- Implemented MATLAB/YALMIP simulations for a spring–mass system and a two-link robotic arm, including Monte Carlo evaluation and frozen-root analysis.

## Publications & manuscripts

**Accepted · International Journal of Systems Science (IJSS)**  
He-Xi Liu, Xiao-Heng Chang, Li-Wei Hou.  
“Observer-Based Dual-Channel Attack-Dependent Adaptive Event-Triggered H∞ Control for T–S Fuzzy Networked Systems under Dual-Channel DoS Attacks.”

**Under review · International Journal of Robust and Nonlinear Control (IJRNC)**  
He-Xi Liu, Xiao-Heng Chang, Li-Wei Hou.  
“PD observer-based H∞ tracking control with 𝒟-stability constraints for IT-2 fuzzy systems with measurement delays under dual-channel DoS attacks.”

## Selected engineering projects

| Project | Engineering focus | Source |
| --- | --- | --- |
| Gimbal–mecanum-wheel robot | Four-wheel velocity mixing, wheel-speed PID, power limiting, and CAN-based board communication. | [Code & documentation](https://github.com/JiraiyaMr/gimbal-mecanum-robot) |
| Gimbal–omniwheel robot | Chassis speed mixing, motor-feedback PID, yaw control, pitch motor commands, BMI088 sensing, and USB/PC interfaces. | [Code & documentation](https://github.com/JiraiyaMr/gimbal-omniwheel-robot) |
| Gimbal–swerve-drive robot | Four-module velocity decomposition, atan2 steering targets, cascaded steering PID, and CAN-based board communication. | [Code & documentation](https://github.com/JiraiyaMr/gimbal-swerve-robot) |
| Modular vision-based waste-sorting system | STM32/FreeRTOS actuation and integration with host-side recognition; conveyors, rotary sorting, release, sensing, and compression | [Code & architecture](https://github.com/JiraiyaMr/Modular-Vision-Based-Waste-Sorting-System) |
| Quadrotor PID gain tuning | Neural-network-based online PID gain adjustment, evaluated in MATLAB/Simulink | [Research summary](https://JiraiyaMr.github.io/#research) |

My engineering experience includes chassis application software, motor-control loops, gimbal and launching functions, and subsystem integration. Public snapshots include shared team code, vendor libraries, and attributed upstream algorithms; the repository documentation describes their scope.

## Background

- **M.Sc., Control Science and Engineering** — Wuhan University of Science and Technology, 2026–present. Graduate coursework rank: **1/136**.
- **B.Eng., Automation** — Wuhan University of Science and Technology, 2022–2026. Average: **90/100**.
- **RoboMaster team awards:** National First Prizes at the 2026 Anhui and 2025 Fujian regional events.

**Tools:** MATLAB · Simulink · YALMIP · C/C++ · Python · STM32 · FreeRTOS · CAN · UART · Git · LaTeX

Contact: **[liuhexi125@gmail.com](mailto:liuhexi125@gmail.com)**
