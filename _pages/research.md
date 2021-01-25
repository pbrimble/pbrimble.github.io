---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

Here is a brief overview of my research interests. These range from my onging work, research projects during my time at the Government of Rwanda, as well as written work for my degrees.

---
## Work in Progress

**Evaluating the Impact of National Solar Home System Subsidies in Togo**  
With Deivy Houeix, Axel Eizmendi-Larrinaga and Toni Oki

**VIIRS Nighttime Lights for Economic Applications**  
With Adam Storeygard, Axel Ezimendi-Larrinaga and Kazuki Motohashi

**Evaluating the Impact of Zoning Laws in Developing Country Cities using Spatial Data**  
With Matthew Sharp

**Valuing Property and Buildings in Kigali and Secondary Cities for an Operational CAMA**  
With Patrick McSharry, Kaspar Kundert, Felix Bachofer and Andreas Braun

## Completed Research

**Using Machine Learning and Remote Sensing to Value Property in Rwanda**  
With Patrick McSharry, Felix Bachofer, Andreas Braun and Jonathon Bower  

*Property valuation models can achieve mass valuation transparently and cheaply. This paper
develops a number of property valuation models for Kigali, Rwanda, and tests them on a unique dataset combining remote sensing data and infrastructure and amenities data for properties in Kigali, with sales transaction data for 2015. We use a machine learning approach, Minimum Redundancy Maximum Relevance, to select from 511 features those that minimise ten-fold cross validated Mean Absolute Error. Cross validated diagnostics are used to eliminate overfitting given that our goal is to generate a model that can be used to extrapolate value estimates out of sample.*

**Rwanda's Agricultural Productivity Gap**

*From the 1990s until the late 2010s, there are three distinct three distinct stages describing the trends in Rwanda’s (unadjusted) agricultural productivity gap. Firstly, during the pre-transition stage from 1991 to 2002, the gap is incredibly large and volatile with an average of 10.15. Secondly,the transition stage from 2002 to 2005 is marked by a steep and permanent decline in the gap from 11.61 to 5.01 over this short time period. Finally, the post-transition stage from 2005 onwards sees the gap stabilise significantly, averaging a much more respectable 6.01 during this decade. Furthermore, a sizeable portion of this gap can be explained by differences in sectoral human capital.*

Download [here](https://github.com/pbrimble/pbrimble.github.io/raw/master/files/rwanda_apg_2018_02.pdf).


**Production Networks and International Trade**   
MPhil Thesis

*This paper examines how increases in international trade and global value chain participation impact world economic volatility. I develop and apply a theoretical model of intermediate input trade to data on production networks in order to assess how global network structures affect aggregate volatility. Due to network interconnections between country-sectors, idiosyncratic shocks to specific country-sectors transmit downstream towards their direct and indirect customers, leading to a potential synchronised expansion of economic activity. This mechanism generates sizeable aggregate fluctuations when the importance of country-sectors is significantly asymmetric, leading to the existence of dominant country-sectors which effectively propagate shocks originating elsewhere in the network to the entire economy. By mapping global production networks to data from world input-output tables, I obtain measures for country-sector importance which capture the centrality of each country-sector in the network. The distribution of these centrality measures then provides information about the structure of the global production network and the implications for aggregate volatility. The key empirical result shows that the network structure of global production is highly interconnected with production fragmented across the world economy. This finding implies that idiosyncratic shocks can propagate through the global production network, leading to sizeable aggregate fluctuations. Understanding the underlying structure of global production networks can help policymakers accommodate for international disruptions to global value chains.*

**The Macroeconomic Impact of Dollarisation Adjustments in Cambodia: a Bayesian DSGE Approach**  
BA Dissertation

*This paper develops and estimates a quantitative dynamic stochastic general equilibrium model with partial dollarisation of the Cambodian economy, to evaluate the volatility implications of de-dollarisation. We find that as the level of dollarisation falls, macroeconomic volatility exhibits a U-shape effect. For the initial stage of de-dollarisation, the economy’s improved ability to accommodate asymmetric foreign shocks drives down volatility. However, for the final stages of de-dollarisation, the vulnerability from foreign debt in dollars leads to a rise in volatility. This implies that some degree of dollarisation can achieve a favourable balance between these two opposing effects, minimising macroeconomic volatility.*


<!--
---
# Econometrics

## Repeated *k*-Fold Cross-Validation Estimators

For estimation and inference on heterogenous treatment effects, Chernozhukov et al. (2019) use a repeated split-sample estimator. The benefits of this estimator is to avoid over-fitting the data and other irregularities, but comes at the cost of lower power as only a proportion of the data is used for inference. I am interested to see if a *k*-fold cross-validated estimator could achieve similar benefits, but allowing for the entire data to be used for inference.

The idea is relatively simple. In the split-sample estimator, the data is split into a training sample (A) and a validation sample (B). Conditional average treatment effects (CATE) are estimated using the training sample, then predictions are made using the validation sample, upon which inference is performed. Suppose that *k*=2, then the 2-fold cross-validated estimator would split the data into two samples (A and B) like with the split-sample estimator. The difference is that instead of only obtaining predictions for Sample B using a model trained with Sample A, I supplement this with predictions for Sample A using a model trained with Sample B. Therefore, all the predictions are out-of-sample and inference can then be performed on the entire sample.
-->
---
