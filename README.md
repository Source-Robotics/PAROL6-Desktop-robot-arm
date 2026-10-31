
<div align="center">

# PAROL6-Desktop-robot-arm

</div>


<img src="Images/img3.png" alt="drawing" width="5000"/>

<div align="center">

</div>

<div align="center">

[![License: MIT](https://img.shields.io/badge/license-GPLv3-blue)](https://opensource.org/license/gpl-3-0/)    ![Issues](https://img.shields.io/github/issues/PCrnjak/PAROL6-Desktop-robot-arm) ![release](https://img.shields.io/github/v/release/PCrnjak/PAROL6-Desktop-robot-arm) [![Powered by the Robotics Toolbox](https://raw.githubusercontent.com/petercorke/robotics-toolbox-python/master/.github/svg/rtb_powered.min.svg)](https://github.com/petercorke/robotics-toolbox-python) 

<p align="center">
  <a href="https://source-robotics.github.io/PAROL-docs/"><img src="https://img.shields.io/badge/doc-page-orange" alt="Documentation"></a>
  <a href="http://discord.gg/prjUvjmGpZ"><img src="https://img.shields.io/discord/1072498136284667955?logo=discord&color=blue" alt="Discord"></a>
  <a href="https://source-robotics.com//"><img src="https://img.shields.io/badge/Shop-shopping-purple?logo=shopify" alt="Shop"></a>
  <a href="https://www.linkedin.com/company/source-robotics/"><img src="https://img.shields.io/badge/LinkedIn-Follow-blue?logo=linkedin" alt="LinkedIn"></a>
  <a href="https://x.com/SourceRobotics"><img src="https://img.shields.io/badge/X-Follow-black?logo=x" alt="X"></a>
  <a href="https://www.youtube.com/@source-robotics"><img src="https://img.shields.io/badge/YouTube-Subscribe-red?logo=youtube" alt="YouTube"></a>
</p>

## [▶️YouTube🔴 Video of Robot in Action!](https://youtu.be/bbrFn3aFLaA)

</div>



## 📖 Project Overview
PAROL6 is a high-performance 3D-printed desktop robotic arm. The design approach of PAROL6 was to be similar to industrial robots in terms of mechanical design, control software, and usability. Control software, GUI, and robots STL files are open-source. 

## How to build / Where to buy?

You can buy the PAROL6 robotic arm on our website: https://source-robotics.com

If you want to Source all the parts yourself and build your own follow these steps:

* Source all the parts from the [BOM](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/BOM)
* Follow [Building instructions](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/Building%20instructions) to assemble your robot
* Follow [DOCS](https://source-robotics.github.io/PAROL-docs/) to get your robot up and running.

## 📚 Resources
- [Official website](https://source-robotics.com)
- [Commander software](https://github.com/PCrnjak/PAROL-commander-software) ------ [Minimal hardware specs!](https://github.com/PCrnjak/PAROL-commander-software/blob/main/confirmed_working_systems.md)
- [PAROL-Web-Commander](https://github.com/Jepson2k/PAROL-Web-Commander) — alternative web-based commander software
- [Python API](https://github.com/PCrnjak/PAROL6-python-API) ; [Python API legacy](https://github.com/PCrnjak/PAROL6-python-API-Alvar)
- [Building instructions](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/Building%20instructions)
- [BOM](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/BOM)
- [DOCS](https://source-robotics.github.io/PAROL-docs/)
- [Video tutorials](https://youtube.com/playlist?list=PLSueoDrBt5MMTL9O8qAWZiJrNIf8-29Qz&si=Zca3UZKENje9ifow)
- [ROS2 / Moveit simulation](https://github.com/PCrnjak/PAROL6-ROS2-MOVEIT)

- [Community projects](community_projects.md) — GUIs, vision/AI demos, and hardware mods built by the community

## 🌐 More about PAROL6 robotic arm

| YouTube | Instagram | Twitter | LinkedIn |
|--------|-----------|---------|----------|
| [![YouTube](https://img.shields.io/badge/YouTube-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@source-robotics) | [![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/source_robotics/) | [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white)](https://twitter.com/SourceRobotics) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/company/source-robotics) |


| Discord | Forum | Hackaday | Blog |
|--------|-------|------| ------|
| [![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/prjUvjmGpZ) | [![Forum](https://img.shields.io/badge/Forum-0A0A0A)](https://discourse.source-robotics.com/) | [![Hackaday](https://img.shields.io/badge/Hackaday-000000?logo=hackaday&logoColor=white)](https://hackaday.io/project/191860-parol6-desktop-robotic-arm) | [![Blog](https://img.shields.io/badge/Blog-Source%20Robotics-blue)](https://source-robotics.com/blogs/blog) 

## Simulation models (URDF and MuJoCo)

**[Start with the PAROL6 model guide](https://github.com/Source-Robotics/robot_descriptions/blob/cc8168520e0c57328b9a9a8e39462b1162b96984/guides/parol6.md)** for downloads, jaw/end-effector
selection and instructions for opening the models.

The maintained models are included through the **[`models/descriptions`](https://github.com/Source-Robotics/robot_descriptions/tree/cc8168520e0c57328b9a9a8e39462b1162b96984)**
Git submodule. It pins model version **2.12.1** together with its guided
documentation. Clicking the submodule opens the shared descriptions landing
page; select PAROL6 there.

All six configurations are included: Flange only; MSG with Solid or Soft TPU
jaws; SSG48 with Solid or Fin-ray jaws; and the pneumatic gripper. The old local
model folder is replaced by this shared source. See the
[migration guide](https://github.com/Source-Robotics/robot_descriptions/blob/cc8168520e0c57328b9a9a8e39462b1162b96984/guides/legacy-models.md)
for changed file locations, public joint names and links to the previous files.

Clone this repository with its models:

```bash
git clone --recurse-submodules https://github.com/Source-Robotics/PAROL6-Desktop-robot-arm.git
```

For an existing checkout:

```bash
git submodule update --init --recursive
```

Local model folders: `models/descriptions/mujoco/parol6` and
`models/descriptions/urdf/parol6_description`.

GitHub's **Download ZIP** does not include submodule contents. For model files
without Git, use the [ready-to-use model ZIPs](https://github.com/Source-Robotics/robot_descriptions/releases/latest)
linked in the guide. Model changes are maintained in `robot_descriptions`; this
repository records an exact version rather than automatically following updates.

## ⚠️ Safety, Liability & Disclaimer
This project includes experimental software, hardware designs, and assembly documentation that are still under development and may contain bugs, errors, or incomplete features. By using, building, or modifying this project, you acknowledge that:

* You use this project entirely at your own risk
* You are solely responsible for safe assembly, testing, and operation
* No guarantee is made regarding correctness, safety, or reliability
* The authors are not responsible for any damage, injury, or loss resulting from the use or misuse of this project
* Hardware performance and safety depend on user assembly, component quality, calibration, and handling, which cannot be guaranteed
* This project is provided “as is.” If you choose to build a device yourself using these files, designs, or instructions, you do so without any warranties or guarantees, including regarding safety, reliability, or suitability for any particular purpose.

THIS PROJECT INVOLVES LETHAL VOLTAGES AND OTHER SERIOUS HAZARDS THAT CAN CAUSE SEVERE INJURY. YOU MUST READ THE FULL [SAFETY WARNING AND DISCLAIMER DOCUMENT](SAFETY_WARNING_AND_DISCLAIMER.md)  BEFORE USING ANY PROJECT FILES. BY PROCEEDING, YOU ACKNOWLEDGE AND ACCEPT ALL RISKS AND AGREE TO USE THIS PROJECT ENTIRELY AT YOUR OWN RESPONSIBILITY.

## 💸Support us

The majority of this project is open source and freely available to everyone. Your assistance, whether through donations or advice, is highly valued. Thank you!

 [![General badge](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/PCrnjak?locale.x=en_US)
[![General badge](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/PCrnjak)

## 🛡️ Licensing
Project is under GPLv3 Licence
