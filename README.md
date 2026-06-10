<!--
  ============================================================
   ParacosmYy / GS-Paracosm GitHub Profile README
   方向：中文优先 · 嵌入式工程 · 清爽专业
  ============================================================
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:E0F7FF,35:EDE9FE,70:F8FAFC,100:DCFCE7&text=GS-PARACOSM&fontColor=1E293B&fontSize=48&fontAlignY=35&animation=fadeIn&fontAlign=50" />
</p>

<h2 align="center">你好，我是 GS-Paracosm</h2>

<p align="center">
  <b>嵌入式固件 / 实时系统 / 工业通信 / 机器人底层控制</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/方向-MCU%20固件与实时控制-3B82F6?style=for-the-badge&labelColor=EFF6FF&color=3B82F6" />
  <img src="https://img.shields.io/badge/关注-Bootloader%20%2F%20OTA%20%2F%20故障诊断-8B5CF6?style=for-the-badge&labelColor=F5F3FF&color=8B5CF6" />
  <img src="https://img.shields.io/badge/习惯-先看现场再写结论-06B6D4?style=for-the-badge&labelColor=ECFEFF&color=06B6D4" />
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy?tab=followers"><img src="https://img.shields.io/github/followers/ParacosmYy?style=social" /></a>
  <img src="https://komarev.com/ghpvc/?username=ParacosmYy&label=Profile%20Views&color=60a5fa&style=flat" />
</p>

---

## 关于我

我主要做 **MCU 固件开发** 和 **嵌入式底层工程**，关注从芯片外设、实时调度、通信链路到系统可维护性的完整闭环。

比起只把功能跑起来，我更在意这些问题：

- 中断、DMA、缓存、总线和任务调度是否真的稳定；
- 通信协议是否便于调试、扩展和定位问题；
- Bootloader / OTA 是否具备校验、回滚、状态恢复能力；
- 现场问题能不能通过日志、Trace、寄存器现场和工具链快速复现；
- 工程结构是否适合长期维护，而不是越写越乱。

---

## 当前坐标

```yaml
姓名 / ID: GS-Paracosm
所在城市: 西安，中国
主要方向: MCU 固件、RTOS、工业通信、机器人底层控制
正在扩展: Embedded Linux、CMake 工程化、自动化构建
工程偏好: 可诊断、可维护、可升级、可回滚
常用方法: 示波器 / 逻辑分析仪 / Trace / GDB / addr2line
```

---

## 技术栈

<table>
<tr>
<td width="50%" valign="top">

### MCU 与外设

- STM32 / Cortex-M4 / Cortex-M7
- CMSIS / HAL / LL
- NVIC / DMA / TIM / PWM / ADC
- Flash / VTOR / MPU / Cache
- 看门狗、低功耗、启动流程

</td>
<td width="50%" valign="top">

### 实时系统

- FreeRTOS / RT-Thread / CMSIS-RTOS2
- Task / Queue / Semaphore / EventGroup
- ISR 与任务同步
- PendSV / SysTick / 调度分析
- 栈溢出、死锁、优先级反转排查

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 工业通信

- CAN / CAN-FD
- Modbus-RTU
- UART / SPI / I2C
- 协议帧设计与链路诊断
- 设备状态机与异常恢复

</td>
<td width="50%" valign="top">

### 构建与调试

- C / C++ / CMake / Make
- GCC-ARM / clangd / VSCode
- J-Link / OpenOCD / GDB
- Docker / 本地 CI
- HardFault / BusFault / 现场还原

</td>
</tr>
</table>

---

## 我更关注的工程块

<table>
<tr>
<td width="33%" valign="top">

### Bootloader / OTA

- Bootloader + 双 APP 分区
- 固件 CRC / 签名校验
- 升级状态机
- 失败回滚与断电恢复

</td>
<td width="33%" valign="top">

### 故障诊断

- HardFault / BusFault 分析
- 栈、寄存器、调用现场保留
- map / elf / addr2line 定位
- 现场复现与最小化验证

</td>
<td width="33%" valign="top">

### 机器人底层控制

- MCU 与上位机协同
- CAN-FD 设备通信
- 实时控制链路
- 电机、传感器与状态反馈

</td>
</tr>
</table>

---

## 代码与项目习惯

- 目录结构尽量清楚：BSP、Driver、Service、App 分层明确；
- 接口优先考虑长期维护，不把业务逻辑塞进中断；
- 关键状态必须可观测，关键错误必须可追踪；
- 能用工具确认的问题，不只靠猜；
- 能自动化的构建、检查、烧录和验证，尽量自动化。

---

## GitHub 数据

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ParacosmYy&show_icons=true&theme=transparent&hide_border=true&locale=cn" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ParacosmYy&layout=compact&theme=transparent&hide_border=true&locale=cn" />
</p>

---

## 欢迎交流

如果你也关注 **嵌入式固件、工业通信、实时系统、机器人底层控制、嵌入式工程化**，可以通过 GitHub 和我交流。

<p align="center">
  <a href="https://github.com/ParacosmYy">
    <img src="https://img.shields.io/badge/GitHub-ParacosmYy-2563EB?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <sub><b>少一点玄学，多一点现场；少一点堆砌，多一点工程闭环。</b></sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:DCFCE7,35:F8FAFC,70:EDE9FE,100:E0F7FF" width="100%" />
</p>
