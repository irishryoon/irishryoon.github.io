---
layout: page
title: Research
permalink: /research/
---

## computational neuroscience and topological data analysis

To be updated.

Joint work with <a href="http://www.chadgiusti.com/">Chad Giusti </a>(U. Delaware) and <a href="https://www.math.upenn.edu/~ghrist">Robert Ghrist</a>(U. Penn).



## RNA suboptimal sampling

RiboNucleic Acid (RNA) exists as a single-stranded polymer molecule. The bases of a RNA can pair to form complex secondary structures. In fact, there are RNAs that regulates important biological functions through a conformation change. An example of such multimodal RNA is illustrated in the following figure.   

![_config.yml]({{ site.baseurl }}/images/SAMIII_conformation1.png){:height="260px"} ![_config.yml]({{ site.baseurl }}/images/SAMIII_conformation2.png){:height="260px"}
*The SAM-III riboswitch is folds into two distinct secondary structures. It regulates gene expression by either exposing or sequestering the Shien Delgarno (SD) sequence.* 

A popular approach for predicting RNA secondary structure is to predict the minimum free energy(MFE) structure. In order to analyze alternatives to the MFE structure, people started sampliing suboptimal structures from the nearest neighbor thermodynamic model(Boltzmann sampling). Most algorithms that predict multiple RNA secondary structure follow the general flow of suboptimal sampling + clustering + reporting cluster representatives. 

During my time at Georgia Tch, I worked on improving a multiple seconary structure prediction algorithm called <a href="https://github.com/gtDMMB/RNAStructProfiling">profiling</a>. I proposed methods for improving the clustering aspect of the flow. In particular, the current method resulted in too many clsuters, and the difference among certain clusters were not biologically meaningful. I proposed algorithmic ways to identify clusters that should be merged based on structural similarity. The new version of profiling is currently under development at Georgia Tech <a href="https://github.com/gtDMMB">Discrete Mathematics and Molecular Biology</a> group.

I also examined the prospect of using Boltzmann sampling to identify new multimodal RNA molecules. I found that suboptimal sampling could be a valid tool for detecting particular types of RNAs(thermodynamic riboswitches). However, there is a class of RNAs(kinetic riboswitches) that is difficult to detect from current Boltzmann sampling methods. I proposed a simple co-transcription simulation method to identify key constituents of the RNA secondary structure that undergoes change. The results have been published <a href="https://www.degruyter.com/view/j/cmb.2019.7.issue-1/cmb-2019-0004/cmb-2019-0004.xml?format=INT">here.</a> 

Georgia Tech, 2018-2019, joint work with Christine Heitsch

## PhD Dissertation: applied sheaf theory

I work in applications of topology. My research is currently focused on applications to data science. Most recently, I used cosheaves and spectral sequences to compute persistence in a distributed manner. I applied such distributed computation to study multi-density data and recover information lost in persistence diagrams. 

For example, consider the following point cloud and its coresponding persistence diagram in dimension one.

![_config.yml]({{ site.baseurl }}/images/PointCloudExample.png){:height="260px"} ![_config.yml]({{ site.baseurl }}/images/PD.png){:height="260px"}

By observing the persistence diagram, one would conclude that there is one significant feature. However, one can see from the point cloud that there are small but significant features that are densely sampled. My construction of distributed computation allows one to identify the persistence points representing such features and annotate them as being significant. 

I have also worked on other applications of persistent cosheaf homology, such as applications to flow networks and splines changing over time. 

Here is a copy of my <a href="https://drive.google.com/file/d/1IdS2gOMYnfDzsFc3yOmFHbl5Pz1iHyuM/preview">research statement.</a> Here is a copy of my <a href="https://repository.upenn.edu/edissertations/2936/">PhD dissertation.</a>

Here is a 30 minute video of my presentation at <a href="https://www.ima.umn.edu/2017-2018/SW5.21-25.18/27292">IMA special workshop on Bridging Statistics and Sheaves.</a>

