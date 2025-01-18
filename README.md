# **CONTROL LABORATORY: SERVO-MOTOR CONTROL AND SYSTEM SIMULATION – PART 2**

## **Overview**
This lab focuses on real-time evaluation, simulation, and control of a servo-motor system using MATLAB, Simulink, and the Quanser QUARC toolbox. The exercises build upon Part 1 and explore open-loop and closed-loop systems, as well as real-time digital implementation.

---

## **Prerequisites**
1. Completion of Part 1 of the lab.
2. Familiarity with MATLAB 2023a, Simulink, and the QUARC toolbox.
3. Access to the Control Lab setup, including the servo-motor hardware and licensed software.

---

## **Objectives**
- Evaluate the open-loop and feedback control systems in real-time.
- Analyze the effects of time delay and sampling on system performance.
- Explore differences between mathematical models and physical systems.
- Implement digital compensators for real-time control.

---

## **Lab Setup**
- **Software**: MATLAB 2023a, Simulink, QUARC toolbox.
- **Hardware**: Servo-motor system interfaced via analog I/O.
- **Working Directory**: Use a local directory (e.g., `C:\temp`) to avoid network delays.

---

## **Tasks**
### 1. **Open-Loop System Evaluation**
   - Simulate and compare continuous and real-time open-loop systems.
   - Record and analyze responses for sinusoidal inputs of 1 rad/s and 5 rad/s.

### 2. **Continuous Feedback Control**
   - Implement proportional feedback control (Gain \(K = 2.23\)).
   - Evaluate the impact of varying gains, input limits, and time delays.
   - Modify the controller to optimize closed-loop performance.

### 3. **Real-Time Digital Implementation**
   - Create a digital compensator with a feedback loop.
   - Compare continuous and digital control responses.
   - Assess the effects of sample time variation on stability and performance.

---

## **Deliverables**
1. **Q2.1**: Compare the outputs of the simulated and real open-loop systems for sinusoidal inputs at 1 rad/s and 5 rad/s. Discuss reasons for differences.
2. **Q2.2**: Plot and compare the outputs and control signals for the real feedback system with \(K = 2.23\) and \(K = 0.2\). Suggest controller modifications to respect servo motor limits.
3. **Q2.3**: Analyze the effects of increasing time delays on the real feedback system. Compare behaviors with the mathematical model and discuss differences.
4. **Q2.4**: Evaluate how removing the servo motor’s load affects system behavior. Identify which physical properties changed and their impact on closed-loop performance.
5. **Q2.5**: Compare time responses of the continuous and digital feedback controllers. Discuss performance differences in terms of overshoot and settling time.
6. **Q2.6**: Examine how increasing sample time (\(T = 0.04\)) affects system stability and performance in the real plant.

---


---
