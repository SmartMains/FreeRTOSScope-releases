# FreeRTOSScope

A Windows tool for looking inside a running STM32 / FreeRTOS program over an ST-LINK probe.

**[Download the latest version](https://github.com/SmartMains/FreeRTOSScope-releases/releases/latest)** (Windows installer and the documents)

## What it does

- **Timing**: a timeline of tasks and interrupts from the SWO/ITM trace, CPU load per task, stack use, program counter profile.
- **Watch**: read variables, peripheral registers (SVD) and bit fields of the running target as graphs; write a new value without a compile or a flash.
- **RTT Terminal**: the text of the program through SEGGER RTT, read from RAM while the core runs, with a line to send back.
- **Terminal**: serial ports in ASCII, HEX, OCT or BIN, with a send line and a log to a file.
- **Sniffer**: two serial ports at once (the device line and the PC line) with protocol decoders: Modbus RTU / ASCII, NMEA 0183, SLIP, COBS, HDLC / PPP.
- **Incidents**: on a fault, the registers, the function, the file and the line, the stack of every task; a log of faults, resets and hangs for long runs.

## Documents

Every release carries the PDF documents: Kick Start Guide, Reference Manual, Product Description and What is new.

## Software update

The program can check this page for a newer version (Help, Software Update).

## Contact

SmartMains, [www.smart-mains.com](https://www.smart-mains.com)
