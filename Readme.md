Talon Breakout Board, v2
------------------------

Epic Robots, Team 4415

December 2018

Epic Robots has designed a breakout board that works with the Talon SRC manufactured by Cross
the Road Electronics.    This breakout board brings all signals from the data port to connectors
that provide secure connections for wiring to limit switches and encoders.  The breakout board
can be secured directly on the Talon, and the sensor/encoder wires can be directed inline with
the other Talon wiring to improve wire routing on the robot.  The connectors use a strong friction
fit to avoid becoming loose during a match.   This design of the breakout boards (and the
companion encoder PCB) was designed and tested during the Fall of 2018 by Epic Robotz
(Team 4415).  The design is being provided here for other teams to use if they see fit.
The boards where designed with a free version of Autodesk EAGLE pcb design software.  
All the files necessary to produce the breakout boards are included in this repository.

Notes
-----

The PCB is designed to be directly mounted in contact with the Talon.  Since the Talon is made of 
metal, care has been taken to place vias in areas where there is no metal on the Talon. However, 
when purchasing PCB boards with this design, be sure to put solder mask over the vias (which
is normally not done when fabricating prototypes).

It is also important to grind away any excess protrusion of through-hole pins on the solder side where
the connectors are soldered into place.  We have inclucded pictures to show how this is done.  Note
that the PCB traces to the connectors are ALL on the top side, so deep grinding of the bottom where
the connector pins protrude is okay.

For additional electrical insulation between the breakout board and the Talon, we suggest that you
epoxy a "gasket" direcly on the PCB.  All the files to 3D print the gasket are provided here as well
as pictures to show how the glue up is done.

We have included a design for a solder jig that holds the through-hole connectors in place while
soldering.  However, you will need to solder the SMD 2x5 connector with an oven or by hand
using a microscope and solder paste.


Bill of Materials
-----------------

    Talon PCB      --  Procured via a PCB manufacturing company using the gerber files.
                       Each PCB will produce 6 breakout boards, and 6 companion encoder boards.
    
    Gasket        --   1 Gasket per Breakout board.  Obtained via 3D printing.
    
    2x5 Connector --   1 per Breakout board.  Digikey 609-3706-1-ND.  This is an SMD part.
    
    4 pin Header  --   1 per Breakout board. Digikey WM16136-ND. This is a through hole part.
    
    3 pin Header  --   2 per Breakout board. Digikey WM2712-ND. This is a through hold part.
    
    Green LED     --   1 per companion encoder board. DigiKey 754-1131-1-ND. This is an SMD part.
    
    Blue LED      --   1 per companion encoder board. DigiKey 754-1437-1-ND. This is an SMD part.
    
    Red LED       --   1 per companion encoder board. DigiKey 754-1132-1-ND. This is an SMD part.
    
    1K Resistor   --   3 per companion encoder board. DigiKey 311-1.0KARCT-ND. This is an SMD part.

    5 Min Epoxy   --   A 3 oz 2-bottle kit will probably glue 100s of Gaskets.

To attach wires to the breakout board, you will need the following:

    3 Pos Housing   -- DigiKey WM2001-ND. One per limit switch

    4 Pos Housing   -- DigiKey WM2002-ND. One per encoder.
    
    Crimp Terminals -- DigiKey WM2312. 3 per limit switch, 4 per encoder.






