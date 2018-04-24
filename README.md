# Welcome

## William Peterson's Portfolio 

### Introduction
This document serves as a short guide to projects; both in-process and "completed."  

For more about me, or to get in touch, please visit my [LinkedIn](https://www.linkedin.com/in/wpgpeterson/).  

[View resume (pdf)](https://github.com/wipegup/wipegup.github.io/blob/master/Resume-Peterson.pdf)  
[View general cover letter](https://github.com/wipegup/wipegup.github.io/blob/master/GenCovLett-Peterson.pdf)  

[Navigate directly to my GitHub Home](https://github.com/wipegup)

## Projects:  

Projects in approximate reverse-chronological order.  

### [Distribution of Bird Taxa](https://github.com/wipegup/Capstone):  
#### What patterns emerge when investigating the division of bird species into genera?  

With molecular, and genetic processes, the division of birds into species seems to have
reached a good level of certainty and consistency. In turn, this project works to formulate
questions about the process of classification as it relates to genus-level division.  

In this pursuit, the **"sequence"** of species within a genus are compared to the **order of description** of species within a genus.  

The "sequence" (frequently referred to as "rank" in this project) is an ordering of species - within a genus - from least derived to most derived.
Practically, the order in which birds are listed in a genus is this sequence/rank.
The first listed is the "least derived," e.g. the species with the oldest close ancestor.
The last listed is the "most derived," e.g. the species which became a unique species most recently;
e.g. the species with the youngest ancestor.  

Slide 4 of [my presentation](https://docs.google.com/presentation/d/1lGLv4CpmHUvI-FvIDLxt898AzNwjlgwsl4Zc_ZBXpa4/edit#slide=id.g36cec819a2_0_0)
offers an example phylogenetic tree, where species 1 (s1) is least derived, and species 2 and 3 (s2, s3) are most derived.  

The "order of description", is simply the order in which the species of a genus were originally described.

Two goals for this project:  
- Create an interactive visualization tool for describing the relationship between date of description
- Present my findings on the peculiarities of genera-divisions within birds.

The long-term vision for this work involves working to determine what part of this investigation might be interesting for the ornithology community at large.
For this, and my general understandings as they relate to biology, and anything resembling "ground-truth," much help has come from [Dr. A.P.Peterson and his work](http://www.zoonomen.net)  

[Code for the interactive can be found here](https://github.com/wipegup/Capstone/blob/master/Interactive.ipynb)  
[Presentation here](https://docs.google.com/presentation/d/1lGLv4CpmHUvI-FvIDLxt898AzNwjlgwsl4Zc_ZBXpa4/edit#slide=id.p)

### [West Nile Kaggle Entry](https://github.com/wipegup/WNVKaggle)  

Work a collaboration with [M.Naumov](https://github.com/Mikhail-Naumov), [C.Greco](https://github.com/claugreco), and [C.Smiley](https://git.generalassemb.ly/ChrissySmiley).

Goal to submit a late entry to [Kaggle's West Nile prediction competition](https://www.kaggle.com/c/predict-west-nile-virus).

I led the group, parceling out tasks, ensuring our efforts stayed focused, and integrating the work and understandings developed by individuals into a cohesive whole.
Practically, much of my efforts were directed at making sure our data was in useable formats for modeling and visualizations. Enabling the rest of the group to apply their
own expertise required anticipating issues, and quickly building understanding and consensus as we made our way through the product.  

In the end we produced our [presentation](https://github.com/wipegup/WNVKaggle/blob/master/WNV%20Presentation-%20Mar%209.pptx) and our [model](https://github.com/Mikhail-Naumov/West_Nile_Virus) which surpassed the Kaggle baseline using a Convolutional Neural Network.

### [Reddit Comments](https://github.com/wipegup/Reddit)  

Collected data from Reddit regarding number of comments per post on posts appearing in "Hot". Then created prediction as a function of durations since initial posting, and the title.  

Scraping of data accomplished with `praw` and `scrapy`.
Searched through Boosted, bagged, logistic, and KNeighbors classifiers on AWS.

[Presented](https://docs.google.com/presentation/d/1mSoWZ1itVh7jFh9yA1KKcEUS1y8cPErRIlIVvb9SJfs/edit)

### [Iowa Liquor](https://github.com/wipegup/IowaLiquor/blob/master/code/Project-2-Peterson.ipynb)
Given data describing liquor sales in the state of Iowa for the 2015 and first quarter of 2016. Using that data, evaluated counties for saturation of liquor stores
in thinking about where a new store might be appropriate.  

Work involved implementing principles of EDA, on data grouped in different manners.  
[Final presentation](https://docs.google.com/presentation/d/1KqRuMIQ2aYtMTT4AQaSLsRpgOwqFP6_uvF5xqEZ7btw/edit#slide=id.p)

Migration from Enterprise GitHub occurred 4/13/18
