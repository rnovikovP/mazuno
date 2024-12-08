# mazuno
Arduino uno random maze game
- random maze generator
- two kind of bonuces
- exit when all bonucess are collect
- limit of steps

# using 
- U8G2 library for SH1107 I2C display 128X128
- 2 position xy joystic
- buzzer


![image](https://github.com/user-attachments/assets/04ce9575-4d35-4b29-b32e-e3587c632e11)





![image](https://github.com/user-attachments/assets/f047de2f-d14e-4f2b-9969-4a1671edc035)


# wires

display |  | UNO   
--- | --- | --- 
SDA | <--> | A4   
SCL | <--> | A5
GND | <--> | GND
VCC | <--> | VCC



Joystic | | UNO   
--- | --- | --- 
VRY | <--> | A0
VRX | <--> | A1     
VCC | <--> | VCC
GND | <--> | GND


Buzzer | | UNO  
--- | --- | --- 
GND | <--> | GND
VCC | <--> | D2


# Libs

[Maze alghorithm](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Simple_algorithms)

[U8G2](https://github.com/olikraus/u8g2)


# issues
## U8G2
- [Screen contrast](https://github.com/olikraus/u8g2/issues/501](https://github.com/olikraus/u8g2/issues/501#issuecomment-366543758}

## UNO R3
- max 13x11 blocks due memory limit
