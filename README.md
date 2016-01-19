# laser-harp
A laser harp with a dedicated management firmware created thanks to Arduino

This project consists in the creation of a musical instrument, in this particular case a laser harp with small and cheap lasers, Arduino as control and a sound generator to simulate the exact instrument. There are some critical points, which have been solved with the invention of a dedicated management firmware: playing with only 8 chords can create some problems for example with the management of the octaves.

The project uses an Arduino Mega 2560 with a shield MP3 SparkFun - eight laser diodes 5V 5mW and eight LDR which detect the presence / absence of the laser beam. The whole system is positioned on a rigid structure in wood which allows the alignment of lasers with the LDR, even remote. We also added to the first version a color touch display which controls the octaves and the resonance frequencies.

