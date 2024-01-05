## freertos-stm32-f303ze
Hands-on FreeRTOS on STM32 teaching board NUCLEO-F303ZE

----

### Outline

**(0) Warm-Up**
- 0-1 *main_01.c*: Multithreading with 2 LED light bulbs

**(1) Producer-Consumer Problem**
- 1-1 *main_02.c*: With a 1-byte buffer using 2 LED light bulbs 
- 1-2 *main_03.c*: With a 5-byte buffer using 2 LED light bulbs 

**(2) Readers-Writers Problem**
- 2-1 *main_04_failed.c*: Used 3 LED light bulbs, 2 for the readers and 1 for the writer. Failed for a deadlock between the readers.
- 2-2 *main_05.c*: Used 3 LED light bulbs, 2 for the readers and 1 for the writer. Solved the preceding deadlock by a semaphore.