
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   ..  这里被注释了
   .. .. math::
   ..    :label: eq-long-formula2


计算机的性能指标
====================

   .. image:: ../images/image14.png
      :alt: 主存储器
      :width: 600px
      :align: center

   把这个2的多少次方背下来

   .. image:: ../images/image15.png
      :alt: 主存储器
      :width: 600px
      :align: center
   
CPU的性能指标(重点)
--------------------------


   .. image:: ../images/image16.png
      :alt: 主存储器
      :width: 600px
      :align: center



   **主频反映的值是每秒钟有会多少个数字脉冲，也就是每秒钟会出现多少个时钟周期**

   假设,主频10Hz就是每一秒中有10个脉冲信号

   有时候整个 **程序的耗时** 也会被称为 **CPU执行时间**

   CPI:就是每一条指令的执行需要多少个时钟周期

   .. math::

      这个程序 所有的时钟周期数=CPI * 所有指令的条数
   
   .. math::

      整个程序的耗时(CPU执行时间)= 所有的时钟周期数/主频

   
   数据通路带宽:数据总线一次所能并行传送信息的位数(各硬件部件通过数据总线传输数据)

   如果一个计算机的数据通路带宽为8bit那么处理一个16bit的数据需要2次数据传输，每次只能传输8bit

   .. image:: ../images/image17.png
      :alt: 主存储器
      :width: 800px
      :align: center

   注意这个图中的常用数量单位