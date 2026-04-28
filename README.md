<p align="center">
  <samp>
    <b>GS-Paracosm</b> · 嵌入式系统工程师 · 西安<br><br>
    MCU 高可靠实时控制 / 工业通信 / 电机控制 / 机器人底层<br><br>
    <i>代码只是起点，波形和 trace 才是真相。</i>
  </samp>
</p>

---

## 关于我

- 深耕 **MCU 实时控制**与**工业通信**，正在向 **Embedded Linux** 与**机器人底层**扩展。
- 习惯用 **Makefile + GCC + Shell** 构建烧录流，也在尝试 **Bazel** 统一嵌入式构建。
- 调试风格：遇到问题先看 **Trace** 和 **示波器**，而不是盲目加打印。
- 欢迎交流：底层控制、异构系统 (MCU + MPU)、工业总线、机器人运动控制。

---

## 开发工具链 · Toolchain

```text
构建系统    :  Makefile  /  CMake  /  Bazel（学习中）
编译器      :  GCC ARM Embedded  /  Clangd
烧录与调试  :  OpenOCD  /  ST-Link CLI  /  J-Link  /  Shell 脚本自动化
容器与 CI   :  Docker  /  WSL2  /  Git hooks
编辑器      :  VSCode  /  Cursor  +  clangd
```

---

## 技术栈 · Tech Stack

### MCU 与核心
`STM32H7` `STM32F4` `STM32G4` `ARM Cortex-M` `RISC-V（了解）`

### RTOS 与内核

| 系统 | 定位 | 熟练度 |
|:---|:---|:---:|
| FreeRTOS | 主力实战 | ████████░░ |
| RT-Thread | 国产生态 | ████████░░ |
| CMSIS-RTOS2 | 抽象接口层 | ███████░░░ |
| Zephyr | 现代化方向 | █████░░░░░ |
| ThreadX | 工业/商业 | ████░░░░░░ |
| NuttX | 类 POSIX | ████░░░░░░ |

### 工业总线 · Industrial Bus

| 层级 | 协议/接口 |
|:---|:---|
| **物理层** | UART · SPI · I2C · RS485 · CAN · CAN-FD · Ethernet · USB · OctoSPI |
| **协议层** | CANopen · Modbus RTU · EtherCAT Slave · IGH EtherCAT Master · UWB Transparent Bridge |
| **工程点** | Frame Design · PDO/SDO Mapping · Bus Timing · FIFO/Ring Buffer · DMA Transport · Protocol Parser · CRC · Fault Recovery |

---

## 核心能力 · Core Expertise

### 🔍 MCU 崩溃调试与 Trace 分析

> 比起在代码里插 `printf`，我更倾向于用 **Trace** 还原崩溃现场。

- **HardFault / MemManage / BusFault / UsageFault** 定位与分析
- **CoreSight Trace**：DWT 周期计数与性能测量、ITM 软件跟踪、ETM 指令流追踪
- **Segger RTT** 与 **SystemView**：实时日志与任务调度可视化
- **栈回溯（Stack Backtrace）**：通过 LR 与 SP 重建调用链
- **Post-mortem 分析**：从故障寄存器、栈内存、Core Dump 中还原现场

### ⚡ 可靠性与固件升级

- **Bootloader / OTA**：A/B 分区、非活跃分区烧录、CRC16/32 双重校验、回滚确认机制
- **故障保护框架**：独立看门狗（IWDG）+ 窗口看门狗（WWDG）+ 多级故障降级策略

### 🌐 工业通信与协议栈

- **EtherCAT 从站**：LAN9253 PDI 中断优化、SM 邮箱与 PDO 周期数据映射、1ms 控制周期、DWT 时序诊断
- **CAN-FD 自定义协议**：29-bit 扩展 ID 设备寻址、DLC 32 综合控制帧、Little-endian 线格式

---

## 项目实验室 · Projects

| 项目 | 关键词 | 简介 |
|:---|:---|:---|
| **PMS 电源管理系统** | `STM32H7` `OTA` `A/B分区` `ADC+DMA` | A/B 双分区 OTA 架构，非活跃分区烧录，CRC 校验与回滚确认，多通道 DMA 采样，多级故障保护。 |
| **EtherCAT → CAN-FD 网关** | `LAN9253` `EtherCAT Slave` `CAN-FD` `1ms周期` | EtherCAT 从站协议栈移植，SDO 邮箱与 PDO 周期映射，PDI 中断抖动诊断，DWT 精确时序测量。 |
| **灵巧手 CAN-FD 协议** | `CAN-FD` `29-bit ID` `DLC32` `Little-endian` | 面向灵巧手的设备寻址与控制帧规范，身份配置协议，线格式优化。 |
| **嵌入式 CI 模板** | `Makefile` `CMake` `Docker` `clangd` | 统一构建流模板，跨平台工具链（WSL2/Docker），格式化与 CI 流水线。 |

---

## 硬件工作台 · Hardware

| 类别 | 装备 |
|:---|:---|
| **调试器** | J-Link ULTRA+ · ST-Link V3 · DAPLink |
| **测量仪器** | Siglent SDS1104X-E 示波器 · Kingst LA2016 逻辑分析仪 |
| **目标板** | STM32H743 · STM32F407 · STM32G474 · Raspberry Pi 4 |
| **实验技能** | SMD/QFN 焊接 · 电源完整性分析 · 信号完整性基础 |

---

## 学习路线 · Roadmap

```
MCU 固件与外设驱动  →  RTOS 内核与驱动框架  →  工业通信协议
                                                          ↓
                机器人控制系统  ←  Embedded Linux BSP  ←  Bootloader/OTA/可靠性
                                                          ↑
                                      电机控制 (FOC/BLDC)
```

| 阶段 | 方向 | 状态 |
|:---:|:---|:---:|
| Stage 01 | STM32 外设驱动 & 裸机 | ✅ |
| Stage 02 | FreeRTOS / RT-Thread 内核深入 | ✅ |
| Stage 03 | CAN-FD · EtherCAT 工业总线 | ✅ |
| Stage 04 | Bootloader · OTA · A/B 分区 | ✅ |
| Stage 05 | **PMSM FOC · BLDC 电机控制** | 🔄 当前 |
| Stage 06 | **Linux BSP · Kernel Driver** | 📅 计划 |
| Stage 07 | **ROS · 机器人中间件** | 📅 计划 |

---

<p align="center">
  <samp>
    <a href="https://github.com/ParacosmYy">GitHub</a> · 
    欢迎交流合作
  </samp>
</p>
