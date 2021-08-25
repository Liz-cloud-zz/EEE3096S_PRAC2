# EEE3096S_PRAC2
# Practical - The Unix shell and RPi Hardware

This practical is designed to teach you core concepts which are fundamental to developing
embedded systems in industry. It will show you the importance of C or C++ for embedded
systems development. We’ll start by running a program in Python - which will be our ‘Golden
Measure’ - and comparing its execution speed to the exact same program written in C++.
This will show us how using different programming languages can impact the performance of
the program. From there, we’ll try and improve the performance of the C code as much as
possible, by using different bit widths, compiler flags and threading.
The quest for optimisation can lead one down a long, unending spiral. What is important to
take away from this practical is the awareness of optimisation concepts and the ability to use
good practice when benchmarking.

There’s a considerable flaw in this investigation in that there is no comparison of results to
our golden measure. Meaning, by the end of the practical, you will (ideally) have considerably
faster execution times - but your speed-up could be entirely useless if the result you’re getting
is not accurate. Comparison of accuracy is left as a task for bonus marks.
