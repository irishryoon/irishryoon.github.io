---
layout: page
title: Research
permalink: /research/
---

## computational neuroscience 

Current project(2019-2020). To be updated. 

I am using tools from signal processing, time series analysis, and topological data analysis to analyze functional brain networks. I have been working with data from spike trains and local field potentials. 

*Joint work with <a href="http://www.chadgiusti.com/">Chad Giusti</a> (U. Delaware) and <a href="https://www.math.upenn.edu/~ghrist/">Robert Ghrist</a> (U. Penn).*



## RNA structure sampling and clustering

A RiboNucleic Acid (RNA) can form complex structure through intra-molecular base-pairing. Some classes of RNAs can regulate biological functions by changing its conformations. An example is illustrated below.   

![_config.yml]({{ site.baseurl }}/images/SAMIII_conformation1.png){:height="180px"} ![_config.yml]({{ site.baseurl }}/images/SAMIII_conformation2.png){:height="175px"}

*<span style = "font-size:0.8em">The SAM-III riboswitch folds into two distinct secondary structures. It regulates gene expression by exposing or sequestering the SD sequence, which controls translation.</span>* 

Identifying multiple structures of a RNA can bring therapeutic advancements for RNA viruses. A popular approach is to sample low-energy structures from the nearest neighbor thermodyanmic model. Most algorithms follow the general flow of <b>sampling</b>, <b>clustering</b>, and reporting <b>cluster representatives</b>.

I worked on improving the <b>clustering</b> aspect of an RNA structure prediction algorithm called <a href="https://github.com/gtDMMB/RNAStructProfiling">profiling</a>. The current method resulted in too many clsuters with negligible biological difference. I proposed algorithmic ways to identify clusters that should be merged based on structural similarity. The enhanced version of profiling is under development by Georgia Tech <a href="https://github.com/gtDMMB">Discrete Mathematics and Molecular Biology</a> group.

I also examined the prospect of using current methods to identify new multimodal RNAs. I found that there is a class of RNAs (kinetic riboswitches) that is difficult to detect from current sampling methods. I proposed a simple co-transcription simulation method to identify multimodality of such RNAs. The results have been published in this <a href="https://www.degruyter.com/view/j/cmb.2019.7.issue-1/cmb-2019-0004/cmb-2019-0004.xml?format=INT">paper.</a> 

*Georgia Tech (2018-2019), joint work with <a href="https://sites.google.com/site/christineheitsch/">Christine Heitsch</a> (Georgia Tech) and <a href="https://ribosnitch.bio.unc.edu/">Alain Laederach</a> (UNC).*

## multiscale feature detection via distributed topological data analysis

For my PhD dissertation, I worked on applications of topology to data science. I used <b>cosheaves</b> and <b>spectral sequences</b> to compute <b>persistence</b> in a distributed manner. I applied such distributed computation to study <b>multi-density data</b> and recovered the information lost in persistence diagrams. 

For example, consider the following point cloud and its coresponding persistence diagram in dimension one.

![_config.yml]({{ site.baseurl }}/images/PointCloudExample.png){:height="260px"} ![_config.yml]({{ site.baseurl }}/images/PD.png){:height="260px"}

By observing the persistence diagram, one would conclude that there is one significant feature. However, one can see from the point cloud that there are small but significant features that are densely sampled. My construction of distributed computation allows one to identify such significant features that are neglected by traditional methods. 

Here is a 30 minute video of my presentation at <a href="https://www.ima.umn.edu/2017-2018/SW5.21-25.18/27292">IMA special workshop on Bridging Statistics and Sheaves.</a>

The paper can be found on <a href="https://arxiv.org/abs/2001.01623">arXiv.</a> Here is a copy of my <a href="https://repository.upenn.edu/edissertations/2936/">PhD dissertation.</a>


*University of Pennsylvania (2013-2018), PhD dissertation. Joint work with <a href="https://www.math.upenn.edu/~ghrist/">Robert Ghrist</a> (U. Penn).*

