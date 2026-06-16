Computational Auction Analysis of Sealed-Bid Auctions Using Auction Theory

This repository contains my independent research project, originally developed as a Treball de Recerca, analysing first-price and second-price sealed-bid auction mechanisms through auction theory, game-theoretic modelling, and Python-based computational simulation.

The project investigates how different auction formats influence strategic bidding behaviour, seller revenue, winner utility, and market efficiency under independent private-value assumptions. By combining microeconomic theory with mathematical modelling and simulation-based analysis, the research evaluates how theoretical auction outcomes compare across repeated computational trials.

Research Overview

Sealed-bid auctions are strategic environments in which bidders submit private offers without observing the valuations or actions of their competitors. This creates a setting of incomplete information, where outcomes depend not only on a bidder’s own valuation, but also on expectations about the behaviour of others.

This project focuses on two core auction mechanisms:

First-price sealed-bid auctions, where the highest bidder wins and pays their own bid
Second-price sealed-bid auctions, also known as Vickrey auctions, where the highest bidder wins but pays the second-highest bid

The research analyses the strategic contrast between these formats: first-price auctions require bid shading to balance winning probability and surplus, while second-price auctions incentivise truthful bidding as a dominant strategy.

Methodology

The computational component uses Python simulations to model auction environments across repeated trials and varying numbers of bidders. Private valuations are randomly generated to represent independent bidder preferences, and auction outcomes are evaluated using mathematical and statistical indicators.

The simulation compares:

Seller revenue across auction formats
Winner utility across different bidder counts
Strategic bid shading in first-price auctions
Truthful bidding incentives in second-price auctions
The effect of increasing competition on auction outcomes
The relationship between theoretical predictions and simulated results
Theoretical Framework

The project draws on concepts from:

Auction theory
Game theory
Bayesian games of incomplete information
Independent private-value models
Utility functions
Bid shading
Dominant strategy equilibrium
Bayesian Nash Equilibrium
Revenue Equivalence Theorem
Risk-neutral and risk-averse bidder behaviour
Key Findings

The simulation results show that seller revenue tends to increase as the number of bidders rises, reflecting the effect of intensified competition on auction prices. At the same time, winner utility decreases as bidder competition compresses the gap between the highest valuation and the final price paid.

The project also highlights a key theoretical distinction between auction formats. In first-price auctions, bidders must strategically shade their bids below their private valuations to preserve surplus while maintaining a chance of winning. In second-price auctions, truthful bidding remains the dominant strategy because the winner’s payment depends on the second-highest bid rather than their own bid.

Overall, the findings support the idea that auction design significantly affects strategic behaviour, market efficiency, and revenue outcomes under conditions of incomplete information.

Skills Demonstrated

Python-based simulation,
Mathematical modelling,
Microeconomic analysis,
Game-theoretic reasoning,
Auction theory,
Data visualisation,
Strategic decision-making analysis,
Research writing,
Quantitative economic modelling,


Citation

Mahmuti, A. (2025). Computational Analysis of Sealed-Bid Auctions Using Auction Theory. Independent research project / Treball de Recerca.
