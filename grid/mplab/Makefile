# MPLAB IDE generated this makefile for use with GNU make.
# Project: blinky_grid.mcp
# Date: Fri Mar 25 09:12:36 2011

AS = MPASMWIN.exe
CC = 
LD = mplink.exe
AR = mplib.exe
RM = rm

blinky_grid.cof : blinky_grid.o uart.o set_led2.o
	$(CC) /p16LF1527 "C:\Program Files\Microchip\MPASM Suite\LKR\16F1823_g.lkr" "blinky_grid.o" "uart.o" "set_led2.o" /u_DEBUG /z__MPLAB_BUILD=1 /z__MPLAB_DEBUG=1 /o"blinky_grid.cof" /M"blinky_grid.map" /W

blinky_grid.o : blinky_grid.asm C:/Program\ Files/Microchip/MPASM\ Suite/P16F1823.INC
	$(AS) /q /p16LF1527 "blinky_grid.asm" /l"blinky_grid.lst" /e"blinky_grid.err" /o"blinky_grid.o" /d__DEBUG=1

uart.o : uart.asm C:/Program\ Files/Microchip/MPASM\ Suite/P16F1823.INC
	$(AS) /q /p16LF1527 "uart.asm" /l"uart.lst" /e"uart.err" /o"uart.o" /d__DEBUG=1

set_led2.o : set_led2.asm C:/Program\ Files/Microchip/MPASM\ Suite/P16F1823.INC
	$(AS) /q /p16LF1527 "set_led2.asm" /l"set_led2.lst" /e"set_led2.err" /o"set_led2.o" /d__DEBUG=1

clean : 
	$(CC) "blinky_grid.o" "blinky_grid.err" "blinky_grid.lst" "uart.o" "uart.err" "uart.lst" "set_led2.o" "set_led2.err" "set_led2.lst" "blinky_grid.cof" "blinky_grid.hex"

