# Cloud-JAM L4

![](https://raw.githubusercontent.com/rushup/Cloud-JAM-L4/master/JAM-L4-TOP.jpg)

Cloud-JAM L4 is the product accelerator (production grade solution) of ST functional pack P-NUCLEO-AZURE1 that combines:

-  NUCLEO L476RG
-  NUCLEO SHIELD IKS01A2
-  NUCLEO SHIELD NFC01A1
-  NUCLEO SHIELD IDW01M1

At a firmware level the Cloud-Jam works the same way as those 4 hardware combined.

So any project or binary created for STM32L476RG microcontroller can run or be debugged on the Cloud- JAM.


# FAQ

**What's different between Cloud-JAM and Cloud-JAM L4?**

Cloud-JAM is based on an STM32F401RE, Cloud-JAM L4 on a STM32L476RG. You should check the datasheet of the microcontroller for detailed informations.

The main differences are:

|          | Cloud-JAM | Cloud-JAM L4|
|---------|-------------|-----------|
|Flash Memory| 512KB | 1MB|
|SRAM| 96KB | 128KB|
|Expansion connetor| I2C, UART, GPIOs | 4 GPIOs|
|USB cable provided| No | Yes |

