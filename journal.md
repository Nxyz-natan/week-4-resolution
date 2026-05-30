# Electric Piano Kit

[Preface] I'm building a 555 timer piano kit because I wanted to make 
something fun and interactive that someone else could assemble and 
actually play with.

## May 26 - Schematic and PCB Design

Today I worked on the full schematic and PCB in KiCad.

The circuit uses a NE555P timer in astable mode with 6 buttons, each 
connected to a different resistor value. When a button is pressed it 
changes the RC timing network which changes the output frequency, 
producing a different note through the passive buzzer.

I placed the 6 buttons in a column to make the layout intuitive  
like a simplified piano keyboard. The USB connector sits on the edge 
of the board for easy power access. I rounded the board corners using 
the fillet tool to give it a cleaner look.

The DRC passed with no errors.

### Time Spent: 1 Hour
