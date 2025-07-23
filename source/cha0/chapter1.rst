
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   ..  这里被注释了
   .. .. math::
   ..    :label: eq-long-formula2


各个硬件的工作原理
=======================

主存储器
-----------------------

    .. image:: ../images/image4.png
        :alt: 主存储器
        :width: 600px
        :align: center

    读数据的访问的过程是，CUP给MAR一个地址，然后 MAR把地址发给主存储器，主存储器把给地址中的数据返回到MAR,此时CPU就可以通过数据总线在MDR读取带数据了

    写数据的过程是，CPU会先通过控制总线告诉主存储器要进行写操作，CPU把要写的数据写到MDR中，把要写入数据的地址给到MAR,然后MAR把地址发到主存储器，最后主存储器获取到MAR中的数据然后写到该内存

    .. image:: ../images/image5.png
        :alt: 主存储器
        :width: 400px
        :align: center

    - 存储单元: 每个存储单元存放一串二进制代码
    - 存储字(word): 存储单元中二进制代码的组合
    - 存储字长: 存储单元中二进制代码的位数
    - 存储元: 即存储二进制的电子元件，每个存储元可存1 bit



运算器的基本组成
-----------------------

    .. image:: ../images/image6.png
        :alt: 主存储器
        :width: 600px
        :align: center
    
    
    .. image:: ../images/image7.png
        :alt: 主存储器
        :width: 600px
        :align: center
    
    .. image:: ../images/image8.png
        :alt: 主存储器
        :width: 600px
        :align: center
    
    .. image:: ../images/image9.png
        :alt: 主存储器
        :width: 600px
        :align: center
    