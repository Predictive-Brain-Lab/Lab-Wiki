---
layout: default
title: M/EEG Resources
parent: M/EEG
nav_order: 3
---

The following section will provide with useful resources when starting with M/EEG analyses. Mostly, links to tutorials, lectures and relevant software for the different analysis.

## Software

The main software used by the members of the Predictive Brain Lab to do M/EEG analysis is the following:
* [FieldTrip](https://www.fieldtriptoolbox.org/) - **MATLAB** software toolbox for MEG, EEG and iEEG analysis. This is the **default** software being used given that it is developed at the Donders and they provide support for it.
* [MNE](https://mne.tools/stable/index.html#) - Open-source **Python** package for exploring, visualizing, and analyzing human neurophysiological data: MEG, EEG, sEEG, ECoG, NIRS, and more
* [EEGLAB](https://sccn.ucsd.edu/eeglab/index.php) - EEGLAB is an interactive **Matlab** toolbox for processing continuous and event-related EEG, MEG and other electrophysiological data

{: .note }
> You can ask other lab members if they have pro's and con's regarding their software selection before deciding what to use. It may be the case that specific software is better for some analysis compared to others. 

## General Resources

### Toolbox
 - The Donders Institute offers hands-on annual courses to get acquainted with some of the most recent neuroimaging techniques. Experts on the field working at the insitute guide these several day workshops. 
You can find the current schedule [here](https://www.ru.nl/en/donders-institute/services/donders-toolkits).

{: .note }
> Ask other lab members for their experience with these courses. Additionally, you might want to consider looking at the software being used during these toolkits as it might not match with your experience or goals.

### Books
* [Analyzing Neural Time Series Data (Theory and Practice)](https://mitpress.mit.edu/9780262019873/analyzing-neural-time-series-data/)  - This book offers a comprehensive guide to the theory and practice of analyzing electrical brain signals. It explains the conceptual, mathematical, and implementational (via Matlab programming) aspects of time-, time-frequency- and synchronization-based analyses of magnetoencephalography (MEG), electroencephalography (EEG), and local field potential (LFP) recordings from humans and nonhuman animals.
* [An Introduction to the Event-Related Potential Technique, Second Edition](https://mitpress.mit.edu/9780262525855/an-introduction-to-the-event-related-potential-technique/) - Very useful book to understand better the computations behind ERPs in EEG data.
* [MEG: An Introduction to Methods](https://academic.oup.com/book/9980)
* [Magnetoencephalography - From Signals to Dynamic Cortical Networks](https://link.springer.com/book/10.1007/978-3-642-33045-2)

### Articles
#### MEG
* [Magnetoencephalography for brain electrophysiology and imaging - Baillet (2017)](https://www.nature.com/articles/nn.4504). A great review on the aspects that uniquely characterize magnetoencephalography (MEG) to study the brain.
* [The brain in time: insights from neuromagnetic recordings - Hari et al. (2010)](https://nyaspubs.onlinelibrary.wiley.com/doi/full/10.1111/j.1749-6632.2010.05438.x). A nice introduction to MEG recordings.
 
#### EEG
* [A Brief Introduction to the Use of Event-Related Potentials (ERPs) in Studies of Perception and Attention - Woodman (2010)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3816929/).
* [Where Does EEG Come From and What Does It Mean? - Cohen (2017)](https://www.sciencedirect.com/science/article/pii/S0166223617300243?via%3Dihub). Great paper to better characterize EEG.
* [The functional importance of rhythmic activity in the brain - Thut et al. (2012)](https://pubmed.ncbi.nlm.nih.gov/22917517/). Paper that reflects different analysis that can be performed with this type of data.
* [Under the Mind's Hood: What We Have Learned by Watching the Brain at Work - Nobre and Ede (2020)](https://www.jneurosci.org/content/40/1/89). Nice reflection on how these neuroimaging methods have been changing our understanding the brain in the last years.

#### Advanced Analysis
* [Decoding Rich Spatial Information with High Temporal Resolution - Stokes et al. (2015)](https://www.sciencedirect.com/science/article/pii/S1364661315002077). Article highlighting how MEG might be ideal for decoding neural states.
* [Decoding Dynamic Brain Patterns from Evoked Responses: A Tutorial on Multivariate Pattern Analysis Applied to Time Series Neuroimaging Data - Grootswagers et al. (2017)](https://pubmed.ncbi.nlm.nih.gov/27779910/). A primer on using MVPA for M/EEG data
* [Characterizing the dynamics of mental representations: the temporal generalization method - King and Dehaene (2014)](https://www.sciencedirect.com/science/article/pii/S1364661314000199?via%3Dihub). Adapting MVPA to time resolved signals. Great paper!
* [Nonparametric statistical testing of EEG- and MEG-data - Maris and Oostenveld (2007)](https://www.sciencedirect.com/science/article/pii/S0165027007001707?via%3Dihub).

### Video Series

- Besides containing tutorials and giving the Donders Toolkit for neuroimaging, the authors of Fieldtrip also upload a variety of videos to their page explaining different concepts or analysis performed in MEG or EEG. These can be found on this [link](https://www.fieldtriptoolbox.org/video/).

{: .note }
> They may overlap with the Donders Toolkit, so you might find information being repeated.

- The Swedish National Facility for MEG has complied a [series of lectures](https://natmeg.se/learnaboutmeg/meglectures/) by a wide range of speakers explaining different terms and analysis types performed in this type of data. They of course do not have continuation between speakers but you might find useful information here.

- Series of videos on Neural Signal Processing and Analysis by Mike X Cohen (used to be a researcher at the Donders). You can find them, [here](https://www.youtube.com/playlist?list=PLn0OLiymPak0t1moK3sn4Sl1seXlEOPHT)

- [Introduction to EEG/MEG Data Analysis](https://www.youtube.com/playlist?list=PLp67eqWCj2f_DBsCMkIOBpBbLWGAUKtu5) - A recently released (2024) series of videos by the head of the M/EEG deparment at Cambridge, Olaf Hauk. It goes through some of the most important concepts for analyzing this type of data. 


### Courses

- [MNE Tutorial Series](https://mne.tools/stable/auto_tutorials/index.html) - Their website provides explanations, sample code, and expected output for the most common types of analysis in M/EEG. They have very clear and thorough explanations, though at the expense of not having too many topics being explained. 
