# week-4-resolution
# Week 4 - Electric Piano Kit

I'm building a 555 timer piano kit because I wanted to make something
fun and interactive that someone else could assemble and actually play with.

## May 26 

I designed the schematic for my electric piano in KiCad.
The circuit uses a NE555P timer with 6 buttons, each one plays a different
note through a buzzer when pressed.
then I routed the PCB placed all the components down with the 6 buttons
in a column and the USB connector on the edge of the board rounded the
corners on the board outline to make it look cleaner.
The DRC passed with no errors.
here is my schematics 
<img width="837" height="480" alt="Screenshot 2026-05-26 at 5 45 45 PM" src="https://github.com/user-attachments/assets/19f17ebe-278a-497a-8a79-09813761ab5e" />
my pcb
<img width="401" height="582" alt="Screenshot 2026-05-26 at 5 49 37 PM" src="https://github.com/user-attachments/assets/47c0e09e-78ab-4200-93f9-314396e54f4c" />

my pcb render
<img width="585" height="585" alt="Screenshot 2026-05-26 at 5 47 01 PM" src="https://github.com/user-attachments/assets/f528bdbf-7df8-4f20-9682-6fc16088d266" />


## BOM

| Designator | Component | Value |
|------------|-----------|-------|
| U1 | NE555P Timer | NE555P |
| SW1-SW6 | Push Button | SW_PUSH_12mm |
| R1 | Resistor | 1K |
| R2 | Resistor | 4.7K |
| R3-R7 | Resistor | 1K |
| C1, C2 | Capacitor | 100nF |
| C3 | Capacitor | 10µF |
| BZ1 | Buzzer | Passive Buzzer |
| J1 | USB A Connector | USB_A |




### Time Spent: 1 Hour
