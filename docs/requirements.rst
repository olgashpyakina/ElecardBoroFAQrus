Технические требования
======================

Серверная часть
---------------

Поддерживаемые браузеры: 

* Chromium версия 51 и новее
* Google Chrome версия 51 и новее
* Mozilla Firefox версия 47 и новее

Для корректной работы убедитесь, что ваш браузер обновлен до последней версии.
Для нагруженных приложений:

.. csv-table::
   :header: "Минимальные требования", "Рекомендуемые требования"

   "Intel (R) Xeon (R) Processor E3-1276 v3", "Intel Xeon Processor E5-xxxx v3  x2"
   "16GB RAM", "32-64GB RAM"
   "1TB HDD Raid 10", "2TB HDD Raid 10 Hot Swap"
   "Linux 64bit CenOs 7.4 core ", "Linux 64bit CenOs 7.4 core "
   
Зонд
----
Для нагруженных приложений:

.. csv-table::
   :header: " ", "Только целостность доставки (TR 101 290 + ClockContinuity)", "Целостность доставки + замирание картинки + эскизы"
   
   "IPTV 200SD+140HD", "Intel(R) Xeon(R) CPU E3-1270 v5 @ 3.60GHz 32GB RAM", "dual CPU Intel® Xeon 8 Core processors E5-2620v4 32GB RAM"
   "HLS 50SD(3)+50HD(2)", "Intel(R) Xeon(R) CPU E3-1270 v5 @ 3.60GHz 32GB RAM", "dual CPU Intel® Xeon 8 Core processors E5-2620v4 32GB RAM"
   
Источники: UDP, RTP [1]_, HTTP, HLS, DVB, file(TS).
Транспорт: MPEG-2 TS (SPTS /MPTS).
Видео-кодеки: MPEG-2, AVC/H.264, HEVC/H.265.

**Системные требования:**

* Windows 7/8/8.1/10 32/64 bit, Server 2008/2012 32/64 bit
* Linux 32bit/64bit + glibc-2.11 (October 2009, Debian 6, Ubuntu 10.04, SLES 11, RHEL 6, CentOS 6) и выше.

**Рекомендуемая ОС:** CentOS 7.4

**Минимальные аппаратные требования:**
Процессоры с поддержкой SSE2 (Intel® Pentium 4 и выше, AMD® Opteron и Athlon 64 и выше).

.. [1] RTP over UDP (multicast) Поток должен отвечать спецификации RTP Payload Format for MPEG1/MPEG2 Video (rfc2250)

