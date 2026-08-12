# Mason Naftaliyev

I hold a B.Sc. in Electrical and Computer Engineering from Ben Gurion
University of the Negev, where I focused on Semiconductors and VLSI.
I am a junior engineer looking for a hardware engineering role.
My main work so far is an FPGA project I carried out end to end,
from architecture and RTL through verification to board bring up.

## FPGA_project

[![Data pipe flow diagram](https://raw.githubusercontent.com/naftalimason/FPGA_project/main/report/UARTburst_AHBsingle_DataPipeFlow.drawio.svg)](https://github.com/naftalimason/FPGA_project)

Full duplex RGB image exchange between a PC and an Artix 7 FPGA over
UART, my main project. All the RTL is SystemVerilog: a custom UART PHY
and MAC at 8 Mbaud, an AHB-Lite image path, an APB register path, and a
280 MHz PLL clock with CDC handling. A burst protocol and RTS/CTS flow
control move a 256x256 image 22x faster than the naive link, lossless
under stall. Verified with a class based testbench under Verilator and
brought up on hardware. Full story in
[FPGA_project](https://github.com/naftalimason/FPGA_project).

## Other work

[academic-projects](https://github.com/naftalimason/academic-projects)
holds analog circuits and intro to VLSI coursework, a CMOS inverter in
Cadence Virtuoso and a Verilog-A SAR ADC.
