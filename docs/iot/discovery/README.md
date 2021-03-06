# [Discovery](https://rust-embedded.github.io/bookshelf/discovery/index.html)

### [简介](简介.md)
### [1 背景](1背景.md)
### [2 硬件及知识要求](2硬件及知识要求.md)
### [3 建立开发环境](3建立开发环境.md)
### [4 会会我们硬件](4会会我们硬件.md)
### [5 LED轮盘](5LED轮盘.md)
### [6 HelloWorld](6HelloWorld.md)
### [7 寄存器](7寄存器.md)
### [8 再解LED](8再解LED.md)
### [9 时钟和计时器](9时钟和计时器.md)
### [10 串行通信](10串行通信.md)
### [11 USART](11USART.md)
### [12 蓝牙设置](12蓝牙设置.md)
### [13 基于蓝牙上串口的传输](13基于蓝牙上串口的传输.md)
### [14 I2C](14I2C.md)
### [15 LED开发指南](15LED开发指南.md)
### [16 punch-o-meter](16punch-o-meter.md)
### [17 还有哪些需要你去探索](17还有哪些需要你去探索.md)

## 探索之旅

>通过[Rust](https://www.rust-lang.org/en-US/)发现微控制器的世界！

本书是基于微控制器的嵌入式系统的入门课程，它使用Rust作为教学语言而不是通常的C / C ++。

##  范围

将涵盖以下主题（最终，我希望）：

-如何编写，构建，刷新和调试“嵌入式”（Rust）程序。

-微控制器中常见的功能（“外设”）：数字输入和输出，脉冲宽度调制（PWM），模数转换器（ADC），通用通信协议，如串行，I2C和SPI等。

-多任务概念：协作与抢占式多任务处理，中断，调度程序等。

-控制系统概念：传感器，校准，数字滤波器，执行器，开环控制，闭环控制等。

## 途径

-初学者友好。以前不需要使用微控制器或嵌入式系统。

-实践性高。大量练习将理论付诸实践。你将在这里完成大部分工作。

-工具为中心。我们将充分利用工具来简化开发。使用GDB做真实debug和日志记录会一开始就被讲解。在这里不会使用LED作为调试机制。

## 非目标

这本书的范围超出了什么范围：

-做Rust教学。这个话题已经有很多材料了。我们将专注于微控制器和嵌入式系统。

-作为关于电路理论或电子学的综合文本。我们将只介绍了解某些设备如何工作所需的最低要求。

-覆盖Rust开发者的那种低级别的细节。我们不会讨论链接器脚本，引导过程或如何将这两者粘合到最低限度工作的Rust程序中。

此外，我不打算将此材料移植到其他开发板; 本书将专门使用STM32F3DISCOVERY开发板。

## 报告问题

本书的来源是在[这个库中](https://github.com/rust-embedded/discovery)。如果您遇到任何拼写错误或代码问题，请在[问题跟踪器](https://github.com/rust-embedded/discovery/issues)上报告。

由...赞助


非常感谢[ integer 32](https://integer32.com)赞助我参与本书！请给他们很多工作（他们做Rust咨询！）所以他们别无选择，只能雇用更多的Rustaceans <3。