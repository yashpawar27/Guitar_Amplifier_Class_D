# Guitar_Amplifier_Class_D

There are several tasks a PREAMP needs to do for the amplifier to function properly
- Signal Boosting (Voltage Amplification): Boosts guitar signal to 1.7V

- Impedance Matching: Matching the guitar's signal to the amplifier's circuitry for consistent sound
  
- Tone Shaping (EQ): Modify Bass, Middle, and Treble
-   Treble: This lets high frequencies pass. This can be achieved by placing a capacitor in the signal path, which will cause the circuit to ignore the Bass/Middle and only let high frequencies pass

-   Bass: This lets low frequencies pass. Pair a resistor with a capacitor, which drains high frequencies to ground, letting only low frequencies through.
  
-   Middle: This lets medium frequencies pass. Combines both the Treble and Bass circuitry to filter out the medium frequencies.


-   Additional Note: Capacitors naturally block low frequencies but let high frequencies pass through easily. This can be used to differentiate frequencies using capacitors with different tolerances.
  
- Generating Distortion (Gain): Overload the preamp's op amp such that the input signal hits the op amp ceiling. This creates heavy distortion.

- Adding Compression: Smooth out the loud and quiet parts of music. Makes the guitar feel more responsive and easier to play. This can be achieved via a compressor circuit.

- Harmonic Enrichment: Adds extra frequencies that weren't there originally; makes the sound "rich"/"complex". This can be achieved via non-linear distortion by implementing a JFET transistor, which "curves" the signal to resemble that of a vacuum tube.

- Managing Multiple Channels: This means the amp switches between the "Clean" and "Lead" channels. The "clean" channel is designed to keep the signal pure. The "Lead/Dirty" channel is designed to produce a gritty, crunky, heavy noise. For now, we will only be creating the clean channel.

- Effects Integration: This allows the preamp to add reverb and delay, or loop the signal. For now, this will not be implemented.
