
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   ..  这里被注释了
   .. .. math::
   ..    :label: eq-long-formula2


数制和编码
====================

信息的二进制编码
-------------------------------

.. list-table:: 二进制整数部分的位次与位权
   :header-rows: 1
   :widths: 10 30

   * - 位次
     - 位权
   * - 0
     - :math:`2^0 = 1`
   * - 1
     - :math:`2^1 = 2`
   * - 2
     - :math:`2^2 = 4`
   * - 3
     - :math:`2^3 = 8`
   * - 4
     - :math:`2^4 = 16`
   * - 5
     - :math:`2^5 = 32`
   * - 6
     - :math:`2^6 = 64`
   * - 7
     - :math:`2^7 = 128`
   * - 8
     - :math:`2^8 = 256`
   * - 9
     - :math:`2^9 = 512`
   * - 10
     - :math:`2^{10} = 1024`
   * - 11
     - :math:`2^{11} = 2048`
   * - 12
     - :math:`2^{12} = 4096`
   * - 13
     - :math:`2^{13} = 8192`
   * - 14
     - :math:`2^{14} = 16384`
   * - 15
     - :math:`2^{15} = 32768`
   * - 16
     - :math:`2^{16} = 65536`

 
.. list-table:: 小数部分位次与位权
   :header-rows: 1
   :widths: 10 30

   * - 位次
     - 位权
   * - -1
     - :math:`2^{-1} = 0.5`
   * - -2
     - :math:`2^{-2} = 0.25`
   * - -3
     - :math:`2^{-3} = 0.125`
   * - -4
     - :math:`2^{-4} = 0.0625`
   * - -5
     - :math:`2^{-5} = 0.03125`
   * - -6
     - :math:`2^{-6} = 0.015625`
   * - -7
     - :math:`2^{-7} = 0.0078125`
   * - -8
     - :math:`2^{-8} = 0.00390625`
   * - -9
     - :math:`2^{-9} = 0.001953125`
   * - -10
     - :math:`2^{-10} = 0.0009765625`

.. tip::进制转换
    
    除权取余(从下往上),乘权取整(从上往下).有的十进制小数无法用二进制精确表示，如0.3

 
**拼凑法(就得用这个方法,死记快)**

  .. image:: ../images/image18.png
      :alt: 进制转化
      :width: 800px
      :align: center

真值和机器数
------------------------

  .. image:: ../images/image19.png
    :alt: 真值和机器数
    :width: 800px
    :align: center