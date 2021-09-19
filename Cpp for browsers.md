<b> C++ for browsers </b>

This project reports on the progress making the C++ code of Stefan Aeberhard (Queensland Software and Process Control Pty Ltd) available for browsers. The collection of source code is called NOA which stands for Normalised Object Applications. 

<b> What is Normalised Software? </b>

Normalisation of software in NOA terms means that every logical software object has exactly one implementation. In practice this means that all software components share (i) the same lower level data structures and (ii) inherit the same shared behaviours. 
Normalisation allows for  guaranteed recombination (compiling) of two or more NOAH software projects. The only issue to resolve is that of having two main programs.

<b> Objects </b> 

NOAH is written in C++ and the objects are those of an object oriented language. Objects are organized hierarchically with the fundamental types at the bottom; those are integral numbers, real numbers, characters, and so on. Most objects comprise of a mix of fundamental types and smaller objects.
Applications
This refers to the use of NOAH objects to make applications for desktops and mobile platforms including

- Desktop GUI applications
- Server (cgi-bin) windowsless applications
- Browser (web assembly) applications

NOA has previously been used for the first two of the above. This project is exploring the use of NOA for browsers

