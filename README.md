# **Controlling a Servo motor using TIM and ADC**
The project combines analog input and generating pwm using timers, you can check the code [HERE!](https://github.com/YoustinaZak/ADC_Servo/blob/main/Core/Src/main.c)

## **Electronic Components**
1) LCD Display
2) Servomotor       (_signal wire: pin A6_)
3) Potentiometer    (_o/p pin: pin A7_)
4) STM32 microcontroller

## **Important numbers**
- To calculate input voltage: (ADC reading/4095) * vref
