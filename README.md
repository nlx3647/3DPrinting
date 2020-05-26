# Ender3ProStuff

For an MKS GEN L v 2.0 board, start with adding jumpers the way it is in the picture.

Then add the TMC2208 v3.0 stepper drivers. These have UART added to them, so you can configure them in Marlin with SPI.

TMC2208

Values for configuration_adv.h:

x, y and z: 760.

E0: 900.
