# AN5418-added-15V

This basically is the [AN5418 example](https://www.st.com/resource/en/application_note/an5418-how-to-build-a-simple-usbpd-sink-application-with-stm32cubemx-stmicroelectronics.pdf) for [X-NUCLEO-USBPDM1](https://www.st.com/en/evaluation-tools/x-nucleo-usbpdm1.html) -- (the [X-NUCLEO-SNK1M1](https://www.st.com/en/evaluation-tools/x-nucleo-snk1m1.html) should be suitable replacement) where added possibility to pick differnt config then default then 5V/500mA. There is implemented simple decision logic to pick the right one. The changes are applied in CubeMX (added configuration should be easy) and [usbpd_dpm_user.c](USBPD/Target/usbpd_dpm_user.c) -- see changes there.

May be useful when "stepping first step out of example".
