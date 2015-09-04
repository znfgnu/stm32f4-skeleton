# stm32f4-skeleton
## Requirements
This **STM43F4 skeleton project** needs:
* [STM32F4 Standard Peripheral Library](https://github.com/rowol/stm32_discovery_arm_gcc/tree/master/STM32F4-Discovery_FW_V1.1.0)
* [ST-Link](https://github.com/texane/stlink.git)
* gcc-arm-none-eabi (installed from repository)

## Quick-start guide
1. Clone STM32F4 SPL repository.
2. Clone ST-Link repository and build it.
3. Install *gcc-arm-none-eabi* with your package manager.
4. Clone this repository.
5. Edit *Makefile*: set *STLINK* and *STM_COMMON* variables according to your configuration.
6. Run: *make*.
7. Plug in your STM32F4 development board.
8. Run: *make burn*.
9. You should see orange LED blinking.

Based on: https://github.com/rowol/stm32_discovery_arm_gcc
