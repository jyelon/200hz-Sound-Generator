200hz sound generator:

This generates a fixed 200hz sine wave, using an arduino and a
resistor ladder DAC.  It is possible with the help of an amplifier
and speaker to turn this into a pure 200hz sound wave.

This program is part of a bigger project - a strange gadge to
detect when a CNC router's bit is touching the workpiece.  The gadget
works like this: you attach a 200hz sound wave generator to the
bed of the router.  You attach a 200hz frequency detector to the
spindle.  When the vibration travels from the bed, up the bit, and
into the spindle, you know the bit is touching the workpiece.
The 200hz waveform generator and the 200hz frequency detector are
separate github projects, but they're meant to go hand in hand.

