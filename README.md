# Introductory statistics for environmental modelling

This page links to a series of IPython notebooks introducing statistical concepts for environmental modelling, especially **Bayesian Markov chain Monte Carlo (MCMC)** methods for model **calibration** and **uncertainty estimation**.

Most of the examples are taken from hydrology or water quality modelling as that is my area of research, but the techniques presented are very general and applicable in a range of different fields.

As environmental models become more and more complex, the problems associated with calibration and evaluation become greater. Powerful statistical techniques are available to help, but for many environmental scientists they present a formidably steep learning curve. 

## Who are these notes aimed at?

My aim is to try to make Bayesian MCMC methods accessible to those with little or no statistical training. If you know what a **distribution** is and are comfortable with the concept of **integration** as the area under a curve, you should be able to follow everything here. 

In most cases I've abandoned mathematical rigour in favour of trying to give some kind of intuition for what's going on. Much of what I've done will probably be horrifying if you're a statistician or a physicist, but if you're just getting to grips with modelling for the first time perhaps this could be a stepping-stone towards better things (see below for some suggestions).

## Disclaimer

My background is in geology, not statistics or hydrological modelling. I still have a great deal to learn and I'm sure these pages will contain mistakes and misconceptions. If you spot anything *completely wrong* (as opposed to just very simplified), I'm always happy to be corrected.

This isn't a formal course in statistics - it's just a set of notes that I'm making available online in the hope that others find them useful.

## Other resources

If you're mathematically inclined, you're unlikely to find anything better than David MacKay's excellent book, [Information Theory, Inference and Learning Algorithms](http://www.inference.phy.cam.ac.uk/itila/book.html), together with the accompanying series of [video lectures](http://www.inference.phy.cam.ac.uk/itprnn/Videos.shtml). If you can follow these without too much difficulty then forget my notes and concentrate your efforts here instead!

I also thoroughly recommend Jake Vanderplas' series of [blog posts](http://jakevdp.github.io/blog/2014/03/11/frequentism-and-bayesianism-a-practical-intro/) as well as his [article on arXiv](http://arxiv.org/abs/1411.5018). 

Cam Davidson-Pilon's [Probabilistic Programming and Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) is another excellent reference.

Finally, if you're interested in these topics for work/research purposes (e.g. if you've just started a PhD in environmental modelling), I'd suggest taking a look at the [EAWAG Summer School in Environmental Systems](http://www.eawag.ch/forschung/siam/lehre/summerschool/index_EN), which I wish I'd attended a couple of years ago.

## Making the most of the IPython notebooks

The links below will take you to static versions of my notebooks rendered with [nbviewer](http://nbviewer.ipython.org/). However, to get the most of out of them, I recommend downloading each notebook to your computer and running it interactively. The following steps should get you started on Windows:

1. You'll need an up-to-date IPython installation. If you don't have one already try [WinPython](http://winpython.sourceforge.net/), which is a comprehensive and portable Python distribution that won't interfere with anything else on your system.<br><br> 

2. Once WinPython is installed, go to one of the notebooks below and download the **.ipynb** file to your computer (the "download" icon is at the top-right of the screen).<br><br>

3. Open the folder containing your WinPython installation and run the **WinPython Command Prompt** (not the normal Windows Command Prompt).<br><br>

4. **Change directories** to wherever you saved the **.ipynb** file and then type `ipython notebook` at the command prompt. Your browser should open to display the IPython dashboard and you'll see a link to the notebook you just downloaded.<br><br>

5. Click to open the notebook then choose `Cell > Run All` from the menu bar. Python will import all the necessary modules and run the notebook cells, which might take a few moments.<br><br>

You can now work through the notebook **interactively**, modifying the code etc. as you go.

## Contents

1. **[Distributions](http://nbviewer.ipython.org/github/JamesSample/James_Notes/blob/master/notebooks/01_Distributions.ipynb)**

    A quick overview of multivariate distributions, with the aim of developing some intuition about the **Sum** and **Product** rules as well as how they relate to **Bayes' Theorem**.<br><br>
    
2. **[Model calibration and likelihood functions](http://nbviewer.ipython.org/github/JamesSample/James_Notes/blob/master/notebooks/02_Calibration_Likelihood.ipynb)**

    A discussion of the issues relating to calibrating complex environmental models, which leads us to the concept of the all-important **likelihood function**.

