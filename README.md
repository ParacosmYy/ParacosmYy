<!--
  ============================================================
   ParacosmYy / GS-Paracosm GitHub Profile README
   Anime Orbit · Embedded Firmware · RTOS · OTA · Tooling
  ============================================================
-->

<p align="center">
  <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/paracosm-orbit-hero.svg" alt="Animated Paracosm project star map for embedded firmware projects" />
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy?tab=followers"><img loading="lazy" src="https://img.shields.io/github/followers/ParacosmYy?style=for-the-badge&label=FOLLOW&labelColor=FFF1F8&color=FF85C9" alt="GitHub followers" /></a>
  <img loading="lazy" src="https://komarev.com/ghpvc/?username=ParacosmYy&label=PROFILE%20VIEWS&color=7AF0FF&style=for-the-badge" alt="Profile views" />
  <img loading="lazy" src="https://img.shields.io/badge/FOCUS-MCU%20%2F%20RTOS%20%2F%20OTA-7DFFCC?style=for-the-badge&labelColor=07121E" alt="Focus: MCU, RTOS, OTA" />
</p>

<p align="center">
  <img loading="lazy" width="30%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/anime-firmware-sticker.gif" alt="Cute animated firmware engineer sticker" />
  <img loading="lazy" width="44%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/anime-orbit-sticker.gif" alt="Animated orbit sticker for MCU RTOS OTA tools and CI" />
</p>

<p align="center">
  <strong>GS / ParacosmYy</strong><br />
  <sub>二次元外壳，嵌入式内核。把项目从“能跑”推进到边界清楚、可验证、可迁移、可交付。</sub>
</p>

<p align="center">
  <a href="mailto:1264206065@qq.com">
    <img loading="lazy" src="https://img.shields.io/badge/EMAIL-1264206065%40qq.com-FF85C9?style=for-the-badge&logo=tencentqq&logoColor=white" alt="Email 1264206065@qq.com" />
  </a>
  <a href="https://github.com/ParacosmYy">
    <img loading="lazy" src="https://img.shields.io/badge/GitHub-ParacosmYy-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub ParacosmYy" />
  </a>
</p>

---

## Project Orbit

`GS_Smart_car` is the current MCU architecture anchor: AURIX TC264D smart-car firmware with App / Service / BSP / HAL / Target / Vendor boundaries, so stable business code does not swallow chip-vendor details.

`GS_ETERNALCHIP` is the OTA reliability track: STM32F411 bootloader work around Flash partitions, image validation, upgrade state, recovery path, and bad-image rejection.

`GS_Thread` is the kernel mechanism track: a readable RT-Thread style rebuild around scheduler, IPC, object container, software timer, PendSV, SysTick, and Cortex-M context switch.

`GS_Tool` is the delivery tooling track: Python / PyQt6 desktop tooling for serial data, protocol parsing, logs, replay, packaging, lint, smoke tests, and GitHub Actions.

`GCC_Cmake_ARM` is the build-system track: a reusable ARM GCC + CMake + Ninja template for scriptable, reproducible Cortex-M builds.

<p align="center">
  <a href="https://github.com/ParacosmYy/GS_Smart_car/tree/tc264-four-wheel-servo-camera-car"><img loading="lazy" src="https://img.shields.io/badge/GS__Smart__car-TC264D%20firmware-7AF0FF?style=for-the-badge&labelColor=07121E" alt="GS Smart car repository" /></a>
  <a href="https://github.com/ParacosmYy/GS_ETERNALCHIP/tree/OTA_Encrypted_Upgrade"><img loading="lazy" src="https://img.shields.io/badge/GS__ETERNALCHIP-OTA%20upgrade-FF85C9?style=for-the-badge&labelColor=07121E" alt="GS ETERNALCHIP OTA repository" /></a>
  <a href="https://github.com/ParacosmYy/GS_Thread"><img loading="lazy" src="https://img.shields.io/badge/GS__Thread-RTOS%20kernel-FFE174?style=for-the-badge&labelColor=07121E" alt="GS Thread repository" /></a>
  <a href="https://github.com/ParacosmYy/GS_Tool"><img loading="lazy" src="https://img.shields.io/badge/GS__Tool-Debug%20tooling-7DFFCC?style=for-the-badge&labelColor=07121E" alt="GS Tool repository" /></a>
  <a href="https://github.com/ParacosmYy/GCC_Cmake_ARM"><img loading="lazy" src="https://img.shields.io/badge/GCC__Cmake__ARM-Build%20template-B397FF?style=for-the-badge&labelColor=07121E" alt="GCC CMake ARM repository" /></a>
</p>

---

## Runtime Mood

I like firmware that can explain itself: clear module ownership, explicit state machines, small hardware-facing contracts, and verification commands that someone else can run without guessing.

I am especially interested in the places where embedded projects usually become blurry: board resources, interrupt boundaries, bootloader handoff, Flash metadata, scheduler context switch, protocol replay, and build reproducibility.

The visual style is soft and playful here, but the engineering taste is intentionally sharp: project boundaries should be calm, boring, and easy to migrate.

---

## Tech Constellation

<p align="center">
  <img loading="lazy" src="https://img.shields.io/badge/AURIX%20TC264D-current%20target-7AF0FF?style=flat-square&labelColor=10152F" alt="AURIX TC264D" />
  <img loading="lazy" src="https://img.shields.io/badge/STM32F411-bootloader%20track-FF85C9?style=flat-square&labelColor=10152F" alt="STM32F411" />
  <img loading="lazy" src="https://img.shields.io/badge/Cortex--M-port%20layer-FFE174?style=flat-square&labelColor=10152F" alt="Cortex-M" />
  <img loading="lazy" src="https://img.shields.io/badge/C99-embedded%20firmware-7DFFCC?style=flat-square&labelColor=10152F" alt="C99 embedded firmware" />
  <img loading="lazy" src="https://img.shields.io/badge/FreeRTOS-RTOS%20practice-B397FF?style=flat-square&labelColor=10152F" alt="FreeRTOS" />
  <img loading="lazy" src="https://img.shields.io/badge/RT--Thread-mechanism%20study-7AF0FF?style=flat-square&labelColor=10152F" alt="RT-Thread" />
  <img loading="lazy" src="https://img.shields.io/badge/ARM%20GCC-CMake%20Ninja-FF85C9?style=flat-square&labelColor=10152F" alt="ARM GCC CMake Ninja" />
  <img loading="lazy" src="https://img.shields.io/badge/Python-PyQt6%20tools-FFE174?style=flat-square&labelColor=10152F" alt="Python PyQt6 tools" />
</p>

---

## Now Loading

`RTOS internals` -> `OTA failure matrix` -> `debug-tool polish` -> `portable target boundary` -> `embedded Linux / BSP expansion`

The next direction is to keep pushing every project toward a stronger handoff story: what the hardware layer owns, what the reusable layer promises, how failure is detected, and how a reviewer can verify the result.

---

## Contact

<p align="center">
  <a href="mailto:1264206065@qq.com">
    <img loading="lazy" src="https://img.shields.io/badge/EMAIL-1264206065%40qq.com-FF85C9?style=for-the-badge&logo=tencentqq&logoColor=white" alt="Email 1264206065@qq.com" />
  </a>
  <a href="https://github.com/ParacosmYy">
    <img loading="lazy" src="https://img.shields.io/badge/GitHub-ParacosmYy-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub ParacosmYy" />
  </a>
</p>
