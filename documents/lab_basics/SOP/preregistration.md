---
layout: default
title: Preregistration and Reproducibility
parent: Standard Operating Procedures
grand_parent: Lab Basics
nav_order: 3
---

# Preregistration and Reproducibility
For the Predictive Lab's stance on Open Science practices and preregistration please refer to our [handbook](https://drive.google.com/file/d/13JbOBwUpk7VZnzmkKABwjEH577l5s3Ku/view)

## Preregistration


In the lab we use two different platforms to preregister our studies:
1. [As Predicted](https://aspredicted.org/)
2. [Open Science Framework (OSF)](https://osf.io/)

with **As Predicted** following a specific structure and **OSF** providing more freedom to your structure. 

The current page provides you with guidance on the information you might want to include in your pre-registration document: 

1. The title of your project.
2. Whether any data have been collected for the study already.
3. The research questions and the hypotheses.
- What are the questions you want to answer with the current study?
- What are your hypotheses?
4. The variables and conditions in your study
- What is the dependent variable?
- What are the independent variables?
- What conditions do you have?
- Is the design event-related or blockwise (for fMRI studies)
5. Primary analyses
- What are the most important analyses you are going to perform?
- How are you going to perform these analyses?
- On which effects are you focusing to answer your main questions?
- How are you going to define your ROIs (for fMRI studies)?
6. Secondary analyses
- What other analyses are you going to perform?
7. Sample size
- How many participants will you test?
- How do you justify this sample size? (see also your PPM)
8. Quality check of your data
- How do you determine whether the data quality is good?
- When will you exclude a participant?
- i.e. if they missed more than …% of all trials.
- i.e. if they showed excessive motion during scanning.
9. Other
- Are there any other aspects of the study you would like to preregister?


The following three links are examples of pre-registered studies in the lab using the OSF:
* Matthias Fritsche - [The role of feature-based attention for serial dependence in perceptual decision making](https://osf.io/q7gj3/)
* Chuyao Yan - [Predicting groups of objects in the visual ventral stream](https://osf.io/s59p6)
* Jonas Karolis Degutis - [Laminar fMRI at 3T: A replication attempt of top-down and bottom-up laminar activity in the early visual cortex](https://osf.io/txuye/)


## Reproducibility and Research Data Management

Any project analysis script should be easily reproducible by other lab members or external parties. Hence, we try to always write code with the assumption that someone else will have to reproduce it without assistance. If you require a nudge on how to organize your code, look at [the writing code section]({% link documents/technical-help/software/reproducible_code.md %}) of the wiki on efficient coding practices. 

As an institute policy the research data for members of the DCCN should be findable and accessible. This can largely be achieved by actively archiving and publishing data via the Radboud Data Repository (RDR), under an appropriate license and access level, and by annotating the data with rich metadata. A major goal of the Donders Institute is to preserve and share research data for the long term. Hence, every researcher at the DCCN is nudged to make their data publicly available ([exceptions exist](https://www.ru.nl/rdm/vm/policy-documents/)). 

The regulations on Research Data Management (RDM) from the Radboud University can be found [here](https://www.ru.nl/rdm/vm/policy-documents/) and those specific for members of the DCCN [here](https://intranet.donders.ru.nl/index.php?id=6467). To faciliate the process of understanding RDM at the Donders, the staff is constructing a handbook so you have all the relevant information there. You can find the page [here](https://rdm.dccn.nl/)

{: .note}
> The handbook page for the RDM is still under construction. So we recommend looking at the two other pages highlighted before to get a full picture of RDM processes.

### How to Up/Download Data and Manage Collections

#### Request New Collection
[This page](https://intranet.donders.ru.nl/index.php?id=6788) provides you with extensive explanations about RDM when starting a project.

In short, the planning phase of the research project provides the opportunity to prepare many RDM-related aspects before any data is acquired or analyzed. At DCCN, the project planning phase is concluded with a presentation of project plans during a PPM and approval of the associated project proposal form. A Data Acquisition Collection (DAC) will be automatically created after your PPM presentation.

{: .note}
> You have to log into the [web interface](https://data.donders.ru.nl/) once, prior to your PPM, for the administration to find you in the system. [Here](https://data.ru.nl/doc/help/helppages/user-manual/login-profile.html) is information on how to do it.

In order to obtain a Research Documentation Collection (RDC) and Data Sharing Collection (DSC) you need to fill out this [request form](https://intranet.donders.ru.nl/index.php?id=donders-repository-request-form) on the DCCN intranet. You will typically need to request these collections after data acquisition/during analysis (RDC) and before publishing a paper containing the link to the shared data (DSC).

#### Edit Collection
You can edit collections via the web interface of the Donders Repository. The web interface can be accessed [here](https://data.donders.ru.nl/). Use your university credentials (u-number) to log in.

You can find your own collections by clicking on "My collections" in the top left corner. You can edit a particular collection by clicking on this collection and then click "Edit metadata" in the top left corner. Here you can change the title of the collection, add new managers, contributors and viewers etc. For FAQ questions on RDM, you can see [this page](https://intranet.donders.ru.nl/index.php?id=5931).

#### Up/Download Data

##### Automatic File Transfer
There are automated file transfers of MRI and MEG data to the Donders Repository and project storage in place. You can find more information on this [here](https://rdm.dccn.nl/docs/4_Collecting/4_UsingUploader.html). Remember to regularly check whether the the MRI and MEG files were transferred correctly. You can find information on how to check this [here](https://data.ru.nl/doc/help/helppages/user-manual/transfer-data/check-data.html). Also note that you will still need to transfer log files and other experiment-related data manually.

##### Manual File Transfer
There are multiple ways of manually up- and downloading data to/from the Donders Repository. You can find detailed information on each transfer method [here](https://data.ru.nl/doc/help/helppages/user-manual/transfer-data.html) or in the [new handbook](https://rdm.dccn.nl/docs/2_Background/2_Tools.html).

{: .note }
> Please note that mounting the Donders Repository as a network drive under Windows or MacOSX can be convenient, but will be considerably slower than Cyberduck, especially when uploading many files.

#### After Finalizing a Study

After completing a study, the raw data, stimulus material and both your experiment and analyses scripts should be uploaded to a Data Sharing Collection (DSC) in the Donders Repository associated with your study. For guidance on managing your research data, please refer to this [page](https://intranet.donders.ru.nl/index.php?id=datastorage-archiving-sharing). Every manuscript from the lab should include a data availability statement directing the reader to the corresponding DSC repository. As general open-science guidelines for members of the lab for the different stages of the publication process we:
* Preprint: Include statement that data and code will be shared
* Journal Submission: Change the DSC repository states to “reviewable external” and include the reviewer link in the data availability statement of the manuscript. Note that this link is not meant for sharing the data for research purposes, but only for review.
* Upon Acceptance: Change the DSC repository status to “published” (irreversible!) and the link included in the data availability statement of the manuscript

{: .note }
> While not a common practice in the lab yet, we are striving to share code and resources also through [GitHub](https://github.com/) (as it is increasingly more common in many different fields) 

