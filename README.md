# Allpass-Filter-for-Group-Delay-Correction-of-a-Vented-Loudspeaker-Enclosure

This project is an attempt at recreating the study presented by Herzog et. al. (2014), wherein an allpass
filter based correction mechanism is designed in order to equalize the group delay that occurs in vented
loudspeakers at low frequencies. 

 An allpass filter that has the same group
 delay as the vented loudspeaker is implemented. The equalization filter is implemented in the
 following steps:
 ● Time-reverse x[n]
 ● Applysecondorder allpass filter
 ● Time-reverse x[n] again

It can be observed that the equalization mechanism does remove the effect of the loudspeaker
enclosure on the frequency spectrum of the audio signal, it does not fully restore the signal to its original
form. On listening to the final output audio signal, it can be observed that the signal is much softer and
has many artifacts.
