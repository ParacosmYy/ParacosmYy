<!--
  ============================================================
   GS-PARACOSM · Cyber Embedded Systems Profile README
   Style: Cyberpunk / Embedded / Robotics / Real-Time / Industrial Bus
  ============================================================
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:0f172a,70:1e1b4b,100:312e81&height=180&section=header&text=GS-PARACOSM&fontSize=48&fontColor=E0F2FE&animation=fadeIn&fontAlignY=34&desc=MCU%20%C2%B7%20RTOS%20%C2%B7%20Industrial%20Bus%20%C2%B7%20Robotics%20Control&descSize=14&descAlignY=56" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2600&pause=900&color=38BDF8&center=true&vCenter=true&width=980&lines=Embedded+Firmware+Engineer;STM32+%2F+RTOS+%2F+CAN-FD+%2F+EtherCAT;Bootloader+%2B+OTA+%2B+Reliability+Engineering;Trace+First+%C2%B7+Printf+Later;From+MCU+to+Embedded+Linux+to+Robotics" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ONLINE-22d3ee?style=for-the-badge&labelColor=020617" />
  <img src="https://img.shields.io/badge/ROLE-Firmware%20Engineer-a78bfa?style=for-the-badge&labelColor=020617" />
  <img src="https://img.shields.io/badge/FOCUS-Real--Time%20Control-38bdf8?style=for-the-badge&labelColor=020617" />
  <img src="https://img.shields.io/badge/LOCATION-Xi'an-64748b?style=for-the-badge&labelColor=020617" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ParacosmYy&label=PROFILE%20VIEWS&style=for-the-badge&color=38bdf8&labelColor=020617" />
</p>

---

<div align="center">

```txt
╔══════════════════════════════════════════════════════════════════════════════╗
║                         EMBEDDED SYSTEMS CONTROL CORE                       ║
║                                                                              ║
║      MCU Firmware  │  RTOS Kernel  │  Industrial Bus  │  Bootloader OTA      ║
║      Trace Debug   │  Motor Control │  Embedded Linux  │  Robotics Base      ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

</div>

## 🧬 Identity Matrix

<table>
<tr>
<td width="55%">

### `GS-Paracosm`

> 嵌入式固件工程师方向，长期聚焦 **MCU 实时控制、RTOS、工业通信、Bootloader/OTA、机器人底层系统**。

我更关注的不是“代码能不能跑”，而是：

- **为什么它能稳定跑**
- **中断、DMA、Cache、RTOS 调度背后的真实行为**
- **异常现场如何保留、复现、定位和闭环**
- **通信协议如何设计成可维护、可扩展、可诊断**
- **固件系统如何做到可升级、可回滚、可追踪**

</td>
<td width="45%">

```yaml
name        : GS-Paracosm
role        : Embedded Firmware Engineer
direction   : MCU -> Embedded Linux -> Robotics
philosophy  : Trace First, Printf Later

core_domain:
  - Real-Time Firmware
  - RTOS Architecture
  - Industrial Communication
  - Bootloader / OTA
  - Fault Diagnosis
  - Robotics Low-Level Control

engineering_style:
  - Clean Architecture
  - Deterministic Timing
  - Defensive Design
  - Field Debuggable
```

</td>
</tr>
</table>

---

## ⚡ Technology Radar

<p align="center">
  <img src="https://img.shields.io/badge/MCU-STM32H7%20%7C%20STM32F4%20%7C%20STM32G4-38bdf8?style=flat-square&labelColor=020617" />
  <img src="https://img.shields.io/badge/Core-ARM%20Cortex--M4%20%7C%20M7-a78bfa?style=flat-square&labelColor=020617" />
  <img src="https://img.shields.io/badge/RTOS-FreeRTOS%20%7C%20RT--Thread%20%7C%20Zephyr-22d3ee?style=flat-square&labelColor=020617" />
  <img src="https://img.shields.io/badge/Bus-CAN--FD%20%7C%20EtherCAT%20%7C%20RS485%20%7C%20UART-818cf8?style=flat-square&labelColor=020617" />
</p>

### 🧠 MCU / Chip / Architecture

<p>
  <img src="https://img.shields.io/badge/STM32H743-020617?style=for-the-badge&logo=stmicroelectronics&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/STM32F407-020617?style=for-the-badge&logo=stmicroelectronics&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/STM32G474-020617?style=for-the-badge&logo=stmicroelectronics&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/ARM%20Cortex--M-020617?style=for-the-badge&logo=arm&logoColor=a78bfa" />
  <img src="https://img.shields.io/badge/CMSIS-020617?style=for-the-badge&logo=arm&logoColor=22d3ee" />
</p>

```txt
┌────────────────────────── MCU Capability Map ──────────────────────────┐
│  Cortex-M4 / M7                                                         │
│  ├─ NVIC / SysTick / PendSV / SVC                                       │
│  ├─ DMA / ADC / UART / SPI / I2C / FDCAN / TIM / PWM                    │
│  ├─ D-Cache / I-Cache / MPU / AXI SRAM / SRAM1~4                        │
│  ├─ Flash Sector / Option Bytes / Vector Table / VTOR                   │
│  └─ HardFault / BusFault / MemManage / UsageFault                       │
└─────────────────────────────────────────────────────────────────────────┘
```

### 🧩 Language / Firmware Foundation

<p>
  <img src="https://img.shields.io/badge/C-020617?style=for-the-badge&logo=c&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/C++-020617?style=for-the-badge&logo=cplusplus&logoColor=a78bfa" />
  <img src="https://img.shields.io/badge/Embedded%20C-020617?style=for-the-badge&logoColor=22d3ee" />
  <img src="https://img.shields.io/badge/Register%20Level-020617?style=for-the-badge&logoColor=818cf8" />
  <img src="https://img.shields.io/badge/HAL%20%2B%20LL-020617?style=for-the-badge&logoColor=38bdf8" />
</p>

```c
/* Firmware Style */
#define TRACE_FIRST_PRINTF_LATER      1
#define REALTIME_CONTROL_PRIORITY     HIGH
#define FIELD_DEBUGGABLE_DESIGN       ENABLED
#define RELIABILITY_OVER_DEMO         TRUE
```

---

## 🚀 Core Expertise

<table>
<tr>
<td width="50%">

### 🛰 Real-Time Firmware

```txt
Task Scheduling
├─ Priority Design
├─ ISR Minimalism
├─ Queue / Semaphore / EventGroup
├─ Task Notification
├─ DMA Half / Full Callback
└─ Watchdog Feeding Strategy
```

- FreeRTOS 任务拆分
- ISR 与任务解耦
- DMA + RingBuffer
- 实时采样与周期控制
- 任务栈水位监控
- 看门狗与故障降级

</td>
<td width="50%">

### 🔥 Fault Diagnosis

```txt
Crash Analysis
├─ HardFault Context
├─ CFSR / HFSR / BFAR / MMFAR
├─ PC / LR / xPSR / MSP / PSP
├─ addr2line Symbol Mapping
└─ Post-mortem Debugging
```

- cmBacktrace
- Core Dump 思路
- 故障现场保留
- 栈回溯与符号定位
- Trace / RTT / SWV
- 逻辑分析仪辅助定位

</td>
</tr>
</table>

<table>
<tr>
<td width="50%">

### 🧨 Bootloader / OTA

```txt
Firmware Upgrade Flow
├─ Bootloader
├─ App A / App B
├─ Parameter Area
├─ Firmware Receive
├─ CRC16 Packet Check
├─ CRC32 Image Verify
├─ Trial Boot
└─ Rollback Protection
```

- A/B 双 APP 分区
- 非活跃区升级
- 升级状态机
- 参数区状态标志
- 断电保护
- 失败回滚

</td>
<td width="50%">

### 🌐 Industrial Communication

```txt
Communication Stack
├─ CAN / CAN-FD
├─ EtherCAT Slave
├─ RS485 / Modbus RTU
├─ UART Protocol
├─ SPI / QSPI / OctoSPI
├─ I2C Sensor Bus
└─ Ethernet Basic Stack
```

- 29-bit 扩展帧设计
- DLC 32/64 协议帧
- Little-endian 线格式
- PDO / SDO 分层
- 周期通信诊断
- 总线异常恢复

</td>
</tr>
</table>

---

## 🧠 RTOS Matrix

| RTOS | Positioning | Kernel Focus | Status |
|:---|:---|:---|:---:|
| **FreeRTOS** | 主力实战 RTOS | Task / Queue / Semaphore / EventGroup / Notify / PendSV | `█████████░` |
| **RT-Thread** | 国产嵌入式生态 | Device Model / FinSH / Component / Driver Framework | `████████░░` |
| **CMSIS-RTOS2** | 抽象接口层 | Thread / Mutex / Semaphore / Message Queue | `███████░░░` |
| **Zephyr** | 现代 RTOS 方向 | Kconfig / DeviceTree / West / Driver Model | `██████░░░░` |
| **ThreadX** | 工业商业 RTOS | Thread / Memory Pool / Event Flags / Low Latency | `█████░░░░░` |
| **NuttX** | POSIX-like RTOS | File / VFS / Driver / Shell / POSIX API | `████░░░░░░` |
| **LiteOS** | IoT / MCU 生态 | Task / IPC / Low Power / IoT Stack | `███░░░░░░░` |
| **uC/OS** | 经典 RTOS | Deterministic Kernel / Semaphore / Mailbox | `███░░░░░░░` |

```txt
RTOS Understanding Path

Bare Metal
   ↓
Interrupt + State Machine
   ↓
Scheduler + Context Switch
   ↓
Task / IPC / Timer / Memory
   ↓
Driver Framework + Middleware
   ↓
System-Level Reliability Design
```

---

## 🌌 Communication Protocol Universe

<table>
<tr>
<td width="33%">

### Field Bus

- CAN
- CAN-FD
- CANopen
- EtherCAT
- Modbus RTU
- RS485
- LIN

</td>
<td width="33%">

### Board-Level Bus

- UART
- SPI
- QSPI
- OctoSPI
- I2C
- I2S
- SDIO

</td>
<td width="33%">

### System / Network

- TCP/IP
- UDP
- Ethernet
- MQTT
- USB CDC
- BLE Basic
- UWB Module Link

</td>
</tr>
</table>

```txt
┌──────────────────────── Protocol Design Principle ───────────────────────┐
│  Header │ Command │ Sequence │ Payload Length │ Payload │ CRC │ Tail       │
│                                                                         │
│  Focus: Extensible / Versioned / Diagnosable / Recoverable / Traceable   │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 🏭 Project System Map

### 🔋 PMS Power Management System

```txt
PMS Firmware Architecture
├─ Bootloader
│  ├─ Image Validation
│  ├─ Vector Table Check
│  ├─ CRC32 Verify
│  └─ App Jump
│
├─ Application Layer
│  ├─ canfd1Task     : BMS Data / Status Report
│  ├─ canfd2Task     : Master Control / OTA / Log Upload
│  ├─ sysStateTask   : ADC / Key / E-Stop / Watchdog
│  ├─ logTask        : Async Log Flush
│  └─ uartTask       : Panel Protocol Parser
│
├─ Driver Layer
│  ├─ ADC + DMA
│  ├─ FDCAN
│  ├─ Flash
│  ├─ PWM
│  └─ UART
│
└─ Reliability Layer
   ├─ Fault Manager
   ├─ Watchdog
   ├─ Boot Confirm
   └─ Rollback State Machine
```

### 🤖 EtherCAT + CAN-FD Gateway

```txt
EtherCAT Slave System
├─ STM32H743
├─ LAN9253 ESC
├─ SPI / QSPI / OctoSPI PDI Access
├─ SM0 / SM1 Mailbox for SDO
├─ SM2 / SM3 Process Data for PDO
├─ 1ms Control Cycle
├─ DWT Timing Measurement
└─ PDI Interrupt Jitter Diagnosis
```

### 🖐 Dexterous Hand CAN-FD Protocol

```txt
CAN-FD Protocol Design
├─ 29-bit Extended ID
├─ Device Identity
├─ Motion Control Frame
├─ Feedback Frame
├─ Diagnostic Frame
├─ Configuration Frame
├─ Little-endian Payload
└─ TLV Extension Area
```

---

## 🛠 Toolchain Arsenal

<p align="center">
  <img src="https://img.shields.io/badge/GCC%20ARM-020617?style=for-the-badge&logo=gnu&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/CMake-020617?style=for-the-badge&logo=cmake&logoColor=22d3ee" />
  <img src="https://img.shields.io/badge/Ninja-020617?style=for-the-badge&logo=ninja&logoColor=a78bfa" />
  <img src="https://img.shields.io/badge/Makefile-020617?style=for-the-badge&logo=gnu&logoColor=818cf8" />
  <img src="https://img.shields.io/badge/Bazel-020617?style=for-the-badge&logo=bazel&logoColor=22d3ee" />
  <img src="https://img.shields.io/badge/Docker-020617?style=for-the-badge&logo=docker&logoColor=38bdf8" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VSCode-020617?style=for-the-badge&logo=visualstudiocode&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/Cursor-020617?style=for-the-badge&logoColor=a78bfa" />
  <img src="https://img.shields.io/badge/Clangd-020617?style=for-the-badge&logo=llvm&logoColor=22d3ee" />
  <img src="https://img.shields.io/badge/GDB-020617?style=for-the-badge&logo=gnu&logoColor=818cf8" />
  <img src="https://img.shields.io/badge/OpenOCD-020617?style=for-the-badge&logoColor=38bdf8" />
  <img src="https://img.shields.io/badge/J--Link-020617?style=for-the-badge&logoColor=a78bfa" />
</p>

```txt
Local Embedded CI
├─ Toolchain        : arm-none-eabi-gcc
├─ Build System     : CMake / Ninja / Makefile
├─ Editor Backend   : clangd / compile_commands.json
├─ Format           : clang-format
├─ Hook             : lefthook
├─ Script Runner    : just / shell
├─ Debug            : J-Link GDB Server / OpenOCD
└─ Environment      : WSL2 / Docker / Linux Shell
```

---

## 🧪 Hardware Workbench

```txt
┌──────────────────────────────────────────────────────────────────────────────┐
│  DEBUG PROBE      │  J-Link  ·  ST-Link V3  ·  DAPLink                       │
│  MEASUREMENT      │  Oscilloscope  ·  Logic Analyzer  ·  Multimeter          │
│  TARGET BOARDS    │  STM32H743  ·  STM32F407  ·  STM32G474  ·  PY32           │
│  BUS DEBUG        │  CAN Analyzer  ·  UART Tool  ·  EtherCAT Diagnosis        │
│  LAB SKILLS       │  Soldering  ·  Timing Capture  ·  Waveform Analysis       │
└──────────────────────────────────────────────────────────────────────────────┘
```

> 我更喜欢用示波器、逻辑分析仪、Trace 和寄存器现场去确认问题，而不是只靠猜。

---

## 🧱 Embedded Reliability Stack

| Layer | Focus | Typical Design |
|:---|:---|:---|
| **Boot Layer** | 启动可靠性 | Vector Check / CRC / App Select / Rollback |
| **Runtime Layer** | 运行稳定性 | Watchdog / Stack Monitor / Fault Manager |
| **Communication Layer** | 通信可靠性 | Sequence / ACK / Timeout / CRC / Retry |
| **Storage Layer** | Flash 可靠性 | Parameter Mirror / Magic / Version / Length / CRC |
| **Debug Layer** | 可诊断性 | Log / Trace / Fault Context / Event Record |
| **Upgrade Layer** | OTA 安全性 | A/B Partition / Trial Boot / Confirm Flag |

```txt
Reliability is not a feature added at the end.
It is a system constraint designed from the first line of firmware.
```

---

## 📈 Learning Roadmap

| Stage | Direction | Status |
|:---:|:---|:---:|
| **01** | MCU 外设驱动 / 寄存器 / HAL / LL | ![done](https://img.shields.io/badge/DONE-22d3ee?style=flat-square&labelColor=020617) |
| **02** | FreeRTOS / 任务调度 / IPC / ISR | ![done](https://img.shields.io/badge/DONE-22d3ee?style=flat-square&labelColor=020617) |
| **03** | CAN-FD / EtherCAT / Modbus / UART 协议设计 | ![done](https://img.shields.io/badge/DONE-22d3ee?style=flat-square&labelColor=020617) |
| **04** | Bootloader / OTA / Flash / 回滚机制 | ![done](https://img.shields.io/badge/DONE-22d3ee?style=flat-square&labelColor=020617) |
| **05** | D-Cache / MPU / DMA 一致性 / Fault 诊断 | ![active](https://img.shields.io/badge/ACTIVE-a78bfa?style=flat-square&labelColor=020617) |
| **06** | FOC / BLDC / 电机控制基础 | ![active](https://img.shields.io/badge/ACTIVE-a78bfa?style=flat-square&labelColor=020617) |
| **07** | Embedded Linux BSP / Driver / Build System | ![next](https://img.shields.io/badge/NEXT-818cf8?style=flat-square&labelColor=020617) |
| **08** | ROS2 / 机器人底层控制 / 分布式系统 | ![plan](https://img.shields.io/badge/PLAN-64748b?style=flat-square&labelColor=020617) |

---

## 📊 GitHub Telemetry

<p align="center">
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=ParacosmYy&show_icons=true&theme=transparent&hide_border=true&title_color=38bdf8&icon_color=a78bfa&text_color=94a3b8&count_private=true&include_all_commits=true" />
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ParacosmYy&layout=compact&theme=transparent&hide_border=true&title_color=38bdf8&text_color=94a3b8&langs_count=10" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ParacosmYy&theme=transparent&hide_border=true&ring=a78bfa&fire=38bdf8&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=64748b" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ParacosmYy&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&margin-h=8&column=6" />
</p>

---

## 🧭 Engineering Creed

<div align="center">

```txt
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│   I do not only write firmware that runs.                                  │
│   I build firmware that can be traced, diagnosed, upgraded and recovered.   │
│                                                                            │
│   Trace First. Printf Later.                                                │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:312e81,50:0f172a,100:020617&height=120&section=footer" width="100%" />
</p>

