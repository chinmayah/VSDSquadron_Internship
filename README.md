# VSDSquadron_Internship
This repository is created for VSD Internship 

 ### VSDSquadron Mini RISC-V Development Board

[Click here for board link](https://www.vlsisystemdesign.com/vsdsquadronmini/)

![Risc-vMini](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/5abdd70f-31f9-4e6b-a6c5-8c940b11ec56)



BOARD SPECIFICATIONS:

| Tech specs   |   |    |
|------------|------------|------------|
| *Board* | Name     | VSDSquadron Mini    |
|      | SKU    | VSDSQM    |
| *Microcontroller*    | CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set    |     |
| *USB connector* | USB 2.0 Type-C    |     |
| *Pins*     | Built-in LED Pin     | 1X onboard user led (PD6)     |
|      | Digital I/O pins     | 15     |
|      | Analog I/O pins     | 10-bit ADC, PD0-PD7, PA1, PA2, PC4     |
|      | PWM pins     | 14X     |
|      | External interrupts     | 	8 external interrupt edge detectors, but it only maps one external interrupt to 18 I/O ports     |
| *Communication*     | USART     | 	1x, PD6(RX), PD5(TX)     |
|      | I2C     | 1x, PC1(SDA), PC2(SCL)    |
|      | SPI     | 1x, PC5(SCK), PC1(NSS), PC6(MOSI), PC7(MISO)     |
|      | Programmer/debugger     | Onboard RISC-V programmer/debugger, USB to TTL serial port support     |
| *Power*     | I/O voltage     | 3.3 V    |
|      | Input voltage (nominal)     | 5 V    |
|      | Source Current per I/O Pin    | 8 mA     |
|      | Sink Current per I/O Pin     | 8 mA     |
| *Clock speed*     | Processor    | 24 MHz     |
| *Memory*     | SRAM     | 2kb onchip volatile sram,16kb external program memory     |
   



__The first online meet was held on 16th of Feb 2024 @6PM__

<details>
    <summary> TASK 1 </summary>
 
1) Install Yosys 

2) Install iverilog 

3) Install gtkwave

## CLONING RISC-V GNU TOOLCHAIN

 ### To install git 
 
$ sudo apt install git-all 

  Error:Unable to locate pakage git-all
  
__Troubleshooting__ 

$ sudo apt-get dist-upgrade

$ sudo apt-get update
![Screenshot from 2024-02-19 16-06-16](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/07706c53-5123-4126-a1f8-ea5448adc4f4)


![Screenshot from 2024-02-19 16-06-37](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/43b3e543-8826-4840-9286-ff6474ffc215)


## INSTALLING YOSYS, IVERILOG & GTKWAVE.

### 1.YOSYS 


$ git clone https://github.com/YosysHQ/yosys.git

![Screenshot from 2024-02-20 12-33-54](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/1b9156d3-88ce-4a3c-bdf0-69ea403b740b)

$ cd yosys 

$ sudo apt install make

$ sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev
![Screenshot from 2024-02-20 12-43-31](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/ad38b9fa-399a-4cdb-abb0-83abd6a783e9)


$ make config-gcc

$ make 

$ sudo make install
![Screenshot from 2024-02-20 17-26-25](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/45972e3a-bbfa-4db9-be61-d8510db7ded2)



### 2.iVerilog
installing iVerilog

$ sudo apt-get install iverilog

![Screenshot from 2024-02-20 17-29-12](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/4ef45917-9ec3-489e-b440-3da444b049eb)



### 3.GTkWave
installing GTkWave

$ sudo apt update

$ sudo apt-get install gtkwave 

![Screenshot from 2024-02-20 17-33-49](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/0b42d407-ab39-4cd6-ab3c-651c0da70422)
![Screenshot from 2024-02-20 17-34-15](https://github.com/chinmayah/VSDSquadron_Internship/assets/85050733/7688b206-d86d-4419-841d-b6d06e3ae642)

</details>
