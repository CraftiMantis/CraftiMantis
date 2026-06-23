<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d3b2e,100:2ED47A&height=130&section=header&text=CraftiMantis&fontColor=eafff2&fontSize=46&fontAlignY=52&desc=embedded%20%C2%B7%20edge-AI%20%C2%B7%20robotics&descSize=16&descAlignY=80" width="100%" alt="CraftiMantis"/>

</div>

---

### About

Bring-up notes for NVIDIA Jetson, Pixhawk / PX4, and the boards around them — device
trees, drivers, CAN, ROS 2, and the companion-computer networking that ties it
together. One board or stack per repo: the steps and the gotchas.

### Selected work

<div align="center">
<a href="https://github.com/CraftiMantis/jetson-pixhawk-baseboard-jp72">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=CraftiMantis&repo=jetson-pixhawk-baseboard-jp72&title_color=2ED47A&icon_color=2ED47A&text_color=c9d1d9&bg_color=0d1117&border_color=21262d&show_owner=false" alt="jetson-pixhawk-baseboard-jp72"/>
</a>
<a href="https://github.com/CraftiMantis/jetson-orin-nx-jp72-wifi">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=CraftiMantis&repo=jetson-orin-nx-jp72-wifi&title_color=2ED47A&icon_color=2ED47A&text_color=c9d1d9&bg_color=0d1117&border_color=21262d&show_owner=false" alt="jetson-orin-nx-jp72-wifi"/>
</a>
<a href="https://github.com/CraftiMantis/seeed-a203v2-xavier-nx-bringup">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=CraftiMantis&repo=seeed-a203v2-xavier-nx-bringup&title_color=2ED47A&icon_color=2ED47A&text_color=c9d1d9&bg_color=0d1117&border_color=21262d&show_owner=false" alt="seeed-a203v2-xavier-nx-bringup"/>
</a>
</div>

- **jetson-pixhawk-baseboard-jp72** — Jetson ↔ Pixhawk over ethernet (MAVLink + uXRCE-DDS) on the Holybro Pixhawk Jetson Baseboard, JetPack 7.2
- **jetson-orin-nx-jp72-wifi** — Intel / MediaTek / Realtek Wi-Fi drivers built from source for Jetson Orin on JetPack 7.2
- **seeed-a203v2-xavier-nx-bringup** — flashing, device tree, UART & CAN bring-up for the Seeed A203-V2 carrier + Xavier NX

### In progress

- Pixhawk / PX4 companion-computer integration on Jetson — uXRCE-DDS and ROS 2
- CubeMARS AK80-9 V3 motor control + `ros2_control` over SocketCAN
- Reviving EOL Jetson Xavier NX on a modern stack (JetPack 6, keeping the GPU alive)

### Stack

`Jetson` · `CUDA` · `ROS 2` · `PX4 / MAVLink` · `Linux` · `device trees` · `CAN` · `C` · `Python` · `Bash` · `Docker`

<div align="center">
<img height="160" src="https://github-readme-stats.vercel.app/api?username=CraftiMantis&show_icons=true&hide_border=true&title_color=2ED47A&icon_color=2ED47A&text_color=c9d1d9&bg_color=0d1117" alt="stats"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CraftiMantis&layout=compact&hide_border=true&title_color=2ED47A&text_color=c9d1d9&bg_color=0d1117&langs_count=8" alt="top langs"/>
</div>
