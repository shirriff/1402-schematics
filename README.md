# IBM 1402 card reader schematics

You probably want to view [1402-schematics.pdf](1402-schematics.pdf).

I've redrawn IBM 1402 [schematics](https://bitsavers.org/pdf/ibm/1402/1402_Reader-Punch_Wiring_Diagram.pdf)
in KiCad to make them more readable, specifically the relay logic for the reader.
The original schematics draws the relay logic in a way that is almost
impossible to follow: crammed together and split across pages.
(Even so, these schematics probably won't make sense to the modern reader.)

## Reader stop

The following diagram, annotated from the [CE Reference Manual](http://www.bitsavers.org/pdf/ibm/1402/S231-002-5_1402_Card_Read-Punch_CE_Instruction-Reference_Apr67.pdf) shows the various paths to a READER STOP.

![Read Stop Data Flow](read-stop.jpg)
