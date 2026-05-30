# Electric Piano Kit

A PCB kit built around a NE555P timer with 6 buttons, each playing a 
different note through a buzzer when pressed. Designed to be assembled 
by anyone with basic soldering skills.

PCB Render:<img width="425" height="509" alt="Screenshot 2026-05-29 at 9 47 26 PM" src="https://github.com/user-attachments/assets/a95db3ef-872a-45cb-ad5b-3dd90783a373" />


KiCanvas Link: https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FNxyz-natan%2Fweek-4-resolution%2Ftree%2Fmain%2Fweek%25204

## How it works

The NE555P runs in astable mode where each button connects a different 
resistor into the timing circuit, changing the output frequency and 
producing a different note through the passive buzzer.



## Schematic

Schematic: <img width="459" height="268" alt="Screenshot 2026-05-29 at 9 47 51 PM" src="https://github.com/user-attachments/assets/d8ccdd8f-dd0e-499b-9131-0bdca344dfe4" />


## PCB

PCB:<img width="321" height="555" alt="Screenshot 2026-05-29 at 9 48 03 PM" src="https://github.com/user-attachments/assets/cf530fac-e423-459a-a888-96efe871d3d4" />




## BOM

| Designator | Component | Value | Footprint |
|------------|-----------|-------|-----------|
| U1 | NE555P Timer | NE555P | DIP-8_W7.62mm |
| SW1-SW6 | Push Button | SW_PUSH | SW_PUSH-12mm |
| R1 | Resistor | 1K | R_Axial_DIN0204 |
| R2 | Resistor | 4.7K | R_Axial_DIN0204 |
| R3-R7 | Resistor | 1K | R_Axial_DIN0204 |
| C1, C2 | Capacitor | 100nF | C_Disc_D8.0mm |
| C3 | Capacitor | 10µF | C_Polarized |
| BZ1 | Buzzer | Passive | Buzzer_12x9.5RM7.6 |
| J1 | USB A Connector | USB_A | USB_A_Molex_Horizontal |

## Assembly Notes

1. Solder all resistors first
2. Then capacitors
3. Then the NE555P IC
4. Then buttons
5. Finally the buzzer and USB connector
6. Plug into USB power and press any button to play a note
