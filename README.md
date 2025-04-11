QSEIS2D - for quasi 2D structure model (only teleseismic applications)

For Windows user, the executable file is provided under folder "WindowsEXE". Linux user may compile the source codes with "gfortran" via a single command like, e.g.,

~>cd .../QseisScode/SourceCode

~>gfortran -o qseiss *.f -O3

to get the excutable code qseiss.

After start the executable code, the program ask for an input file in the ASCII format. An example input file is provided under folder "InputFile". You may change the input data included in this file for your own applications.

References

Wang, R., (1999), A simple orthonormalization method for stable and efficient computation of Green's functions, Bulletin of the Seismological Society of America, 89(3), 733-741.
