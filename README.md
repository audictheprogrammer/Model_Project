# MODEL - Project


## Everything must be implemented in C

- Implement an arithmetic for complex numbers based on double-precision floating-point numbers, i.e. with real and imaginary parts.
- Implement the FFT and inverse FFT for vectors of size 2k: these functions must enlarge vectors of sizes that are not powers of 2.
- Implement the naive algorithm for multiplying polynomials with integers coefficients.
- Implement an FFT-based algorithm for multiplying polynomials with integers coefficients (see exercise in the course material).
- Compare their efficiency.

## Practical and organisation aspects:

This project can be done as groups of three. In that case, the names of all students must appear clearly and explicitly both in comments on top of all C files and on the report. Any complaint about this matter (e.g. if your name does not appear anywhere on the submission) more than a few hours after the deadline will not be taken into account. You are responsible for checking the files submitted by the other persons in your group, and send us any complaint as early as possible. Always open your submitted files to make sure you submitted the latest version, you submitted all files, etc.

## Expected files (in a single zip file):

- Source files of your code, including a makefile to facilitate compilation.
- A "readme" file (text or markdown format) which gives basic instructions on how to compile and try the code.
- A report in pdf, which presents (see also above where some similar advice is mentioned):
    1. your implementations: main functions and organization of your code, explanations of parts that are not yet fully functional, difficulties that you encountered, etc,
    2. the results of your benchmarks: timings of your functions on different sizes of matrices
    3. your conclusions about the performance you have observed, and possible improvements in your code.




// Avancee :

- Produit de polynomes naif OK
- Produit de polynomes FFT OK
- Il reste à comparer les performances

Enzo : j'ai vérifié -> get_prim_root/get_roots/split TOUT FONCTIONNE
il faut vérifier les autres fonction ie eval et le code en général (qu'on utilise la bonne racine/la bonne taille etc...)