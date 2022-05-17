# Contents 

Magma companion code and computations from the paper “Equiangular lines in Euclidean spaces: dimensions 17 and 18”

The magma code is given in three files: polynomial.magma, compatibility.magma, and checkLemmata.magma.

polynomial.magma contains basic functions about polynomial generation.

compatibility.magma contains functions pertaining to the notion of Seidel compatibility.

checkLemmata.magma contains procedures the output computations used in the lemmas in the paper “Equiangular lines in Euclidean spaces: dimensions 17 and 18”. The outputs of these procedures are given in separate .txt files located in the folder /outputText/

The folder /precomputedData/ contains some precomputed data that is required to run some procedures in checkLemmata.magma.  This precomputed data is not necessary and is provided for the sake of convenience.

# How to use

Paste the contents of the following files into a magma terminal in the following order:

1. polynomial.magma
2. compatibility.magma
3. checkLemmata.magma

Then you can run the procedures that produce computations used in the companion paper, e.g., 

checkLemma56();
