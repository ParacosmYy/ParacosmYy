<!--
  ============================================================
   ParacosmYy / GS-Paracosm GitHub Profile README
   Embedded Firmware · RTOS · Bootloader · Debug Tooling
  ============================================================
-->

<p align="center">
  <img loading="lazy" width="94%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/profile-hero-v3.svg" alt="GS-Paracosm embedded firmware profile banner for MCU, RTOS, OTA, and debug tooling" />
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy?tab=followers"><img loading="lazy" src="https://img.shields.io/github/followers/ParacosmYy?style=for-the-badge&label=FOLLOW&labelColor=EFF6FF&color=60A5FA" alt="GitHub followers" /></a>
  <img loading="lazy" src="https://komarev.com/ghpvc/?username=ParacosmYy&label=PROFILE%20VIEWS&color=A78BFA&style=for-the-badge" alt="Profile views" />
  <img loading="lazy" src="https://img.shields.io/badge/FOCUS-MCU%20%2F%20RTOS%20%2F%20OTA-2DD4BF?style=for-the-badge&labelColor=F0FDFA" alt="Focus: MCU, RTOS, OTA" />
</p>

<p align="center">
  <strong>面向机器人与嵌入式系统的固件开发者</strong><br />
  <sub>MCU / RTOS / Bootloader / Secure OTA / ARM GCC + CMake / Embedded Debug Tooling</sub>
</p>

<p align="center">
  <a href="mailto:1264206065@qq.com">
    <img loading="lazy" src="https://img.shields.io/badge/EMAIL-1264206065%40qq.com-2563EB?style=for-the-badge&logo=tencentqq&logoColor=white" alt="Email 1264206065@qq.com" />
  </a>
  <a href="https://github.com/ParacosmYy">
    <img loading="lazy" src="https://img.shields.io/badge/GitHub-ParacosmYy-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub ParacosmYy" />
  </a>
</p>

---

## First Signal

我关注的是把嵌入式项目从“能跑”推进到“边界清楚、可验证、可迁移、可交付”。

| 维度 | 当前证据 |
|---|---|
| 固件架构 | `GS_Smart_car` 将 AURIX TC264D 智能车代码收敛到 App / Service / BSP / HAL / Target / Vendor 边界 |
| 升级可靠性 | `GS_ETERNALCHIP` 的 OTA 分支覆盖 Bootloader、Flash 分区、镜像校验、状态机与恢复路径 |
| 内核理解 | `GS_Thread` 复刻 RT-Thread 关键路径，聚焦调度器、IPC、对象容器、定时器和 Cortex-M 移植 |
| 工程交付 | `GS_Tool` 以 Python / PyQt6 / uv / GitHub Actions 做嵌入式调试上位机和质量门禁 |
| 构建现代化 | `GCC_Cmake_ARM` 抽取 ARM GCC + CMake + Ninja 的可复现构建模板 |

---

## Featured Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParacosmYy/GS_Smart_car/tree/tc264-four-wheel-servo-camera-car"><b>GS_Smart_car</b></a><br />
      <sub><b>AURIX TC264D 智能车固件架构</b></sub><br />
      <sub>四轮舵机镜头车工程。将视觉、传感、控制、BSP、HAL、Target 与 Vendor 分层，业务层不直接包含芯片或厂家 SDK 头文件。</sub><br />
      <sub>Evidence: C99 · TC264D · SEEKFREE SDK · iLLD · event scheduler · target port boundary</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParacosmYy/GS_ETERNALCHIP/tree/OTA_Encrypted_Upgrade"><b>GS_ETERNALCHIP / OTA_Encrypted_Upgrade</b></a><br />
      <sub><b>STM32F411 加密 OTA 升级链路</b></sub><br />
      <sub>围绕 Bootloader / APP 协作、Flash 分区、镜像校验、升级状态机和异常恢复整理可靠升级流程。</sub><br />
      <sub>Evidence: STM32F411 · FreeRTOS · OTA/IAP · Flash partition · verify / rollback checklist</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParacosmYy/GS_Thread"><b>GS_Thread</b></a><br />
      <sub><b>类 RT-Thread 内核复刻</b></sub><br />
      <sub>把线程调度、对象管理、IPC、软件定时器和 Cortex-M PendSV / SysTick 移植拆成可阅读、可验证、可复盘的内核工程。</sub><br />
      <sub>Evidence: C · Scheduler · IPC · Object container · Cortex-M port</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParacosmYy/GS_Tool"><b>GS_Tool / EmbedDebug</b></a><br />
      <sub><b>嵌入式调试上位机</b></sub><br />
      <sub>面向串口、多源数据、协议解析、日志回放和现场排障的 Python/PyQt6 工具链，配套 uv scripts、CI、lint、测试和打包命令。</sub><br />
      <sub>Evidence: Python 3.10+ · PyQt6 · uv · PyInstaller · GitHub Actions · smoke tests</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParacosmYy/GS_watch/tree/feature/boot_loader"><b>GS_watch / feature_boot_loader</b></a><br />
      <sub><b>STM32F411 IAP Bootloader</b></sub><br />
      <sub>维护上电初始化、APP 合法性检查、Flash 布局、升级入口和 APP 安全跳转，为后续手表 APP 与 OTA 打底。</sub><br />
      <sub>Evidence: STM32F411 · Keil / ARMCC · Flash layout · app jump · boot boundary</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParacosmYy/GCC_Cmake_ARM"><b>GCC_Cmake_ARM</b></a><br />
      <sub><b>ARM GCC + CMake 构建模板</b></sub><br />
      <sub>将传统 IDE 工程迁移到可脚本化、可复现、可 CI 集成的 Cortex-M 构建体系。</sub><br />
      <sub>Evidence: CMake · Ninja · ARM GCC · linker script · reusable toolchain config</sub>
    </td>
  </tr>
</table>

---

## Engineering Proof

- **边界意识**：稳定业务层只面对 facade / HAL 契约，MCU、板级资源和 Vendor 细节收敛到 Target 或项目配置层。
- **可靠性意识**：升级链路不只写 Flash，还明确镜像校验、状态机、断电恢复、回滚和错误镜像拒绝路径。
- **内核机制**：围绕 Cortex-M 异常返回、PendSV、SysTick、临界区、就绪表和对象容器理解 RTOS 关键路径。
- **交付纪律**：工具类项目以 `uv run ...` 暴露启动、测试、lint、打包和验证命令，并接入 GitHub Actions。
- **文档习惯**：README 不只放口号，尽量给出架构图、目录边界、验证命令、验收清单和维护边界。

---

## Stack Snapshot

| Layer | Focus |
|---|---|
| MCU / SoC | AURIX TC264D, STM32F411, ARM Cortex-M, future embedded Linux / BSP expansion |
| Firmware | C99, Embedded C, Bootloader, IAP / OTA, Flash layout, interrupt and scheduler boundary |
| RTOS / Kernel | FreeRTOS, RT-Thread mechanisms, scheduler, IPC, timer, Cortex-M context switch |
| Build / CI | ARM GCC, CMake, Ninja, Keil / ARMCC interop, uv, GitHub Actions |
| Debug Tooling | UART, TCP/UDP loopback, protocol parsing, logs, replay, PyQt6 desktop tooling |
| Extra | Python, TeX / mathematical modeling, documentation and engineering review workflows |

<p align="center">
  <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/tech-stack-map-v3.svg" alt="Embedded technical stack map covering MCU, RTOS, OTA, build tooling, debug tools, and modeling" />
</p>

---

## Project Map

<p align="center">
  <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/project-matrix-v3.svg" alt="Firmware evidence project map: GS_Smart_car, GS_ETERNALCHIP, GS_Thread, GS_Tool, GS_watch, and GCC_Cmake_ARM" />
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy/GS_ETERNALCHIP/tree/OTA_Encrypted_Upgrade">
    <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/eternalchip-branches.svg" alt="GS_ETERNALCHIP branch map for OTA, bootloader, RTOS, and embedded experiments" />
  </a>
</p>

---

## Now

| Track | Current work |
|---|---|
| RTOS | Continue reading and rebuilding RT-Thread kernel primitives in `GS_Thread` |
| OTA | Turn Bootloader / APP / Flash / metadata into a clearer verification story |
| Tooling | Keep tightening `GS_Tool` around CI, UI smoke tests, packaging, and field debugging workflows |
| Portability | Keep MCU-specific work localized to target/vendor/project-config layers |

<p align="center">
  <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/advanced-tech-roadmap-v3.svg" alt="Advanced embedded roadmap covering RTOS, build systems, OTA, debug tooling, and embedded Linux expansion" />
</p>

---

## Activity

<p align="center">
  <img loading="lazy" width="88%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/github-metrics.svg" alt="GitHub contribution metrics for GS-Paracosm" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/output/github-contribution-grid-snake-ocean.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/output/github-contribution-grid-snake-ocean.svg" />
    <img loading="lazy" width="88%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/output/github-contribution-grid-snake-ocean.svg" alt="GitHub contribution graph animation" />
  </picture>
</p>

---

## Code Principles

<p align="center">
  <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/code-principles-v3.svg" alt="Code principles: simple boundary, explicit state, testable loop, and portable target layer" />
</p>

---

## Contact

<p align="center">
  <a href="mailto:1264206065@qq.com">
    <img loading="lazy" src="https://img.shields.io/badge/EMAIL-1264206065%40qq.com-2563EB?style=for-the-badge&logo=tencentqq&logoColor=white" alt="Email 1264206065@qq.com" />
  </a>
  <a href="https://github.com/ParacosmYy">
    <img loading="lazy" src="https://img.shields.io/badge/GitHub-ParacosmYy-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub ParacosmYy" />
  </a>
</p>

<p align="center">
  <img loading="lazy" width="100%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/profile-footer.svg" alt="GS-Paracosm footer wave" />
</p>
