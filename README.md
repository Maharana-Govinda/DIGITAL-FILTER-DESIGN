COMPANY: CODTECH IT SOLUTIONS

NAME: GOVINDA MAHARANA

INTERN ID: CT04DF2309

DOMAIN: VLSI

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION OF TASK 4 

Design and Simulate a Digital FIR Filter Using Verilog or MATLAB
In Task 4, I had to design and simulate a Digital FIR (Finite Impulse Response) Filter. FIR filters are widely used in digital signal processing (DSP) applications such as audio processing, image filtering, and communication systems. The task could be done using Verilog or MATLAB. I chose to implement it in MATLAB due to its rich set of signal processing tools and easier visualization capabilities.

Using MATLAB R2023a, I designed a low-pass FIR filter using the fir1 function, which designs a filter based on the window method. I plotted the frequency response using fvtool and verified characteristics such as:

Passband frequency

Stopband attenuation

Phase response

To validate the filter, I applied test signals using filter() function and plotted the input and output waveforms to see how the filter suppressed unwanted frequency components.

In parallel, I also explored Verilog implementation by describing the FIR filter as a multiply-accumulate structure. It used:

An array of coefficients (h[n])

A shift register for input samples

A series of multipliers and adders

Simulation was done in ModelSim, and I used waveform analysis to see how inputs were convolved with the coefficients to produce the filtered output.

FIR filters are everywhere — from mobile phones for voice clarity to biomedical equipment for ECG signal smoothing. Understanding how they work and how to implement them in hardware gives a strong base in DSP hardware design.

This task enhanced my understanding of:

Convolution operations

Filter design principles

Hardware implementation vs software simulation

The role of fixed-point arithmetic in Verilog DSP systems

This knowledge is highly applicable in the VLSI domain, especially for engineers designing DSP cores or hardware accelerators. Filters like FIR are embedded in ASICs or FPGAs for high-speed signal processing tasks.

#OUTPUT

