NucleoF401-COIDE-blink
======================

Template project for a STM32 Nucleo-F401RE board in Coocox CoIDE. 

CoIDE 1.7.7 does not support officialy STM32F401RE from Nucleo-F401RE so I created this tamplate project that is a modified version of the STM32F401RC (that is supported in CoIDE).

Based on the post from
http://developer.mbed.org/forum/platform-34-ST-Nucleo-F401RE-community/topic/4855/

Ram and flash size corrected in Coide linker config.
Clock is configured to external HSE 8MHz from STLINK.
USART used to comunicate using STLINK Virtual COM Port.

Flash Latency set in 2 wait states.
Flash prefetch enable.
