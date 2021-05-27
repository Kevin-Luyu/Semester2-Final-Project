Project name: Simulation and Inference for the Generalizaed Toilet Paper Problem

Contributors: Kevin Lu, Travis You


Contents:

toilet_paper.ipynb:
This program has five functions: 1) generate the distribution of leftover paper at p=.25, p=.5, and =.75, where p represents the proportion of big-chooser, when the initial amount of toilet paper n is given, 2) generate the centers and error bounds of the distribution of leftover paper from p=0 to p=1 at n=10, n=50, and n=100 respectively, 3) approximate the amount of leftover paper when n is large using Knuth's method, 4) calculate the exact number of p using Knuth's function 5) perform bootstrapping method to make a inference for p given a sample of results

n-roll simulation.ipynb:
This program is used to generate the centers of the distributions of the leftover paper from p=0 to p=1 when n=100 and the initial number of paper rolls is 2, 3, 4, or 5 respectively.


Instruction for toilet_paper.ipynb:
1. Run Cell 1 to Cell 3 to import packages and load functions
2. To perform function 1), run Cell 4
3. To perform function 2), run Cell 5 and Cell 6
4. To perform function 3), run Cell 7 to Cell 10
5. To perform function 4), run Cell 11 to 12 for an example
6. To perform function 5), run Cell 13 to Cell 19

Instruction for n-roll simulation.ipynb:
1. Run all cells
