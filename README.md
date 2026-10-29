TXS0108E Bidirectional Level-Shifter PMOD

A compact, open-source 8-channel bidirectional voltage level-translation board adopting the standard PMOD form factor. Built around the Texas Instruments TXS0108E, this board facilitates seamless logic level conversion without requiring a dedicated direction control pin.

Designed natively in KiCad, this module is specifically optimized to bridge custom RISC-V cores and open silicon test environments with standard 3.3V or 5V sensors and peripherals.

🚀 Features

Auto-Direction Sensing:No DIR pin required; automatically detects the direction of data flow.
Wide Voltage Range:
Port A (Low Voltage): 1.2V to 3.6V
Port B (High Voltage): 1.65V to 5.5V 

High-Speed Protocol Support: Compatible with push-pull (SPI, UART) and open-drain (I2C) communication protocols.

Standard PMOD Interface: 12-pin (2x6) standard PMOD header layout for plug-and-play compatibility with FPGA development boards and microcontroller testbeds.

Signal Integrity: Carefully routed traces with localized 100nF decoupling capacitors on both VCCA and VCCB rails to ensure stable switching at high frequencies.

