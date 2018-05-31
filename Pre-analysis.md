## Pre-Analysis Plan: The Structure of UN Treaty Diffusion"
## Ki Eun Ryu, Frederick Boehmke, Olga Chyzh, Zhanna Terechshenko, Bruce Desmarais, Jeff Harden
## Date: 5/30/2018

## Abstract

A country’s decision to ratify an international treaty is, in part, a function of the number and type of previous ratifiers as well as its expectations regarding future ratifiers. The timing and sequence of signatories and ratifiers, as well as the textual context helps understand the nature of this process. We analyze the content and the signing/ratification patterns of 1,500 UN multilateral treaties during 1945-2017, to classify treaties into distinct groups and infer diffusion patterns within these groups. We estimate the latent diffusion networks using NetInf to uncover connections between states. To understand the complex structure of treaty diffusion, we then estimate exponential random graph models (ERGMs) on the resulting latent networks. The ERGMs shed light on both the covariates that associate with diffusion ties between countries, and the forms of interdependence that characterize treaty diffusion networks. Lastly, we draw upon methods of network comparison with ERGMs to understand the ways in which different diffusion networks are similar and different. The results of this study provide an assessment of the number and structure of diffusion networks that underlie the spread of UN treaties among states. Our findings can be used to predict the patterns according to which a treaty will spread based on its content.



## Motivation

- Understudied mechanisms of treaty diffusion
- Existing studies focus on certain types of treaties
- First quantitative study on UN treaties diffusion

## Research Questions

- How does the text of the treaties can help us to understand the diffusion mechanism?

# Research Strategy

## Sample size

- 1,500 UN multilateral treaties during 1945-2017

### Data Collection

- Completed

### Data Processing

- Removing stopwords, numbers, punctuation; stemming words, etc.

### Option 1

- Identify clusters within UN treaties documents using (ex. using hierarchical clusters)
- Examine the effect of the clusters on the diffusion network. For example, we might expect that treaties that involve human rights issues are more likely to be diffused than military treaties.

### Option 2

- Use text of the treaties as a variable in the model

# Empirical Analysis

## Model

### Option 1

- Exponential random graph models (ERGMs)

### Option 2

- Latent space model
