# hodea-stm32f3-vpkg
STM32F3 vendor package.

This repository repackages substantial support files from the chip vendor
in order to include them in own projects as *git submodule*.

It provides the following components:
- CMSIS files
- System View Description files (for use with debuggers)

## Use of Third Party Code
This repository repackages parts of the
[Embedded software for STM32F3 series](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-embedded-software/stm32cubef3.html)
and the
[STM32F3 System View Description](http://www.st.com/resource/en/svd/stm32f3_svd.zip).
Please see [ThirdPartyNotices.md](./ThirdPartyNotices.md) file regarding
the licensing.
