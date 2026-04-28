<!--
  ============================================================
   ParacosmYy / GS-Paracosm GitHub Profile README
   Style: Transparent · Clean Cyber · Embedded Systems
   Usage: Copy this file content to ParacosmYy/README.md
  ============================================================
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:E0F7FF,35:EDE9FE,70:F8FAFC,100:DCFCE7&text=GS-PARACOSM&fontColor=1E293B&fontSize=48&fontAlignY=35&animation=fadeIn&desc=MCU%20Firmware%20%C2%B7%20RTOS%20%C2%B7%20Industrial%20Bus%20%C2%B7%20Robotics%20Control&descAlignY=56&descSize=15" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2600&pause=900&color=2563EB&center=true&vCenter=true&width=980&lines=Embedded+Firmware+Engineer;STM32+%2F+FreeRTOS+%2F+CAN-FD+%2F+EtherCAT;Bootloader+%2B+OTA+%2B+Fault+Diagnosis;Trace+First+%C2%B7+Printf+Later;From+MCU+to+Embedded+Linux+to+Robotics" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-MCU%20Real--Time%20Control-3B82F6?style=for-the-badge&labelColor=EFF6FF&color=3B82F6" />
  <img src="https://img.shields.io/badge/Direction-Embedded%20Linux%20%26%20Robotics-8B5CF6?style=for-the-badge&labelColor=F5F3FF&color=8B5CF6" />
  <img src="https://img.shields.io/badge/Style-Trace%20First%2C%20Printf%20Later-06B6D4?style=for-the-badge&labelColor=ECFEFF&color=06B6D4" />
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy?tab=followers"><img src="https://img.shields.io/github/followers/ParacosmYy?style=social" /></a>
  <img src="https://komarev.com/ghpvc/?username=ParacosmYy&label=Profile%20Views&color=60a5fa&style=flat" />
</p>

---

<div align="center">

### 🌌 Clean Cyber Embedded System Dashboard

<img src="https://skillicons.dev/icons?i=c,cpp,cmake,bash,linux,docker,git,github,vscode&theme=light" />

</div>

<br>

<table>
<tr>
<td width="58%" valign="top">

## 👋 About Me

我是 **GS-Paracosm**，目前长期聚焦 **MCU 固件、RTOS 实时系统、工业通信、Bootloader/OTA、机器人底层控制**。

我更喜欢把嵌入式问题拆到足够底层：

- 不是只看代码能不能跑，而是看 **时序、总线、缓存、中断、DMA、任务调度** 是否真的稳定；
- 不是只会 `printf`，而是优先用 **Trace、逻辑分析仪、示波器、故障寄存器、栈回溯** 找到真实现场；
- 不是只做 Demo，而是更关注 **可升级、可回滚、可诊断、可维护** 的工程系统。

</td>
<td width="42%" valign="top">

## 🧭 Current Coordinate

```yaml
name      : GS-Paracosm
identity  : Embedded Firmware Engineer
base      : Xi'an, China
mainline  : MCU -> Embedded Linux -> Robotics

focus:
  - STM32 / Cortex-M
  - FreeRTOS / RT-Thread
  - CAN-FD / EtherCAT
  - Bootloader / OTA
  - Fault Diagnosis
  - Motor Control

motto: Trace first, printf later.
```

</td>
</tr>
</table>

---

## 🧩 Tech Stack · 技术栈矩阵

<table>
<tr>
<td width="50%" valign="top">

### 🧠 MCU / Core

<p>
  <img src="https://img.shields.io/badge/STM32H7-EEF6FF?style=flat-square&logo=stmicroelectronics&logoColor=2563EB&labelColor=EFF6FF&color=60A5FA" />
  <img src="https://img.shields.io/badge/STM32F4-EEF6FF?style=flat-square&logo=stmicroelectronics&logoColor=2563EB&labelColor=EFF6FF&color=60A5FA" />
  <img src="https://img.shields.io/badge/STM32G4-EEF6FF?style=flat-square&logo=stmicroelectronics&logoColor=2563EB&labelColor=EFF6FF&color=60A5FA" />
  <img src="https://img.shields.io/badge/Cortex--M4%2FM7-F5F3FF?style=flat-square&logo=arm&logoColor=7C3AED&labelColor=F5F3FF&color=A78BFA" />
  <img src="https://img.shields.io/badge/CMSIS-ECFEFF?style=flat-square&logo=arm&logoColor=0891B2&labelColor=ECFEFF&color=22D3EE" />
</p>

- NVIC / SysTick / PendSV / SVC
- ADC / DMA / TIM / PWM / FDCAN
- Flash / Option Bytes / VTOR / MPU
- D-Cache / I-Cache / AXI SRAM / SRAM4

</td>
<td width="50%" valign="top">

### ⚙️ RTOS / Scheduler

<p>
  <img src="https://img.shields.io/badge/FreeRTOS-EFF6FF?style=flat-square&logoColor=2563EB&labelColor=EFF6FF&color=3B82F6" />
  <img src="https://img.shields.io/badge/RT--Thread-F0FDFA?style=flat-square&logoColor=0D9488&labelColor=F0FDFA&color=14B8A6" />
  <img src="https://img.shields.io/badge/CMSIS--RTOS2-F5F3FF?style=flat-square&logo=arm&logoColor=7C3AED&labelColor=F5F3FF&color=8B5CF6" />
  <img src="https://img.shields.io/badge/Zephyr-F8FAFC?style=flat-square&logo=zephyrproject&logoColor=334155&labelColor=F8FAFC&color=94A3B8" />
  <img src="https://img.shields.io/badge/ThreadX-F8FAFC?style=flat-square&labelColor=F8FAFC&color=94A3B8" />
</p>

- Task / Queue / Semaphore / EventGroup
- Task Notification / StreamBuffer / MessageBuffer
- ISR FromISR API / PendSV 上下文切换
- Stack High Water Mark / Watchdog 策略

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 Industrial Communication

<p>
  <img src="https://img.shields.io/badge/CAN--FD-EEF2FF?style=flat-square&labelColor=EEF2FF&color=6366F1" />
  <img src="https://img.shields.io/badge/EtherCAT-EEF2FF?style=flat-square&labelColor=EEF2FF&color=6366F1" />
  <img src="https://img.shields.io/badge/CANopen-F5F3FF?style=flat-square&labelColor=F5F3FF&color=8B5CF6" />
  <img src="https://img.shields.io/badge/Modbus--RTU-ECFEFF?style=flat-square&labelColor=ECFEFF&color=06B6D4" />
  <img src="https://img.shields.io/badge/RS485-F0FDFA?style=flat-square&labelColor=F0FDFA&color=14B8A6" />
  <img src="https://img.shields.io/badge/UART-F8FAFC?style=flat-square&labelColor=F8FAFC&color=64748B" />
</p>

- CAN-FD 29-bit 扩展 ID 规划
- DLC 8 / 32 / 64 协议帧设计
- Little-endian 线格式与 DMA 友好解析
- EtherCAT 从站 PDO / SDO / SyncManager

</td>
<td width="50%" valign="top">

### 🛠 Build / Debug / CI

<p>
  <img src="https://img.shields.io/badge/GCC-F8FAFC?style=flat-square&logo=gnu&logoColor=334155&labelColor=F8FAFC&color=64748B" />
  <img src="https://img.shields.io/badge/CMake-EFF6FF?style=flat-square&logo=cmake&logoColor=2563EB&labelColor=EFF6FF&color=3B82F6" />
  <img src="https://img.shields.io/badge/Ninja-F8FAFC?style=flat-square&logoColor=334155&labelColor=F8FAFC&color=64748B" />
  <img src="https://img.shields.io/badge/Makefile-F8FAFC?style=flat-square&labelColor=F8FAFC&color=64748B" />
  <img src="https://img.shields.io/badge/Docker-ECFEFF?style=flat-square&logo=docker&logoColor=0891B2&labelColor=ECFEFF&color=22D3EE" />
  <img src="https://img.shields.io/badge/WSL2-F8FAFC?style=flat-square&logo=linux&logoColor=334155&labelColor=F8FAFC&color=64748B" />
</p>

- arm-none-eabi-gcc / clangd / clang-format
- J-Link / ST-Link / OpenOCD / GDB
- VSCode / Cursor / Cortex-Debug
- Shell / Just / CMake Presets / Local CI

</td>
</tr>
</table>

---

## 🚀 Core Engineering Blocks

<table>
<tr>
<td width="33%" valign="top">

### 🧬 Bootloader / OTA

<p align="center">
  <img src="https://img.shields.io/badge/A%2FB%20Partition-DBEAFE?style=for-the-badge&labelColor=EFF6FF&color=60A5FA" />
</p>

- Bootloader + Dual APP
- 非活跃分区升级
- CRC16 分包校验
- CRC32 整包校验
- Trial Boot 确认机制
- 失败回滚与状态机

</td>
<td width="33%" valign="top">

### 🧯 Fault Diagnosis

<p align="center">
  <img src="https://img.shields.io/badge/Post--mortem-FAE8FF?style=for-the-badge&labelColor=FAF5FF&color=C084FC" />
</p>

- HardFault / BusFault
- CFSR / HFSR / BFAR / MMFAR
- PC / LR / xPSR / MSP / PSP
- cmBacktrace
- addr2line 符号定位
- 故障现场保留

</td>
<td width="33%" valign="top">

### 🤖 Robotics Control

<p align="center">
  <img src="https://img.shields.io/badge/Low--Level%20Control-CCFBF1?style=for-the-badge&labelColor=F0FDFA&color=2DD4BF" />
</p>

- 实时控制链路
- 传感器采样与滤波
- CAN-FD 设备通信
- EtherCAT 周期同步
- 电机控制基础
- MCU + MPU 协同

</td>
</tr>
</table>

---

## 🧪 Embedded Lab · 实验室能力

<table>
<tr>
<td width="50%" valign="top">

### 🔬 Debug Instruments

```txt
Oscilloscope        -> 时序 / 电源纹波 / PWM / 波形验证
Logic Analyzer     -> UART / SPI / I2C / CAN 时序分析
J-Link / ST-Link   -> SWD 下载 / GDB 调试 / RTT 日志
Multimeter         -> 电源 / 电阻 / 连通性 / 基础排查
```

</td>
<td width="50%" valign="top">

### 🧰 Engineering Habits

```txt
Bring-up           -> 先电源、再时钟、再外设、最后业务
Driver             -> 先阻塞、再中断、再 DMA、再 RTOS 化
Debug              -> 先现场、再假设、再验证、最后闭环
Protocol           -> 先帧格式、再状态机、再异常恢复
```

</td>
</tr>
</table>

---

## 🛰 Project Orbit · 项目轨道

<table>
<tr>
<td width="50%" valign="top">

### ⚡ PMS Power Management System

> `STM32H7` · `FreeRTOS` · `CAN-FD` · `Bootloader` · `OTA` · `ADC DMA`

- 双 CAN-FD 通信链路
- 电压 / 电流 ADC + DMA 采样
- Bootloader + A/B APP 分区升级
- Watchdog + 多级故障保护
- EasyLogger 日志与状态上报

</td>
<td width="50%" valign="top">

### 🔗 EtherCAT to CAN-FD Gateway

> `STM32H743` · `LAN9253` · `EtherCAT Slave` · `CAN-FD` · `DWT Trace`

- EtherCAT 从站协议栈迁移
- LAN9253 PDI 通信优化
- 1ms 控制周期时序诊断
- PDO / SDO 数据通道拆分
- 逻辑分析仪 + DWT 定位抖动

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖐 Dexterous Hand CAN-FD Protocol

> `CAN-FD` · `29-bit ID` · `DLC32` · `Protocol Design` · `Device Identity`

- 六自由度灵巧手控制协议
- 控制 / 反馈 / 配置 / 诊断 ID 分层
- Little-endian 线格式
- 设备身份、版本、UID、NodeID 设计
- TLV 扩展预留

</td>
<td width="50%" valign="top">

### 🧱 Embedded Local CI Template

> `CMake` · `Ninja` · `GCC` · `clangd` · `Docker` · `VSCode`

- 统一 GCC + CMake 构建入口
- clangd 代码索引与跳转
- Cortex-Debug + J-Link GDB Server
- just / shell 一键构建烧录
- 团队工程模板化沉淀

</td>
</tr>
</table>

---

## 🌱 Learning Roadmap

<p align="center">
  <img src="https://img.shields.io/badge/MCU%20Firmware-Done-3B82F6?style=for-the-badge&labelColor=EFF6FF" />
  <img src="https://img.shields.io/badge/RTOS%20Kernel-Deepening-8B5CF6?style=for-the-badge&labelColor=F5F3FF" />
  <img src="https://img.shields.io/badge/Industrial%20Bus-Deepening-06B6D4?style=for-the-badge&labelColor=ECFEFF" />
  <img src="https://img.shields.io/badge/Motor%20Control-Learning-14B8A6?style=for-the-badge&labelColor=F0FDFA" />
  <img src="https://img.shields.io/badge/Embedded%20Linux-Next-64748B?style=for-the-badge&labelColor=F8FAFC" />
  <img src="https://img.shields.io/badge/ROS%20Robotics-Next-64748B?style=for-the-badge&labelColor=F8FAFC" />
</p>

```mermaid
graph LR
    A[MCU Firmware] --> B[RTOS Kernel]
    B --> C[Industrial Bus]
    C --> D[Bootloader / OTA]
    D --> E[Motor Control]
    E --> F[Embedded Linux BSP]
    F --> G[ROS / Robotics]
```

---

## 📦 Featured Repositories

<p align="center">
  <a href="https://github.com/ParacosmYy/GS_Thread">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ParacosmYy&repo=GS_Thread&theme=transparent&hide_border=true&title_color=2563EB&text_color=475569&icon_color=8B5CF6" />
  </a>
  <a href="https://github.com/ParacosmYy/GS_ETERNALCHIP">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ParacosmYy&repo=GS_ETERNALCHIP&theme=transparent&hide_border=true&title_color=2563EB&text_color=475569&icon_color=8B5CF6" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy/GS_Smart_car">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ParacosmYy&repo=GS_Smart_car&theme=transparent&hide_border=true&title_color=2563EB&text_color=475569&icon_color=06B6D4" />
  </a>
  <a href="https://github.com/ParacosmYy/GS_watch">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ParacosmYy&repo=GS_watch&theme=transparent&hide_border=true&title_color=2563EB&text_color=475569&icon_color=06B6D4" />
  </a>
</p>

---

## 📊 GitHub Telemetry

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ParacosmYy&show_icons=true&theme=transparent&hide_border=true&title_color=2563EB&text_color=475569&icon_color=8B5CF6&count_private=true&include_all_commits=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ParacosmYy&layout=compact&theme=transparent&hide_border=true&title_color=2563EB&text_color=475569&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ParacosmYy&theme=transparent&hide_border=true&ring=60A5FA&fire=8B5CF6&currStreakLabel=2563EB&sideLabels=475569&dates=64748B" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ParacosmYy&theme=react&hide_border=true&bg_color=00000000&color=2563EB&line=8B5CF6&point=06B6D4&area=true&area_color=DBEAFE" width="95%" />
</p>

---

## 🧠 Engineering Keywords

<p align="center">
  <img src="https://img.shields.io/badge/HardFault%20Analysis-EFF6FF?style=flat-square&labelColor=EFF6FF&color=3B82F6" />
  <img src="https://img.shields.io/badge/DMA%20%2B%20Cache-F5F3FF?style=flat-square&labelColor=F5F3FF&color=8B5CF6" />
  <img src="https://img.shields.io/badge/MPU%20Region-ECFEFF?style=flat-square&labelColor=ECFEFF&color=06B6D4" />
  <img src="https://img.shields.io/badge/ADC%20Sampling-F0FDFA?style=flat-square&labelColor=F0FDFA&color=14B8A6" />
  <img src="https://img.shields.io/badge/CAN--FD%20Protocol-EEF2FF?style=flat-square&labelColor=EEF2FF&color=6366F1" />
  <img src="https://img.shields.io/badge/EtherCAT%20PDO%2FSDO-FAE8FF?style=flat-square&labelColor=FAE8FF&color=C084FC" />
  <img src="https://img.shields.io/badge/Bootloader%20State%20Machine-DBEAFE?style=flat-square&labelColor=DBEAFE&color=60A5FA" />
  <img src="https://img.shields.io/badge/OTA%20Rollback-CCFBF1?style=flat-square&labelColor=CCFBF1&color=2DD4BF" />
  <img src="https://img.shields.io/badge/J--Link%20RTT-F8FAFC?style=flat-square&labelColor=F8FAFC&color=64748B" />
  <img src="https://img.shields.io/badge/SystemView-F8FAFC?style=flat-square&labelColor=F8FAFC&color=64748B" />
</p>

---

## 🤝 Connect

<p align="center">
  <samp>
    我目前主要深耕 MCU 固件与实时控制，同时正在向 Embedded Linux、机器人底层控制与工业通信系统继续扩展。<br>
    如果你也关注底层系统、工业总线、机器人控制、嵌入式工程化，欢迎交流。
  </samp>
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy">
    <img src="https://img.shields.io/badge/GitHub-ParacosmYy-2563EB?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:DCFCE7,35:F8FAFC,70:EDE9FE,100:E0F7FF" width="100%" />
</p>
