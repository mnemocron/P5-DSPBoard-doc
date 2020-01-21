# Fachbericht P5

---

### Abstract

In the area of HAM radio or hobby music a demand exists for an inexpensive and simple audio effect box.
This project aims to develop such an effect box focussing on good performance but at a low cost using the ARM Cortex-M4 series processor architecture because it offers floating point digital signal processing (DSP).
In the greater picture the board will be programmable through a user friendly computer software, thereby offering an attractive solution for consumers interessted in a signal processing device.
The device uses an STM32F412 microcontroller with a TLV320 stereo audio codec and features a USB port for power and programming as well as two 1 inch OLED displays, two rotary encoders and two push buttons and is capable of running on a rechargeable battery.
The board allows the manipulation of the audio signal using the CMSIS/DSP library, whereby a simple FIR filter is implemented for demonstration purposes.
As a result of validation measurements, the hardware has a THD_2 of 75.77dB and an ENOB of 11.23 bit.

**Keywords**

ARM Cortex-M4, CMSIS/DSP, Audio Effect Box, Digital Signal Processing

---

### Source Code

[github.com/mnemocron/P5-DSP-Board-mdk](https://github.com/mnemocron/P5-DSP-Board-mdk)


---

### License

Copyright (c) 2019 Simon Burkhardt, Mischa Studer

No license applies! You may not reuse the provided code in any form without permission.


