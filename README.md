# FM-using-Python

Aim


To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:



Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program

import numpy as np

import matplotlib.pyplot as plt

Am = 2.9

Ac = 5.8

Fm = 259

Fc = 2590

Fs = 25900

b = 2.3

t=np.arange(0,2/Fm,1/Fs)

m=Am*np.cos(2*np.pi*Fm*t)

plt.subplot(3,1,1)

plt.plot(t,m)

c=Ac * np .cos(2* np.pi* Fc* t)

plt.subplot(3,1,2)

plt.plot(t,c)

s=Ac* np .cos(2 * np.pi * Fc * t+b * np.sin(2 * np.pi* Fm* t))

plt.subplot(3,1,3)

plt.plot(t,s)


Output Waveform

<img width="575" height="413" alt="image" src="https://github.com/user-attachments/assets/64fccd58-a595-4d97-a049-a9dea5a976b3" />



Tabular Column

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/5acfa918-8167-4a4c-87fb-d21ae0a99350" />


Result


The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
