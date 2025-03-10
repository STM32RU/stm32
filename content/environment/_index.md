---
title: Рабочая среда
geekdocCollapseSection: true
---

Источник: [@stm32std](https://t.me/stm32std)

## IDE

- [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) (Win, Linux, Mac).  Программа для инициализации периферии и генерации первичного кода в графическом режиме. Разработана компанией ST специально для stm32. Генерирует код основаный на библиотеке HAL, либо LL. Очень удобный, полезный и бесплатный инструмент. Генерирует код для различных IDE представленных ниже, а так же Makefile для поклонников "хардкора" 😉

- [Atollic TrueSTUDIO](https://atollic.com/truestudio/) (Win, Linux). Среда основанная на Eclipse. Выкуплена компанией ST и распространяется бесплатно. С недавнего времени поддержка прекращена в пользу STM32CubeIDE. Тем не менее, лично я всё ещё пользуюсь TrueSTUDIO.

- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) (Win, Linux, Mac). Собственная разработка компании ST объединяющая в себе TrueSTUDIO и STM32CubeMX. 

- [Keil MDK](http://www.keil.com/) (Win). Популярная среди разработчиков среда. Является бесплатной отчасти. Если написаный код не превышает 30Кб, то бесплатно, если больше, то надо покупать лицензию.

- [SW4STM32](https://www.st.com/en/development-tools/sw4stm32.html) (Win, Linux, Mac). Эта среда так же основана на Eclipse, и похожа на TrueSTUDIO. Думаю в дальнейшем Alexey или ещё кто-нибудь расскажет о ней больше.

- [IAR](https://www.iar.com/iar-embedded-workbench/) (Win). Простая (в плане количества надстроек) и мощная среда, с собственным компилятором, но при этом не самым удобным редактором кода. Очень быстрая сборка и отладка.

- [CLion](/environment/setup-clion-for-stm32/) (Win, Linux, Mac) бесплатный пробный период на 30 дней.

## Утилиты

- [STM32CubeProg](https://www.st.com/en/development-tools/stm32cubeprog.html) (Win, Linux, Mac)
- [ST-LINK utility](https://www.st.com/en/development-tools/stsw-link004.html) (Win)
- ST MCU Finder - приложение для подбора микроконтроллера производства ST по параметрам. [PC](https://www.st.com/content/st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-utilities/st-mcu-finder-pc.html), [Android](https://play.google.com/store/apps/details?id=fr.appsolute.st), [iOS](https://apps.apple.com/us/app/st-mcu-finder/id864903472).

## Help для IDE

### CubeIDE

{{< expand "Добавление своей папки в проект" >}}
Источник: [@stm32std](https://t.me/stm32std/14889)

![1](environment/1.jpg)
{{< /expand >}}


### AtollicTrueStudio

- [Установка TrueStudio и STM32CubeMX](https://istarik.ru/blog/stm32/106.html)
- [Atollic_TrueSTUDIO_for_STM32_User_Guide](/environment/Atollic_TrueSTUDIO_for_STM32_User_Guide.pdf)
- [Atollic_Serial_wire_viewer_realtime_tracing](/environment/Atollic_Serial_wire_viewer_realtime_tracing.pdf)
- [Загрузка без Debug](https://www.youtube.com/watch?v=VBzLFedDxAA)
- [Добавление ссылки на файл](https://www.youtube.com/watch?v=0SzzZe7-ccs)
- [Проект на CMSIS в TrueStudio](http://easyelectronics.ru/cozdanie-minimalnogo-proekta-pod-stm32-v-atollic-true-studio.html)
