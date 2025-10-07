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

<img width="910" height="817" alt="image" src="https://github.com/user-attachments/assets/214d4fbc-e15c-43ab-aad3-78400af7340d" />



Output Waveform


<img width="1915" height="1015" alt="image" src="https://github.com/user-attachments/assets/38f76552-ebf6-4aa4-9a6c-f30e7e4a63cc" />



Tabular Column

<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/d6676e00-6b70-419d-8814-163e5ded0657" />



Calculation

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/b2a87696-819d-4649-b5a7-22ccb1df425a" />





Result


The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
