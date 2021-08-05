# Filter Design Based on fft & ifft

## Introduction
In order to cope with the filtering requirements under extreme requirements, FFT&IFFT filters are designed. Compared with traditional filters, the frequency accuracy is improved higher. 

## Processing
First cut the sound wave into small pieces to realize the processing of fft, which can transform the signal to the frequency domain. Then the redundant signal can be made to zero according to the user's request. Then the signal in the time domain can be recover from the signal by ifft. Last the pieces will be arranged as a sound wave.

