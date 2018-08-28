## Pre-Analysis Plan for The Structure of International Treaty Diffusion"
## Ki Eun Ryu, Frederick Boehmke, Olga Chyzh, Zhanna Terechshenko, Bruce Desmarais,
 Jeff Harden
## Date: 5/30/2018

## Introduction

This document describes plan for the analysis of the diffusion of international treaties. 
Below we provide some brief background on the diffusion of international treaties and 
outline our expectations on the primary channels, speed, and nature of diffusion in different
issue areas. Then we discuss the details of our planned analysis.

(Theoretical expectations go here)

## Research Strategy

The aim of this project is to identify and explore the channels of the diffusion of international
norms. Building on recent advances in the broader diffusion research (Volden 2006; Desmarais,
Harden, and Boehmke 2015), we plan to use a machine-learning algorithm to construct a probabilistic
tree-network of likely pathways of norm diffusion. At the root of the tree are the few
influencer-countries, who are able to spread the norm to the countries that are most susceptible
to their influence(followers), who in turn spread it to their own followers, and so on.
We plan to provide the description of this network, including identification of the most 
salient edges and the main influencers, centrality of the network, etc. 


## Data 

For the purpose of this project we use the data are obtained from the United Nations (UN)
depository, which is a comprehensive collection of international treaties among states that
are members of the UN. The depository includes about 1,500 multilateral treaties during 
1945-2017.  We restrict the sample to multilateral treaties across the issue areas of 
security, economics, human rights and environment. We exclude treaties with restricted
membership (e.g., NAFTA) and treaties that preceded the foundation of the UN. We also excluded
all non-state members (e.g., international organizations). After removing invalid entries,
the resulting sample includes information on 1107 treaties and 47,505 treaty-participant
observations.

In the analysis, we subsample these treaties into three issue areas: human rights treaties,
economic treaties, and environmental treaties. As a result, we have 67 human rights treaties,
188 economic treaties, and 91 environmental treaties in our data. 


## Empirical Analysis

Our empirical analysis is going to consist of two parts. In the first part, we infer the
networks using the \texttt{NetInf} algorithm developed by Gomez-Rodriguez, Leskovec, and
Krause (2010). This algorithm traces paths of diffusion and influence through networks and
finds the most stable diffusion network. Once we infer the networks, we evaluate each
combination of the parameters (number of edges, diffusion model parameters, and size of the
time window used for the inference of each network on a grid. 

In the second part, we will focus on the text of treaties in order to identify whether 
treaty text predicts diffusion networks. In particular, we plan to perform
topic modelling. For example, we plan to perform is including the author topic model, where
the authors are countries that write/register the treaty. 

In addition, we plan to look at the complexity of features, as more complex treaties might
take longer to adopt and spread but may also rely more on networks since prior adoptors can
provide information that substitutes for a detailed understanding of the treaty.





 


