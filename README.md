<!--
  ============================================================
   ParacosmYy / GS-Paracosm GitHub Profile README
   浅色二次元架构 · 嵌入式固件 · RTOS · OTA · 调试工具
  ============================================================
-->

<p align="center">
  <img loading="lazy" width="96%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/paracosm-light-architecture.svg" alt="浅色二次元嵌入式项目架构图" />
</p>

<p align="center">
  <a href="https://github.com/ParacosmYy?tab=followers"><img loading="lazy" src="https://img.shields.io/github/followers/ParacosmYy?style=for-the-badge&label=%E5%85%B3%E6%B3%A8&labelColor=FFF7FB&color=FF78B7" alt="GitHub 关注数" /></a>
  <img loading="lazy" src="https://komarev.com/ghpvc/?username=ParacosmYy&label=%E8%AE%BF%E5%AE%A2&color=58C9F1&style=for-the-badge" alt="主页访客数" />
  <img loading="lazy" src="https://img.shields.io/badge/%E6%96%B9%E5%90%91-MCU%20%2F%20RTOS%20%2F%20OTA-66DFAE?style=for-the-badge&labelColor=F6FFF9" alt="方向：MCU、RTOS、OTA" />
</p>

<p align="center">
  <img loading="lazy" width="31%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/anime-light-firmware-sticker.gif" alt="浅色二次元嵌入式工程师动图贴纸" />
  <img loading="lazy" width="45%" src="https://raw.githubusercontent.com/ParacosmYy/ParacosmYy/main/assets/anime-light-architecture-loop.gif" alt="浅色中文架构边界动图" />
</p>

<p align="center">
  <strong>GS / ParacosmYy</strong><br />
  <sub>浅色二次元外壳，嵌入式工程内核。关注 MCU、RTOS、OTA、调试工具和可迁移架构。</sub>
</p>

<p align="center">
  <a href="mailto:1264206065@qq.com">
    <img loading="lazy" src="https://img.shields.io/badge/QQ%E9%82%AE%E7%AE%B1-1264206065%40qq.com-FF78B7?style=for-the-badge&logo=tencentqq&logoColor=white" alt="QQ 邮箱 1264206065@qq.com" />
  </a>
  <a href="https://github.com/ParacosmYy">
    <img loading="lazy" src="https://img.shields.io/badge/GitHub-ParacosmYy-34385E?style=for-the-badge&logo=github&logoColor=white" alt="GitHub ParacosmYy" />
  </a>
</p>

---

## 项目轨道

我希望嵌入式项目不只停在“能跑”，而是继续向边界清楚、状态可追踪、验证可复现、迁移可控的方向推进。

`GS_Smart_car`：当前的 MCU 架构锚点。围绕 AURIX TC264D 智能车固件整理 App / Service / BSP / HAL / Target / Vendor 边界，让稳定业务层不要吞掉芯片和厂家 SDK 细节。

`GS_ETERNALCHIP`：OTA 可靠性轨道。关注 Bootloader、Flash 分区、镜像校验、升级状态机、异常恢复和错误镜像拒绝路径。

`GS_Thread`：RTOS 机制轨道。复刻 RT-Thread 关键路径，拆解调度器、IPC、对象容器、软件定时器、PendSV、SysTick 和 Cortex-M 上下文切换。

`GS_Tool`：调试工具轨道。使用 Python / PyQt6 / uv / GitHub Actions 做串口数据、协议解析、日志回放、打包验证和现场排障工具。

`GCC_Cmake_ARM`：构建现代化轨道。抽取 ARM GCC + CMake + Ninja 模板，让 Cortex-M 工程更容易脚本化、复现和接入 CI。

<p align="center">
  <a href="https://github.com/ParacosmYy/GS_Smart_car/tree/tc264-four-wheel-servo-camera-car"><img loading="lazy" src="https://img.shields.io/badge/GS__Smart__car-TC264D%20%E6%99%BA%E8%83%BD%E8%BD%A6-58C9F1?style=for-the-badge&labelColor=F5FCFF" alt="GS Smart car 仓库" /></a>
  <a href="https://github.com/ParacosmYy/GS_ETERNALCHIP/tree/OTA_Encrypted_Upgrade"><img loading="lazy" src="https://img.shields.io/badge/GS__ETERNALCHIP-OTA%20%E5%8D%87%E7%BA%A7-FF78B7?style=for-the-badge&labelColor=FFF7FB" alt="GS ETERNALCHIP OTA 仓库" /></a>
  <a href="https://github.com/ParacosmYy/GS_Thread"><img loading="lazy" src="https://img.shields.io/badge/GS__Thread-RTOS%20%E6%9C%BA%E5%88%B6-FFD66B?style=for-the-badge&labelColor=FFFDF1" alt="GS Thread 仓库" /></a>
  <a href="https://github.com/ParacosmYy/GS_Tool"><img loading="lazy" src="https://img.shields.io/badge/GS__Tool-%E8%B0%83%E8%AF%95%E4%B8%8A%E4%BD%8D%E6%9C%BA-66DFAE?style=for-the-badge&labelColor=F6FFF9" alt="GS Tool 仓库" /></a>
  <a href="https://github.com/ParacosmYy/GCC_Cmake_ARM"><img loading="lazy" src="https://img.shields.io/badge/GCC__Cmake__ARM-%E5%8F%AF%E5%A4%8D%E7%8E%B0%E6%9E%84%E5%BB%BA-A997FF?style=for-the-badge&labelColor=F7F5FF" alt="GCC Cmake ARM 仓库" /></a>
</p>

---

## 架构边界

我更喜欢把工程拆成能被解释清楚的层：应用层表达业务意图，服务层沉淀流程和状态机，HAL 层提供稳定契约，Target 层承接板级资源和移植代码，Vendor 层收敛芯片厂商细节。

这种边界看起来有点“保守”，但它很适合嵌入式：换 MCU、换板子、换 SDK 时，应该优先改 Target / Vendor / 工程配置，而不是让业务层跟着芯片细节一起漂移。

我在 README、架构图、验证命令和验收清单里也会尽量保持这种风格：能交付的东西，要能被后来的人复盘。

---

## 技术星群

<p align="center">
  <img loading="lazy" src="https://img.shields.io/badge/AURIX%20TC264D-%E5%BD%93%E5%89%8D%E4%B8%BB%E7%BA%BF-58C9F1?style=flat-square&labelColor=F5FCFF" alt="AURIX TC264D" />
  <img loading="lazy" src="https://img.shields.io/badge/STM32F411-Bootloader%20%2F%20OTA-FF78B7?style=flat-square&labelColor=FFF7FB" alt="STM32F411" />
  <img loading="lazy" src="https://img.shields.io/badge/Cortex--M-%E7%A7%BB%E6%A4%8D%E8%BE%B9%E7%95%8C-FFD66B?style=flat-square&labelColor=FFFDF1" alt="Cortex-M" />
  <img loading="lazy" src="https://img.shields.io/badge/C99-%E5%B5%8C%E5%85%A5%E5%BC%8F%E5%9B%BA%E4%BB%B6-66DFAE?style=flat-square&labelColor=F6FFF9" alt="C99 嵌入式固件" />
  <img loading="lazy" src="https://img.shields.io/badge/FreeRTOS-%E5%B7%A5%E7%A8%8B%E5%AE%9E%E8%B7%B5-A997FF?style=flat-square&labelColor=F7F5FF" alt="FreeRTOS" />
  <img loading="lazy" src="https://img.shields.io/badge/RT--Thread-%E6%9C%BA%E5%88%B6%E5%A4%8D%E5%88%BB-58C9F1?style=flat-square&labelColor=F5FCFF" alt="RT-Thread" />
  <img loading="lazy" src="https://img.shields.io/badge/ARM%20GCC-CMake%20%2F%20Ninja-FF78B7?style=flat-square&labelColor=FFF7FB" alt="ARM GCC CMake Ninja" />
  <img loading="lazy" src="https://img.shields.io/badge/Python-PyQt6%20%E5%B7%A5%E5%85%B7-FFD66B?style=flat-square&labelColor=FFFDF1" alt="Python PyQt6 工具" />
</p>

---

## 当前施工中

`RTOS 内核路径` → `OTA 失败矩阵` → `调试工具体验` → `MCU 可迁移边界` → `嵌入式 Linux / BSP 扩展`

接下来会继续把项目往“可审查、可验证、可维护”的方向推：硬件层负责什么，稳定层承诺什么，失败如何被发现，交付物如何被别人复现。

---

## 联系我

<p align="center">
  <a href="mailto:1264206065@qq.com">
    <img loading="lazy" src="https://img.shields.io/badge/QQ%E9%82%AE%E7%AE%B1-1264206065%40qq.com-FF78B7?style=for-the-badge&logo=tencentqq&logoColor=white" alt="QQ 邮箱 1264206065@qq.com" />
  </a>
  <a href="https://github.com/ParacosmYy">
    <img loading="lazy" src="https://img.shields.io/badge/GitHub-ParacosmYy-34385E?style=for-the-badge&logo=github&logoColor=white" alt="GitHub ParacosmYy" />
  </a>
</p>
