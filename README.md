# Phasor plots

The minds of many students in the lifesciences turn numb as soon as they encounter even a single equation in a paper. This notebook is an effort to teach the analysis of FRET/FLIM by phasor plots to that part of the student audience, relying on two pillars: 1) the treatment builds up from high-school level in a -I hope- very intuitive way; and 2) it is built up in R, using ONLY base-R commands (i.e., it should run on any PC), and it uses numerical simulations rather that analytic math. This allows the user to interactively change many parameters (Tau, nr of photons, background, etc etc) and develop a very intuitive feeling for how this affects phasorplots.

It is assumed that the reader knows a tiny bit of coding in R, or can quickly read up on that. Reading through the actual codes should be easy, because I put in comments and because I go VERY slow with lots of repeats. I also recommend reading the code because it will prepare you to run simulations in R yourself, and it will allow you to modify any and all parameters and run code again. But even if you don't, the graphs should help intuitive understanding.

Use: run each of the code blocks in this notebook in turn. Note that in R you have to run the code blocks in order. If you return after running a later block, it may remember settings from those later code blocks. If this happens, just run previous code blocks in sequence again.

KJ, Summer 2023. Comments are welcome!

![image](https://github.com/user-attachments/assets/2c53a36e-a256-4182-b63c-62d56a1d7be4) ![image](https://github.com/user-attachments/assets/7b84d247-b15b-4f3e-8c88-ef21a5f3b2be)

_Phasor plots for high (left) and low (right) FRET states of our Epac sensor._

