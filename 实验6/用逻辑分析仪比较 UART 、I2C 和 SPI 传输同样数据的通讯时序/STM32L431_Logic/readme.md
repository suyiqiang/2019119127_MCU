
# 实验六-用逻辑分析仪比较 UART 、I2C 和 SPI 传输同样数据的通讯时序

    实验六：使用小熊派 IoT实验套件和STM32CubeMX，用逻辑分析仪分析和比较 Uart 、I2C 和 SPI 传输同样数据的通讯时序。

## 接线

    小熊派      USART2      I2C     SPI
    PA2         TX          
    PA3         RX
    PB6                     SCL
    PB7                     SDA
    PA1                             SCK
    PA7                             MOSI

# 参考资料

bing:

    关键词: 用逻辑分析仪 USART 的时序
    逻辑分析仪的简单使用介绍（附带i2c、串口、spi数据分析）https://cloud.tencent.com/developer/article/1862094

    关键词: 软件模拟SPI
    软件模拟SPI接口程序代码（4种模式）https://blog.csdn.net/zwj695535100/article/details/107303648/

    关键词: HAL库 微秒延时
    STM32CubeMX | STM32 HAL库方式的微秒延时函数https://blog.csdn.net/qq153471503/article/details/102930097
