# ESP-AT
[![Documentation Status](https://readthedocs.com/projects/espressif-esp-at/badge/?version=latest)](https://docs.espressif.com/projects/esp-at/en/latest/?badge=latest)

- [中文版](#esp-at-项目)

esp-at project was started and powered by Espressif Systems (@[espressif](https://github.com/espressif/)) as an official project, for the **ESP8266**, **ESP32**, **ESP32-C3**, and **ESP32-S2** Series SoCs provided for Windows, Linux, and macOS.  
It is now supported and maintained by Espressif esp-at team (@[esp-at](https://github.com/espressif/esp-at)).


esp-at is Free Software under a MIT license.
dfasdfasdfasdf
# Introduction
Espressif Wi-Fi and Bluetooth® chipsets are often used as add-on modules to seamlessly integrate wireless connectivity features into new and existing products.  
In an effort to facilitate this and cut down on engineering costs, Espressif Systems has developed a set of AT commands that can be used to interface with Espressif products.

"AT" means 'attention'. Each command string is prefixed with "AT", and a number of discrete commands can be concatenated after the "AT".

The AT command firmware allows for rapid integration by providing:

- In-built TCP/IP stack and data buffering
- Easy integration with resource-constrained host platforms
- Easy-to-parse command-response protocols
- Customized, user-defined AT commands

# Resources
- There are several guides for esp-at developers and users. These guides can be rendered in a number of formats, like HTML and PDF.  
  Documentation for the latest version: [https://docs.espressif.com/projects/esp-at/en/latest/index.html](https://docs.espressif.com/projects/esp-at/en/latest/index.html). This documentation is built from the [docs directory](https://github.com/espressif/esp-at/tree/master/docs) of this repository.

- [Check the Issues section on GitHub](https://github.com/espressif/esp-at/issues) if you find a bug or have a feature request. Please check existing Issues before opening a new one.

- The [esp-at forum](https://www.esp32.com/viewforum.php?f=42) is a place to ask questions and find community resources.

# Project Roadmap
1. The next version of ESP-AT firmware (v2.4.0.0) is planned to be released in March 2022. At present, only ESP32-C3 series firmware is planned to be released, and ESP32-C3 firmware would support Bluetooth LE 5.0.

2. ESP-AT Support Policy for ESP Chip Series

- ESP32-C3 Series
  - **Preferred recommended chip by ESP-AT**
  - Released version is recommended: [v2.3.0.0_esp32c3](https://github.com/espressif/esp-at/releases/tag/v2.3.0.0_esp32c3)

- ESP32 Series
  - Released version is recommended: [v2.2.0.0_esp32](https://github.com/espressif/esp-at/releases/tag/v2.2.0.0_esp32)
  - The next version of ESP-AT firmware (v2.3.0.0) for ESP32 is in preparatory stage, but no an estimated time of release.

- ESP8266 Series
  - **ESP32-C3 is recommended instead**
  - ESP-AT will not release the major version for ESP8266.
  - ESP-AT no longer adds new features to ESP8266.
  - [v2.2.1.0_esp8266](https://github.com/espressif/esp-at/releases/tag/v2.2.1.0_esp8266) is the last version of ESP-AT for ESP8266, corresponding to branch [release/v2.2.0.0_esp8266](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp8266), corresponding to documentation [https://docs.espressif.com/projects/esp-at/en/release-v2.2.0.0_esp8266](https://docs.espressif.com/projects/esp-at/en/release-v2.2.0.0_esp8266/).
  - ESP-AT will regularly update [release/v2.2.0.0_esp8266](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp8266) branch for ESP8266. Update includes vital bugfix and security repair.

- ESP32-S2 Series
  - **ESP32-C3 is recommended instead**
  - ESP-AT will not release the major version for ESP32-S2.
  - ESP-AT no longer adds new features to ESP32-S2.
  - [v2.1.0.0_esp32s2](https://github.com/espressif/esp-at/releases/tag/v2.1.0.0_esp32s2) is the last version of ESP-AT for ESP32-S2, corresponding to branch [release/v2.1.0.0_esp32s2](https://github.com/espressif/esp-at/tree/release/v2.1.0.0_esp32s2), corresponding to documentation [https://docs.espressif.com/projects/esp-at/en/release-v2.1.0.0_esp32s2](https://docs.espressif.com/projects/esp-at/en/release-v2.1.0.0_esp32s2/).
  - ESP-AT will regularly update [release/v2.2.0.0_esp32](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp32) branch for ESP32-S2. Update includes vital bugfix and security repair.

# ESP-AT 项目
esp-at 作为由 Espressif Systems (@[espressif](https://github.com/espressif/)) 发起和提供技术支持的官方项目，适用于 Windows、Linux、macOS 上的 **ESP8266**、**ESP32**、**ESP32-C3**、和 **ESP32-S2** 系列芯片。  
当前该项目由 Espressif esp-at 团队 (@[esp-at](https://github.com/espressif/esp-at)) 负责技术支持和维护。  

esp-at 是 MIT 许可证下的免费软件。

# 简介
乐鑫 Wi-Fi 和蓝牙芯片可以用作附加模块，完美集成在其他现有产品上，提供无线通讯功能。
为降低客户开发成本，乐鑫开发了一套 AT 指令集，方便客户简单快速地使用 AT 指令来控制芯片。

乐鑫提供的 AT 指令固件具有以下特色，利于芯片集成到应用中：

- 内置 TCP/IP 堆栈和数据缓冲
- 能便捷地集成到资源受限的主机平台中
- 主机对指令的回应易于解析
- 用户可自定义 AT 指令

# 资源
- 这里为开发者和用户提供了一些指南，这些指南可以以多种格式呈现，比如 HTML 和 PDF。  
  最新文档见：[https://docs.espressif.com/projects/esp-at/zh_CN/latest/index.html](https://docs.espressif.com/projects/esp-at/zh_CN/latest/index.html)。该文档是由本仓库 [docs 目录](https://github.com/espressif/esp-at/tree/master/docs) 自动编译构建的。

- 如果你有 bug 上报或者功能需求，可以在 [GitHub Issues](https://github.com/espressif/esp-at/issues) 里提交。请在提交前检索下是否有相同的 Issue。

- [esp-at 社区](https://www.esp32.com/viewforum.php?f=34) 可以用来询问问题或寻找一些社区资源。

# 项目路线图
1. 下一版本 ESP-AT 固件 (v2.4.0.0)，计划在 2022 年 3 月发布。当前仅计划发布 ESP32-C3 系列固件，ESP32-C3 固件将支持低功耗蓝牙 5.0。

2. ESP-AT 对不同芯片系列支持策略

- ESP32-C3 系列
  - **ESP-AT 首选推荐芯片**
  - 推荐使用发布版本：[v2.3.0.0_esp32c3](https://github.com/espressif/esp-at/releases/tag/v2.3.0.0_esp32c3)

- ESP32 系列
  - 推荐使用发布版本：[v2.2.0.0_esp32](https://github.com/espressif/esp-at/releases/tag/v2.2.0.0_esp32)
  - ESP32 下一版本 ESP-AT 固件 (v2.3.0.0) 在开发准备阶段，但暂无预计的发布时间

- ESP8266 系列
  - **推荐使用 ESP32-C3 芯片**
  - ESP-AT 不再为 ESP8266 添加新功能
  - ESP-AT 不再为 ESP8266 发布大版本
  - [v2.2.1.0_esp8266](https://github.com/espressif/esp-at/releases/tag/v2.2.1.0_esp8266) 是 ESP-AT 为 ESP8266 发布的最后一个版本，对应分支为 [release/v2.2.0.0_esp8266](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp8266)，对应文档为 [https://docs.espressif.com/projects/esp-at/zh_CN/release-v2.2.0.0_esp8266](https://docs.espressif.com/projects/esp-at/zh_CN/release-v2.2.0.0_esp8266/)
  - ESP-AT 将定期在 [release/v2.2.0.0_esp8266](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp8266) 分支为 ESP8266 进行重要 bug 修复，安全修补等更新

- ESP32-S2 系列
  - **推荐使用 ESP32-C3 芯片**
  - ESP-AT 不再为 ESP32-S2 添加新功能
  - ESP-AT 不再为 ESP32-S2 发布大版本
  - [v2.1.0.0_esp32s2](https://github.com/espressif/esp-at/releases/tag/v2.1.0.0_esp32s2) 是 ESP-AT 为 ESP32-S2 发布的最后一个版本，对应分支为 [release/v2.1.0.0_esp32s2](https://github.com/espressif/esp-at/tree/release/v2.1.0.0_esp32s2)，对应文档为 [https://docs.espressif.com/projects/esp-at/zh_CN/release-v2.1.0.0_esp32s2](https://docs.espressif.com/projects/esp-at/zh_CN/release-v2.1.0.0_esp32s2/)
  - ESP-AT 将定期在 [release/v2.2.0.0_esp32](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp32) 分支为 ESP32-S2 进行重要 bug 修复，安全修补等更新
