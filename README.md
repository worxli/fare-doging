# MATLAB HS12 – Research Plan

> * Group Name: netzwerk
> * Group participants names: Ammann Jens, Bischofberger Lukas
> * Project Title: Ticket inspection behaviour and its influence on fare evasion 

## General Introduction

(States your motivation clearly: why is it important / interesting to solve this problem?)
(Add real-world examples, if any)
(Put the problem into a historical context, from what does it originate? Are there already some proposed solutions?)
Public transportation is of outstanding importance for your society since it ensures the mobility for a brought clientele, independent of social state and physical condition. In order to preserve public transportation and its financing, it is crucial to keep the fare evasion beyond a curtain limit. To realize this, fare evasion behaviour and its interference with the ticket inspection must be researched.

## The Model
The passenger and ticket inspector are represented by agents that show in a first step independent uniform behaviour. In a second step the behaviour of the agent is depends on each other. The mean idea of the passenger behaviour is that the probability of dodging fare increases with the time not being inspected and dodging fare successfully. This can then represent the situation, where ticket inspector plan their routs together and passenger share fare dodging experience. The public transportation net is implemented by a matrix, where the lines represent the different stations and the value of the row the connection to other stations. During the simulation the behaviour of the ticket inspectors is hold constant whereas the fare dodging behaviour of the passenger changes due to their experience and his social environment. 
(Define dependent and independent variables you want to study. Say how you want to measure them.) (Why is your model a good abtraction of the problem you want to study?) (Are you capturing all the relevant aspects of the problem?)

## Fundamental Questions

(At the end of the project you want to find the answer to these questions)
(Formulate a few, clear questions. Articulate them in sub-questions, from the more general to the more specific. )
What behaviour for the passanger leads to realistic results (compared to surveys eg. San Francisco).
What behavoir for the ticket inspectors lead to realistic results?
What is the influence of the ticket inspector behavoir to the behavoir of the passanger?
How can the ticket inspector behaviour be modified to minimize fare evasion?
How can the ticket inspector behaviour be modified to maximize profit?


## Expected Results
We expect that  if the passanger are not share experience a regional focused inspection leads to higher fare evasion rate, as the inspection rate decreases regionally and thus the dodging fare probability increases. 
If on the other hand experience sharing among the passenger is implemented, the evasion rate probably decreases dramatically, cause the passenger “warn” each other of a regional inspection focus.
(What are the answers to the above questions that you expect to find before starting your research?)


## References 

(Add the bibliographic references you intend to use)
(Explain possible extension to the above models)
(Code / Projects Reports of the previous year)
Strategies of the Stakeholders Related with the Behavior of Fare Evasions Based on Game Theory
Author(s): Wu Dan; Qiu Canhua

Source: Proceedings 2011 Fourth International Conference on Information Management, Innovation Management and Industrial Engineering (ICIII 2011) Pages: 94-7  Part: vol.3  Published: 01 2011  DOI: 10.1109/ICIII.2011.308  

Uncovering San Francisco, California, Muni's Proof-of-Payment Patterns to Help Reduce Fare Evasion
Author(s): Lee, J (Lee, Jason)

Source: TRANSPORTATION RESEARCH RECORD  Issue: 2216   Pages: 75-84   DOI: 10.3141/2216-09   Published: 2011

## Research Methods

(Cellular Automata, Agent-Based Model, Continuous Modeling...) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards)

Agent-Based Model (humans can change their behaviour and interact, controllers and environement is static and doesn't change throughout the simulation)
