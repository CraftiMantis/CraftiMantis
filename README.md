I build closed-loop robots on the NVIDIA + ROS 2 stack — BLDC/CAN motor control,
flight controllers turned into real-time motor MCUs, and the Jetson edge compute and
networking underneath. Sim-to-real with Isaac Sim and Isaac Lab.

The public repos here are the foundation the robots run on — board bring-up, drivers,
and the cross-host comms.

### Building now

- **AK80-9 V3 motor control** — a `ros2_control` SystemInterface for the CubeMARS AK80-9 V3 over SocketCAN
- **Pixhawk 6X as a motor MCU** — ArduPilot + Lua + Scripting-CAN, Jetson companion over the baseboard's internal ethernet → [jetson-pixhawk-baseboard-jp72](https://github.com/CraftiMantis/jetson-pixhawk-baseboard-jp72)
- **Hoverboard hub motors on open firmware** — Artery AT32F413 mainboard reflashed and driven over UART, with a browser test bench on a Pi
- **Wheel-legged platform** — Isaac Sim → policy → hardware

### Selected work

- **[jetson-pixhawk-baseboard-jp72](https://github.com/CraftiMantis/jetson-pixhawk-baseboard-jp72)** — Jetson ↔ Pixhawk over the baseboard ethernet switch (MAVLink + uXRCE-DDS), JetPack 7.2
- **[jetson-orin-nx-jp72-wifi](https://github.com/CraftiMantis/jetson-orin-nx-jp72-wifi)** — Intel / MediaTek / Realtek Wi-Fi drivers built from source for Jetson Orin, JetPack 7.2
- **[seeed-a203v2-xavier-nx-bringup](https://github.com/CraftiMantis/seeed-a203v2-xavier-nx-bringup)** — flashing, device tree, UART & CAN bring-up for the Seeed A203-V2 + Xavier NX

### Stack

NVIDIA Jetson · Isaac Sim / Isaac Lab · ROS 2 · PX4 / ArduPilot · MAVLink · SocketCAN · BLDC / FOC · Linux / device trees · C · Python
