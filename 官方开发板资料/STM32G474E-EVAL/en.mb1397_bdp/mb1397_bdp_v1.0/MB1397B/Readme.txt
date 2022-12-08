MB1397A-03-RC1:
1. sheet 4: Text "From STLINK V3E MCO (25MHz) for interposer", 25MHz changed to 8MHz
2. sheet 13: Text "OpAmp1" changed to "OpAmp4"; "Comp4" changed to "Comp6"
3. sheet 16: swapping Net "MC2_Ain" and "MC2_Cin"
4. SB25 closed both for MC config and Normal board
5. Remove R26 for MC config, PC8 as TIM8_CH3
6. add a black hat for B3, add a JOYSTICK BLUE HAT for B1
7. solder R143, R146 on board for extension connectors testing

MB1397B-01-RC1:
1. CN19 pin 7/8/13/14 net name VBUS1 changed to VBUS
2. PD2 as RS485_DIR: add SB123 on U6 pin 112 and SB17 changed to OFF
3. NRST connected to U40.P3 (PA5 changed to PA6)
4. R194,R196,R199,R204,R206 and R208 changed to 47R
5. database updated: SW7, U40, U38, U39; U36, U22, D1, T1, T9, T10, H3, H4
6. CN17 and CN19 footprint will add 2 alignment hole,  BOM warning for remove CN17 pin7.
7. footprint MOS_POWERFLAT_3P3X3P3_P065 pin 5-8 for solder mask and paste mask profile is same as top layer
8. U3 STTS751-0WB3F replace with STTS751-0DP3F with different footprint
9. no remove CN19 pin7 (BOM warning)
10. update FMC A0-A20, D0-D15 and QSPI D0-D3,NCS for BK1 and BK2 to 0 ohm series resistor
11. C177, C178 5.6pF changed to 3.9pF, SB82 and  SB81 close to PF0/PF1 for HSE accuracy 
12. C182, C183 footprint changed to C0402, SB88 and  SB87 close to PC14/PC15 for LSE accuracy
13. update on schematic Page 14:
MFX1 --> MFX0  JOY_SEL
MFX3 --> MFX2 JOY_LEFT
MFX2 --> MFX1 JOY_DOWN
MFX4 --> MFX3 JOY_RIGHT
MFX5 --> MFX4 JOY_UP 
14. add CN32 for MC testing with silkscreen "DAC2"
15. CN31 should move to the right 2mm. same with JP18.
16. update Q2 and Q3 footprint
17. LD5 large metal PAD should not soldermask for though via
18. MC sheet: add HW27
update resistor value:
R76 = R59 = R24 = 1.3kOhm
R66 = R51 = R25 = 9.1kOhm
R115 = R104 = R22 = 1.3kOhm
R122 = R95 = R20 =9.1kOhm
R65 = R56 = R32 = R106 = 1.1kOhm
R67, R57, R33, R105 = 3.3kOhm
19. remove JP3 and HW19
20. remove JP3 silkscreen, OA1_OUT changed to OA_OUT

MB1397B-02:

1. replaced EOL STTPUH7 to STT4P3LLH6


MB1397B-03:

1. SB8=OFF and SB10=ON for High brightness LED as default for demo request
2. add variant G484E for BOM


MB1397B-03:

1. SB8=OFF and SB10=ON for High brightness LED as default for demo request
2. add variant G484E for BOM


MB1397B-04:
1. C177, C178 changed to 1.8pF
2. C182, C183 changed to 4.3pF
3. add "U" samples for U6 to same for BOM and PBS
4. remove HW25 for battery information