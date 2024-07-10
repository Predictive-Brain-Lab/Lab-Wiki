---
layout: default
title: Psychophysics
parent: Behavioral Testing 
nav_order: 3
---

# Psychophysics

Psychophysics concerns itself with the relationship between physical properties of stimuli and the sensations and perceptions produced by them. In this section, we provide guidance on how to implement psychophysical procedures that you might use in your experiments. 

## What Do We Use Psychophysics For?
* To estimate thresholds, just-noticeable differences (JND), point of subjective equality (PSE), etc. for every subject.
* To map the shape of psychometric curves for every subject
* To control for task difficulty, so that the task accuracy is comparable across subjects (or conditions)

## What Are Commonly Used Methods?
The two types of staircasing procedures described below have their own pros and cons. To understand them better, we recommend you read the literature associated to each of them. A **key difference** to keep in mind is that _running fit method_ assumes that you know the shape of the underlying psychometric functions. On the other hand, the _up-down method_ works regardless of the shape of the underlying psychometric function. 

### 1. N-Up-M-Down Staircase (_e.g.,_ 2-Up-1 Down)

**How do we decide the N and the M?**
- Check the desired accuracy level you are aiming for, see _Table 2_ of the [Garcia-Perez (1998) paper](https://www.sciencedirect.com/science/article/pii/S0042698997003404?via%3Dihub#SEC2)

  
### 2. Running-Fit Methods

Following every trial, all collected data is used to fit a psychometric function (PF). This fitted PF is then utilized to determine the stimulus intensity for the next trial. 

**bestPEST** ([see here](https://link.springer.com/article/10.3758/BF03204398))

It assumes a specific form of the psychometric function and estimates only the threshold parameter of the psychometric function.

**Quest** ([see here](https://link.springer.com/article/10.3758/BF03202828))

It is essentially the Bayesian alternative to _bestPEST_. Note that when the prior is uniform and we use the mode of the posterior distribution as our estimate of the threshold, Quest is equivalent to the bestPEST.

Also see [here](https://jov.arvojournals.org/article.aspx?articleid=2611972), for a 2017 revised version of QUEST. 

**Practical Tricks**

The following list describes a series of tricks that can help you improve the final outputs of your staircase procedure:

* Provide your subjects with enough time to practice before running your staircase. As a rule of thumb you can provide them with ~50 trials.
* Create plots of every run of your staircase to check for convergence
* Use minimum two runs of staircases, and only read out from the ones that have converged.
* Instead of having very long runs of staircases (_e.g.,_ staircase of 90 trials), split them into short staircases (_e.g.,_~45 trials). This results in better output.

### Useful Resources

To implement any of the aforementioned procedures you are recommended to use [PsychToolbox](http://psychtoolbox.org/) (MATLAB) or [PsychoPy](https://www.psychopy.org/) (Python). _Note_: it is notoriously hard to implement staircases with Presentation. Hence, we recommend using one of the two other software options. 

The following list provides resources to learn more about these procedures:

* [The Palamedes Toolbox](https://www.palamedestoolbox.org/) - MATLAB routines for analyzing psychophysical data
* [Implementing staircase procedures in PsychoPy](https://www.psychopy.org/recipes/interleaveStaircases.html)
* [Forced-choice staircases with fixed step sizes: asymptotic and small-sample properties (Garcia-Perez, 1998)](https://www.sciencedirect.com/science/article/pii/S0042698997003404?via%3Dihub#SEC2) - Essential paper for thresholding
* [Simple adaptive testing with the weighted up-down method (Kaernbach, 1991)](https://psycnet.apa.org/record/1982-02539-001) - More specific resource. Not always applicable (see paper above first for an overview)
