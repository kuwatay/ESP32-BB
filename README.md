
# ESP32-BB

## 1. Introduction

**ESP32-BB** (Bearbone) is yet another ESP-32 based development board. 
For the programming of the board, an *extended 7-pin FTDI adapter* is required.

## 2. Schematic

![Schematic] (ESP32-schematic.png)

## 3. Board layout

![Board Layout] (ESP32-board.png)

## 4. BOM

|     Name   |          Parts                    |   Value                 |
|  :-------: | :-------------------------------: | :---------------------: |
|     U1     |  3.3V Low voltage drop Regulator  | LM1117-3.3              | 
|     U2     |  ESP-WROOM-32                     | -                       | 
|  LED1,LED2 |  LED1 (Green)  LED2(RED)          | (1608 size)             | 
|     J1     |  2.1mm power Jack                 | Power in                | 
|     J2     |  7 pin                            | L-angle connector       | 
|   J3,J4    |  10Pin x 2 receptacle             | pin header is ok        | 
|  SW1,SW2   |  Tactile Switch                   | Alps SKHH or equivalent | 
|   Q1,Q2    |  NPN-TR                           | (2SC2712)               | 
|   R1,R3    |  Carbon Register                  | 10K Ohm 1/10W(1608)     | 
|   R7,R8    |  Carbon Register                  | 1K Ohm 1/10W(1608)      | 
| R9,R10,R11 |  Carbon Register                  | 10K Ohm 1/10W(1608)     | 
|   R12,R13  |  Carbon Register                  | 1K Ohm 1/10W(1608)      | 
|     C2     |  Multilayer Ceramic Capacitor     | 1nF / 10V  (2012)       |
|     C6     |  Electrolytic  Capacitor          | 100uF / 10V or better   |
|     C7     |  Electrolytic  Capacitor          | 10uF / 10V or better    |
|     C8     |  Multilayer Ceramic  Capacitor    | 0.1uF / 10V (1608)      |

## EOF