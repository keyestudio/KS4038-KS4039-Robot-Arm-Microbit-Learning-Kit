# KS4038(KS4039) Keyestudio Robot Arm Microbit Learning Kit

![img](./media/wps1.png)

## 1.Description

Micro:bit is a microcontroller of ARM structure designed by the BBC. To be specific, it is only half size of a credit card, onboard with a Bluetooth, an accelerometer, an electronic compass, three buttons, a 5 x 5 LED dot matrix as well as a microphone and is mainly used for programming education of teenagers.
To make Micro:bit more accessible to learn, our team specially developed this robot arm Micro:bit learning kit. It is a STEM education robot arm dedicated to DIY production, programming learning, parent-child entertainment as well as educational training. For instance, we are able to leverage the Micro:bit mainboard and two joystick modules to control the rotation angles of four servos as a way to realize the robot arm to pick up or drop objects in different positions.
For your convenience, tutorials of MakeCode graphical programming and MicroPython language programming are contained in this kit, each of which boasts Micro:bit basic projects and Micro:bit robot arm projects, making it easy for enthusiasts of different ages to master.

## 2. Kit

KS4038 contains Micro:bit mainboard, but KS4039 doesn't contain it.

| #    | Components                             | QTY  | Picture                                                      |
| ---- | -------------------------------------- | ---- | ------------------------------------------------------------ |
| 1    | Micro:bit Mainboard+Official Color Box | 1    | ![img](./media/wps2.jpg)                                     |
| 2    | Micro:bit 16-channel Servo Shield      | 1    | ![img](./media/wps3.png)                                     |
| 3    | Acrylic Board                          | 1    | ![image-20251121110138565](./media/image-20251121110138565.png) |
| 4    | Acrylic Handle                         | 1    | ![img](./media/wps4.jpg)                                     |
| 5    | MeArm ABS Cylindrical Holder           | 1    | ![img](./media/wps5.jpg)                                     |
| 6    | 180° Servo                             | 3    | ![image-20251121110225840](./media/image-20251121110225840.png) |
| 7    | 180° Servo (Metal Gear)                | 1    | ![img](./media/wps6.jpg)                                     |
| 8    | Keyestudio Joystick Module             | 2    | ![image-20251121110256134](./media/image-20251121110256134.png) |
| 9    | 3D PS2 Joystick Cap                    | 2    | ![image-20251121110310038](./media/image-20251121110310038.png) |
| 10   | Cross Screwdriver                      | 1    | ![img](./media/wps7.png)                                     |
| 11   | Wrench                                 | 1    | ![img](./media/wps8.jpg)                                     |
| 12   | M3*6MM Round Head Screws               | 12   | ![img](./media/wps9.png)                                     |
| 13   | M3*10MM Round Head Screws              | 22   | ![img](./media/wps10.png)                                    |
| 14   | M3*14MM Flat Head Screws               | 2    | ![image-20251121110757608](./media/image-20251121110757608.png) |
| 15   | M3*12MM Round Head Screws              | 12   | ![image-20251121110816281](./media/image-20251121110816281.png) |
| 16   | M3*24+6MM Copper Pillar                | 4    | ![img](./media/wps11.png)                                    |
| 17   | M3*6MM+6MM Copper Pillar               | 10   | ![image-20251121110854462](./media/image-20251121110854462.png) |
| 18   | M3 Hex Nuts                            | 22   | ![img](./media/wps12.png)                                    |
| 19   | M3 Hexagon Self-locking Nuts           | 24   | ![image-20251121110922406](./media/image-20251121110922406.png) |
| 20   | M2x5MM Phillips Self-tapping Screws    | 10   | ![image-20251121110935390](./media/image-20251121110935390.png) |
| 21   | M3 304 Gasket                          | 10   | ![image-20251121110956103](./media/image-20251121110956103.png) |
| 22   | M2x8MM Phillips Self-tapping Screws    | 2    | ![img](./media/wps13.png)                                    |
| 23   | M3*16MM Flat Head Screws               | 2    | ![image-20251121111019598](./media/image-20251121111019598.png) |
| 24   | 200MM M-F DuPont Wire                  | 4    | ![img](./media/wps14.png)                                    |
| 25   | Alligator Clip to DuPont Wire          | 8    | ![img](./media/wps15.jpg)                                    |
| 26   | 3*100MM Tie                            | 7    | ![image-20251121111051437](./media/image-20251121111051437.png) |
| 27   | 6AA Battery Holder                     | 1    | ![img](./media/wps16.jpg)                                    |
| 28   | USB Cable                              | 1    | ![img](./media/wps17.jpg)                                    |
| 29   | Slotted Screwdriver                    | 1    | ![img](./media/wps18.jpg)                                    |

## 3. Features

1. Detailed installation methods  
2. Detailed debugging method of Micro:bit  
3. Strong expansibility: Boast Micro:bit servo shield and pins, and other sensors and modules can be extended.  
4. Multiple controls : Joystick control and mobile phone APP BT control (Apple and Android phones/Tablets)
5. Learning basic programming: MakeCode graphical programming and MicroPython language programming

## 4. Parameters
Working voltage: DC 5V
Power supply: Micro USB interface: DC 5V
Green terminal post: DC 4.5V-28V
Maximum output current: 1.5A
Maximum power consumption: 32W
Bluetooth remote distance: About 30- 50m (measured) (It is best to use it in an open area with no distracting devices around)

## 5.Keyestudio Micro：bit 16-channel Servo Shield

![](./media/eebc85c465703051749dd80641346e44507dafe8d7385e9e6173d8932f13c457.jpg)

### 5.1. Introduction

We always fail to drive several motors by Micro:bit control board in DIY experiment. To tell the truth, the output voltage of Micro:bit control board is DC 3.3V while servo should be driven by DC 5V. Also, the drive current of this board is low, and the controlled IO ports are limit when driving multiple servos. 
With this in mind, we specially design this Keyestudio Micro:bit 16-channel servo shield. It mainly adopts a PCA9685PW chip, which enables to communicate with Micro:bit control board for I2C. This shield includes 16 IO ports, making it convenient to connect servos and control 16 servos angle. We expand each control terminal to G, V (5V) and S and use 3pin headers with a spacing of 2.54mm as interfaces. 
When it comes to power supply, we can use Micro USB interface to input DC 5V voltage, or use two green wiring terminals to input DC 4.5V-28V voltage.
More importantly, it adopts a golden finger interface to bring out some control terminals on the Micro:bit control board and 3.3V voltage output terminals, which is convenient for you to connect sensors and modules to the Micro:bit.

***\*Note: The normal no-load current of servo is about 220mA, and the maximum affordable current of Micro USB is 2A. So if you power this board via Micro USB, the board is unable to drive 16 servos simultaneously.\**** 

### 5.2. Parameter

I2C input, control 16-channel PWM output, capable to control 16-channel servos.
Control chip: PCA9685PW
Power supply: Micro USB Port: DC 5V; Green Terminals: DC 4.5V-28V
Frequency: 40-1000Hz
Dimension:  63-43-12mm
Weight: 18.6g

### 5.3. Schematic Diagram

![wps19](./media/wps19.jpg)
