### 1. Square Waves
A square wave is a non-sinusoidal waveform that alternates between a high and a low state, creating a waveform that resembles a series of squares. It is characterized by its period (T), which is the time it takes to complete one full cycle, and its frequency (f), which is the number of cycles per second. The relationship between frequency and period is given by:

$ f = \frac{1}{T} $

2. Fundamental Frequency
The fundamental frequency is the lowest frequency of a periodic waveform and is the first harmonic of the wave. For a square wave, the fundamental frequency is the frequency at which the wave oscillates. It is the primary frequency that defines the shape of the square wave.

3. Harmonics
Harmonics are integer multiples of the fundamental frequency. In the case of a square wave, only odd harmonics are present. This means that if the fundamental frequency is $ f_1 $, the harmonics can be expressed as:

First harmonic (fundamental): f1=f
Third harmonic: f3=3f
Fifth harmonic: f5=5f
Seventh harmonic: f7=7f
And so on...
The even harmonics (2nd, 4th, etc.) are absent in a square wave.

4. Fourier Series Representation
A square wave can be represented as a sum of its harmonics using Fourier series. The Fourier series for a square wave can be expressed as:

$ f(t) = \frac{4A}{\pi} \sum_{n=1,3,5,\ldots}^{\infty} \frac{1}{n} \sin\left(2\pi n f t\right) $

where $ A $ is the amplitude of the square wave, and $ n $ represents the odd harmonics.

5. Amplitude and Harmonics
In a square wave, the amplitude of the harmonics decreases as the frequency increases. Specifically, the amplitude of the $ n $-th harmonic is inversely proportional to $ n $:

$ A_n = \frac{4A}{\pi n} $

This means that higher harmonics contribute less to the overall shape of the square wave.

6. Phase Relationships
The phase of the harmonics in a square wave is not uniform. Each harmonic can have a different phase shift relative to the fundamental frequency. This phase relationship contributes to the overall shape and characteristics of the square wave.

7. Applications
Square waves are widely used in electronics and signal processing. They are used in digital circuits, clock signals, and as test signals in various applications. Understanding square waves and their harmonics is crucial for designing and analyzing circuits that operate with digital signals.

Conclusion
The experiment involving square waves, their fundamental frequency, and harmonics provides insights into the behavior of periodic signals. By analyzing these properties, one can better understand the principles of waveforms, signal processing, and their applications in technology.
