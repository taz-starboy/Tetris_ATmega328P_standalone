# Tetris_ATmega328P_standalone
![](https://img.shields.io/badge/version-1.0.0-green)

<p>**Introduction**</p>
<p>this project helps you install a light version on a pcb.</p>
<p>It explains how to start with a virgin ATmega328P:</p>
1. How to burn the bootloader on the ATmega328P
2. Burn the tetris program
3. Set due connectors to play it on a pcb

## Burn the bootloader on the ATmega328P

<p align="center">
    <img src="burn_bootloader_connections_image.png" width="50%" />
</p>

## Burn the Tetris program
<p>Get the Tetris program from this link:</p>
[arduino-uno--TETRIS](https://github.com/taz-starboy/arduino-uno--TETRIS)

## Set due connectors to play it on a pcb
|   Arduino Uno Pin  | ATmega328P Pin |
| ----------- | ----------- |
| Reset      | 1       |
| RX <- 0   | 2        |
| TX -> 1    | 3       |
| 2   | 4        |
| 3     | 5       |
| 4 (PWM)   | 6        |
| 5V      | 7       |
| GND   | 8        |
| CRYSTAL      | 9       |
| CRYSTAL   | 10        |
| 5 (PWM)      | 11      |
| 6 (PWM)  | 12        |
| 7    | 13       |
| 8   | 14        |
| 9 (PWM)     | 15       |
| 10 (PWM)   | 16        |
| 11 (PWM)      | 17       |
| 12   | 18        |
| 13      | 19       |
| 5V   | 20        |
| 5V    | 21       |
| GND   | 22        |
|A0     | 23       |
| A1   | 24        |
| A2      | 25       |
| A3  | 26       |
| A4     | 27       |
| A5 | 28        |