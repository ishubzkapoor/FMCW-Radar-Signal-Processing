## FMCW Radar Signal Processing

This project demonstrates the basic signal processing chain of an FMCW radar for both single-target and multiple-target scenarios. The notebooks show how a transmitted chirp is reflected by targets, mixed with the received echo to generate a beat signal, and processed using FFT-based techniques to estimate target range.

### Single Target Processing Chain

The single-target notebook focuses on the core FMCW radar principle in a simple and easy-to-follow way. It shows the transmitted chirp, delayed target echo, beat-frequency generation, and range FFT used to estimate the target distance.

**Processing flow:**
`Transmit Chirp → Delayed Echo → Mixer / Beat Signal → Range FFT → Target Range Estimation`

### Multiple Target Processing Chain

The multiple-target notebook extends the same FMCW concept to multiple objects at different ranges and velocities. It demonstrates how radar returns from several targets are combined, processed across fast-time and slow-time samples, and visualized using range-Doppler processing.

**Processing flow:**
`Multiple Target Echoes → Beat Signal Generation → Range FFT → Doppler FFT → Range-Doppler Map`
