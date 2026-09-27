# STM32H7_PlayVideo
Bare-metal 30 fps full-screen video on STM32H743: SD card → async SDMMC IDMA → Cortex-M7 2× upscale → 32 MB SDRAM double buffer → LTDC 1024×600 @ 60 Hz, with a capacitive touch play/pause and seek bar. No RTOS, no GPU.
