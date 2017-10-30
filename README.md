STM32
=====

A repo for my various smaller [STM32 MCU](http://www.st.com/en/microcontrollers/stm32-32-bit-arm-cortex-mcus.html) projects.

 

**Index**

-   [*BlinkLightsCommandLine*](BlinkLightsCommandLine/README.md): Written for the [STM32F411 development board](http://www.st.com/en/microcontrollers/stm32f411.html?querycriteria=productId=LN1877), this example simply blinks the onboard LEDs.  Although a simple program, its importance is that it shows how to compile and debug entirely on the command line using GCC and GDB.  
-   *OnboardAudioOutput*: Written for the [STM32F411 development board](http://www.st.com/en/microcontrollers/stm32f411.html?querycriteria=productId=LN1877), this example outputs a stereo, 16 bit sine wave tone from the [CS43L22 onboard DAC](https://www.cirrus.com/products/cs43l22/).  For clarity of how the board works, no HAL, Standard Peripheral or any other API is used.
-   *SystickInterruptCommandLine*: Written for the [STM32F411 development board](http://www.st.com/en/microcontrollers/stm32f411.html?querycriteria=productId=LN1877), this example shows how to configure the systick register and use the systick interrupt.

