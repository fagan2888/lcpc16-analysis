To regenerate the mex files for octave, use the 'mkoctfile' utility and put the compiled libraries
in the folder corresponding to your platform.

E.g.
    
    mkoctfile --mex createMatrixRandJS.c
    mkoctfile --mex createRandomPageMatrices.c
