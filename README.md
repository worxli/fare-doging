# MATLAB HS12 – Research Plan

> * Group Name: netzwerk
> * Group participants names: Ammann Jens, Bischofberger Lukas
> * Project Title: fare-doging

## General Introduction

(States your motivation clearly: why is it important / interesting to solve this problem?)
(Add real-world examples, if any)
(Put the problem into a historical context, from what does it originate? Are there already some proposed solutions?)

A lot of people use public transportation, but also many of them accidentally or intentionally
don't pay for it. From our perspective it would be interesting to see how the behaviour of those who conciously don't buy a ticket changes with the kind of temporal control by the transportation service. 

## The Model

(Define dependent and independent variables you want to study. Say how you want to measure them.) (Why is your model a good abtraction of the problem you want to study?) (Are you capturing all the relevant aspects of the problem?)

We model a set of train routes, which cost a fixed price and have a fixed number of trains on it. We also have a fixed number of people who are able to use the different train routes with a fixed number of rides over a specific time period. Each person has a probability to become a fare-dodger, this probability can change dependent on his social environement (his friend got controlled) or if he himself got into a control.

## Fundamental Questions

(At the end of the project you want to find the answer to these questions)
(Formulate a few, clear questions. Articulate them in sub-questions, from the more general to the more specific. )

What would be the best model for the public transportation company to control the tickets?
How would they have the least people fare-doging?
How would they make the most profit?


## Expected Results

(What are the answers to the above questions that you expect to find before starting your research?)


## References 

(Add the bibliographic references you intend to use)
(Explain possible extension to the above models)
(Code / Projects Reports of the previous year)


## Research Methods

(Cellular Automata, Agent-Based Model, Continuous Modeling...) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards)

Agent-Based Model (humans can change their behaviour and interact, controllers and environement is static and doesn't change throughout the simulation)