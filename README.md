# Electronic level

Project of two-dimensional electronic level based on [LSM303D acelerometer](http://www.st.com/content/ccc/resource/technical/document/datasheet/1c/9e/71/05/4e/b7/4d/d1/DM00057547.pdf/files/DM00057547.pdf/jcr:content/translations/en.DM00057547.pdf), 
Nokia5110 screen, [NUCLEO-F103RB board](http://www.st.com/en/evaluation-tools/nucleo-f103rb.html) and 
[STM32 Standard Peripheral Library](http://www.st.com/en/embedded-software/stm32-standard-peripheral-libraries.html?querycriteria=productId=LN1939).

Used peripherals:
* I2C - communication with accelerometer(`lsm303d.h`, `lsm303d.c`)
* SPI - communication with the screen(`lcd.h`, `lcd.c`)
* ADC and DMA - measurement of the external light
* Timers and PWM - control of the screen brightness (proportional to the light)
* UART - communication with PC

![alt text](https://github.com/KarolloS/Electronic-level/blob/master/level.png)

Project was done as a part of Control Systems Course at Warsaw University of Technology.
