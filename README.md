![](https://github.com/MrKohESP/GAmP/blob/5ed73520a8f6a7e9f614d7c9210eb063b58ba687/IMG_4959.jpg)
# GAmP
This circuit and subsequent project and headphone amplifier was designed and built for Mr. Koh's birthday.  It was built with web based tools only including [circuitlab.com](https:circuitlab.com), [EasyEDA](https://pro.easyeda.com/), and [onshape.com](https://onshape.com).

# Happy Birthday Mr. Koh 2025

This GAmP is a discret transister class A headphone amplifier capabable of driving headphones from 16 ohms to 600 ohms.  While only tested on 16 and 300 ohms the differences in performance for any impedences above 90 ohms were all similar.

# Schematic
![Final Schematic](https://github.com/MrKohESP/GAmP/blob/88427f906add45697c17dd080569a8d51216f463/Screenshot%202025-02-19%20132237.png)

Full size pdf version: https://github.com/MrKohESP/GAmP/blob/main/SCH_Schematic1_2025-02-19.pdf

You can simulate this circuit using our [simulation link](https://www.circuitlab.com/circuit/v85n8m64j45p/headphone-amplifier/)

You can make your own GAmP by copying the [easyEDA project]().

# BOM

| ID | Name                     | Designator           | Footprint                         | Quantity | Manufacturer Part        | Manufacturer           | Supplier | Supplier Part |
|----|--------------------------|----------------------|-----------------------------------|----------|--------------------------|------------------------|----------|---------------|
| 1  | BC856                    | Q8,Q9,Q1,Q2          | SOT-23-3_L2.9-W1.3-P1.90-LS2.6-BR | 4        | BC856                    | BLUE ROCKET(??)        | LCSC     | C7429738      |
| 2  | BC847C,215               | Q11,Q14,Q13,Q4,Q7,Q6 | SOT-23-3_L2.9-W1.6-P1.90-LS2.8-BR | 6        | BC847C,215               | Nexperia(??)           | LCSC     | C8664         |
| 3  | MMBT2907A(RANGE:100-300) | Q10,Q3               | SOT-23-3_L3.0-W1.7-P0.95-LS2.9-BR | 2        | MMBT2907A(RANGE:100-300) | CJ(????/??)            | LCSC     | C43692        |
| 4  | 100nF                    | C9,C10,C14           | C0402                             | 3        | CL05B104KB54PNC          | SAMSUNG(??)            | LCSC     | C307331       |
| 5  | 10pF                     | C6,C2                | C0603                             | 2        | CL10C100JB8NNNC          | SAMSUNG(??)            | LCSC     | C1634         |
| 6  | 10k?                     | R23,R11              | RES-ADJ-TH_3P-L10.0-W10.0-P2.50-L | 2        | 3296W-1-103              | BOCHEN(??)             | LCSC     | C118954       |
| 7  | DC-005 2.0               | DC1                  | DC-IN-TH_DC-5520-1                | 1        | DC-005 2.0               | BOOMELE(????)          | LCSC     | C16214        |
| 8  | 1000uF                   | C5,C1                | CAP-TH_BD10.0-P5.00-D1.0-FD       | 2        | KM108M025G17RR0VH2FP0    | CX(??)                 | LCSC     | C10750        |
| 9  | 10nF                     | C8,C11,C4            | C0402                             | 3        | CL05B103KB5NNNC          | SAMSUNG(??)            | LCSC     | C15195        |
| 10 | 1uF                      | C12                  | C0603                             | 1        | CL10A105KB8NNNC          | SAMSUNG(??)            | LCSC     | C15849        |
| 11 | 10uF                     | C7,C3                | C0603                             | 2        | CL10A106MA8NRNC          | SAMSUNG(??)            | LCSC     | C96446        |
| 12 | 10uF                     | C13                  | C0805                             | 1        | CL21A106KAYNNNE          | SAMSUNG(??)            | LCSC     | C15850        |
| 13 | KT-0603R                 | LED1                 | LED0603-RD                        | 1        | KT-0603R                 | KENTO                  | LCSC     | C2286         |
| 14 | BLM18PG600SN1D           | L1                   | L0603                             | 1        | BLM18PG600SN1D           | muRata(??)             | LCSC     | C85834        |
| 15 | 330?                     | R13,R16,R1,R4        | R0402                             | 4        | 0402WGF3300TCE           | UNI-ROYAL(??)          | LCSC     | C25104        |
| 16 | 10k?                     | R15,R21,R3,R9        | R0402                             | 4        | 0402WGF1002TCE           | UNI-ROYAL(??)          | LCSC     | C25744        |
| 17 | 1k?                      | R14,R2               | R0402                             | 2        | 0402WGF1001TCE           | UNI-ROYAL(??)          | LCSC     | C11702        |
| 18 | 4.7k?                    | R18,R6               | R0402                             | 2        | 0402WGF4701TCE           | UNI-ROYAL(??)          | LCSC     | C25900        |
| 19 | 51k?                     | R17,R5               | R0402                             | 2        | 0402WGF5102TCE           | UNI-ROYAL(??)          | LCSC     | C25794        |
| 20 | 100k?                    | R22,R20,R10,R8       | R0402                             | 4        | 0402WGF1003TCE           | UNI-ROYAL(??)          | LCSC     | C25741        |
| 21 | 10?                      | R19,R24,R7,R12       | R0603                             | 4        | 0603WAF100JT5E           | UNI-ROYAL(??)          | LCSC     | C22859        |
| 22 | 1.2k?                    | R25                  | R0603                             | 1        | 0603WAF1201T5E           | UNI-ROYAL(??)          | LCSC     | C22765        |
| 23 | MMBT2222A 1P             | Q12,Q5               | SOT-23-3_L2.9-W1.3-P1.90-LS2.4-BR | 2        | MMBT2222A 1P             | CJ(????/??)            | LCSC     | C8512         |
| 24 | PJ-3200                  | CN2,CN1              | AUDIO-TH_PJ-3200                  | 2        | PJ-3200                  | XKB Connectivity(????) | LCSC     | C2689690      |
| 25 | Test-Point               | TP1,TP2              | Test-Point-0.5mm                  | 2        |                          |                        |          |               |


# PCB

![Front Side](https://github.com/MrKohESP/GAmP/blob/88427f906add45697c17dd080569a8d51216f463/2D_PCB1_2025-02-19.png)

![Back Side](https://github.com/MrKohESP/GAmP/blob/88427f906add45697c17dd080569a8d51216f463/2D_PCB1_2025-02-19%20(1).png)

# 3D Model of PCB

![3D Image](https://github.com/MrKohESP/GAmP/blob/6eb4d379a9d827a5ec4db1e81b124d0b5fc4782c/3D_PCB1_2025-02-19.png)

Full size step version: https://github.com/MrKohESP/GAmP/blob/6eb4d379a9d827a5ec4db1e81b124d0b5fc4782c/3D_PCB1_2025-02-19.step

# PCB Production

![Production Timeline](https://github.com/MrKohESP/GAmP/blob/6eb4d379a9d827a5ec4db1e81b124d0b5fc4782c/Screenshot%202025-02-19%20131143.png)

# Enclosure

The enclosure is a custom designed SLA 3D printed snap-fit, vented, and split case.  Designed in OnShape an online 3D modeling site.  

You can see the assembly and models here: https://cad.onshape.com/documents/f1fd810423af36052080a337/w/e044fea8778af83a679eb873/e/5cdc29b059e584418c251eba?renderMode=0&uiState=67b62f22d31edd59f9896b6c

![Enclosure](https://github.com/MrKohESP/GAmP/blob/1d8ae425c8e42637553fd9db300b304da8d80c0a/IMG_4970.jpg)

# 3D Models of the Enclosure

![Bottom](https://github.com/MrKohESP/GAmP/blob/2a3f61c9f114ce1736a71b3a98f7bf1d06da5cfb/Screenshot%202025-02-19%20141003.png)

Full size stl file bottom: 
https://github.com/MrKohESP/GAmP/blob/6eb4d379a9d827a5ec4db1e81b124d0b5fc4782c/GAmP%2BvX%2BBottom.stl)

![Top](https://github.com/MrKohESP/GAmP/blob/2a3f61c9f114ce1736a71b3a98f7bf1d06da5cfb/Screenshot%202025-02-19%20140923.png)

Full size stl file top:
https://github.com/MrKohESP/GAmP/blob/6eb4d379a9d827a5ec4db1e81b124d0b5fc4782c/GAmP%2BvX%2BTop.stl)

# Enclosure Production

![Production Timeline](https://github.com/MrKohESP/GAmP/blob/578d3e1ba422d9222d90fe251d4de9fd1371d41c/Screenshot%202025-02-19%20131044.png)
