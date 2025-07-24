
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   ..  这里被注释了
   .. .. math::
   ..    :label: eq-long-formula2


计算机的性能指标
====================

**机器字长**：机器一次能操作的最大位数，等于CPU内部运算器的位数和通用寄存器的位数,通常说“某16位或者32位
机器”其中16、32就是说的机器字长，简称字长。字长是计算机进行一次整数运算（定点整数）所能处理的二进制数据的
位数。通常等于通用寄存器的位数或ALU的宽度，字长越长，数的表示范围就越大，计算精度越高

**存储字长**：一个存储单元中能存储的最大位数，等于MDR的位数

**指令字长**：指令字长取决于这指令的功能和格式，不同功能的指令，长度会有所不同


**CPU时钟周期时间**：机器内部主时钟脉冲信号的宽度，它是CPU工作的最小时钟单位，也就是一个时钟周期所需要消耗的时间
  
**主频（CPU时钟频率）**：机器内部主时钟的频率，即时钟周期的倒数。


  :math:`主频=\frac{1}{CPU时钟周期时间}`

  :math:`CPU时钟周期时间=\frac{1}{主频}`

也就是这两个互为相反数主频通常以Hz为单位，10Hz表示每秒10个时钟周期，1MHz表示每秒100W个时钟周期

CPI：指执行一条指令需要多少个时钟周期

IPS：没秒钟执行多少条指令

  :math:`IPS=\frac{主频}{CPI}`

CPU执行时间：指运行一个程序所需要花费的时间

  :math:`CPU执行时间 = 指令数 \times CPI \times CPU时钟周期时间 = \frac{指令数 \times CPI}{主频}` 

  :math:`时钟周期数 = 指令数 \times CPI`

  :math:`CPU执行时间 = 时钟周期数 \times CPU时钟周期时间 = \frac{时钟周期数}{主频}`

MIPS：每秒钟执行多少百万条指令

  :math:`MIPS=\frac{指令条数}{执行时间\times 10^6}=\frac{主频}{CPI\times 10^6}`