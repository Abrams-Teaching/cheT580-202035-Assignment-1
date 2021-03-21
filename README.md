# D R E X E L&nbsp; &nbsp;  U N I V E R S I T Y
## Department of Chemical and Biological Engineering
### CHE T580 Modern Molecular Simulations
### Cameron F. Abrams cfa22@drexel.edu

# Assignment 1:  Git, C, Python, and the GNU Scientific Library

This assignment will test your installation of git, gcc, and Python using a few small programs.

## Instructions

1. Clone this repository to your local machine, and `cd` into the working directory, and launch VScode:
   ```bash
   $ git clone git@github.com:Abrams-Teaching/cheT580-202035-Assignment-1.git
   $ cd cheT580-202035-Assignment-1
   $ code .
   ```
2. Compile the program `gsl_test.c`, and run it:
   ```bash
   $ gcc -o gsl_test.c -lgsl
   $ ./gsl_test
   ```
   You can do this at a standalone terminal command-line, or inside VScode.
3. Modify `gsl_test.c` to perform the required output, recompile, and run.  Copy and paste the output into a new file called `my_gsl_output.dat`.
4. Compile the program `hhd.c`, and run it:
   ```bash
   $ gcc -o hhd hhd.c -lm
   $ ./hhd 10
   ```
   The `10` command-line argument is a number of "generations" of a fractal curve called the Harter-Heighway Dragon that `hhd.c` will generate.  Note the name of the output file this execution generates.
5. Run the python script `plot_dragon.py` according to its instructions.  Note the name of the image file generated.
6. Return your results by adding, committing, and pushing:
   ```
   $ git add .
   $ git commit -m "My Assignment 1 Results"
   $ git push
   ```
   