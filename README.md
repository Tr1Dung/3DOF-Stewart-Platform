<h1 align="center">3-DOF Stewart Platform</h1>

<img width="758" height="1024" alt="zU_Y-5Q1" src="https://github.com/user-attachments/assets/c0f61896-af74-4106-bda9-7770300652b1" />

A 3-DOF (pitch, roll, heave) 3-RPS Stewart platform driven by three stepper-motor electric linear actuators and controlled by an STM32H753 microcontroller. Built as an RMIT University Vietnam engineering capstone, it serves as an academic demonstrator and as the base for ongoing work on vision-based ball balancing with closed-loop control.
**Hardware**
STM32H753, 3× DM542 drivers, actuator specs (200 mm stroke, 12 mm lead), 24V power supply.
**Build and flash**
1. Open /firmware in STM32CubeIDE → build → flash via ST-Link.
2. Putty manual input via serial communication.
3. Press Start/Stop button to Start and Stop the machine, respectively. An MCU reset brings all leg to home position.
4. In putty, 2 desired Mode is available: IMU (Sensor mode)/Manual.
