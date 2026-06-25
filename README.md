# STM32-Core-SDK

## 📌 Overview
**STM32-Core-SDK** is a clean, lightweight, and highly organized collection of STM32 MCU platform files (Headers, Startup codes, and Linker scripts). It has been carefully restructured and debloated to serve as the foundational SDK for the **PowerStorm IDE**, ensuring fast automated downloads and clean project builds.

## 🚀 Features
* **Debloated Structure:** Unnecessary junk files, heavy examples, and redundant docs have been removed for faster IDE integration.
* **Auto-Download Ready:** Structured specifically to work seamlessly with dependency resolvers and automated build systems.
* **Multi-Family Support:** Organized directories for various STM32 series (e.g., STM32F0, STM32F4, STM32H7, etc.).

## ⚖️ Legal Disclaimer & Copyright
*This project is an independent effort to organize existing files for better tooling integration and is not officially affiliated with STMicroelectronics.*

* **Original Authors:** All core device headers, CMSIS files, and hardware abstraction layer (HAL) codes are the intellectual property of **STMicroelectronics** and **ARM Ltd.**
* **License:** These files are redistributed under the **Apache License, Version 2.0**. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.
* **Modifications:** The original files have not been logically altered; however, the directory structure has been reorganized and unnecessary files have been removed to optimize download size.
* Please refer to the `LICENSE.md` file included in this repository for full licensing details. 
* This repository is provided **"AS-IS"**, without any warranties of any kind.

## ⚙️ How it works with PowerStorm IDE
PowerStorm's `DependencyResolver` automatically fetches the specific MCU family folder from this SDK when a new project is created or built, eliminating the need for manual SDK management.
