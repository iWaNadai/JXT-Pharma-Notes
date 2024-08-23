---
title: Intro to Chemical Kinetics
tags:
  - pharmaceutical-inorganic-chemistry
date: 2024-08-23
---
***Formulas that appear in this note is also noted here [[Formulas]].*** 
# The of a Reaction
Chemical kinetics is the area of chemistry concerned with the speed or rate at which a chemical reaction occurs.

It is called chemical kinetics because it literally refers to the movement or change ( kinetics ) of a chemical reaction.

A central concept in chemical kinetics is the reaction rate of a chemical reaction.

We can all express chemical reactions simply as such: 

$$\text{reactants}\longrightarrow\text{products}$$

This expression shows us that over a course of time, the reactants involved are consumed to forms the products. 

This observation means we can do the following:
- observe the decrease in concentration of our reactants; and
- observe the increase in concentration of our products.

With this in mind, we can rewrite our expression using the concentration of our reactants ( $A$ ) and the concentration of our products ( $\text{B}$ ).

$$\text{A}\longrightarrow\text{B}$$

This rewritten expression allows us to create expressions for their rates in terms of concentration per unit of time ( seconds ).

$$\text{rate}=-\frac{\Delta\left[A\right]}{\Delta t}\quad\text{or}\quad\text{rate}=\frac{\Delta\left[\text{B}\right]}{\Delta t}$$
In these expressions, the terms $\Delta\left[\text{A}\right]$ and $\Delta\left[\text{B}\right]$ refer to the change of their respective concentration; divided by the change in time or the time elapsed ( $\Delta t$ ).

In the first expression, $\Delta\left[\text{A}\right]$ is a negative quantity because it decreased in concentration, therefor a negative sign is added to make the rate positive; unlike the second expression where $\Delta\left[\text{B}\right]$ is a positive quantity because it increases with time.

## Overall Reaction Rate
If we are given the following chemical reaction:

$$2\text{A}\longrightarrow\text{B}$$

We can make the following observations:
- 2 moles of reactant $\text{A}$ is consumed;
- 1 mole of product $\text{B}$ is formed;
- reactant $\text{A}$ reacts twice as product $\text{B}$;

With these observations, we can determine the overall reaction rate ( $\text{R}_\text{OA}$ ) of our reaction as such:

$$\text{R}_\text{OA}=-\frac{1}{2}\frac{\Delta\left[\text{A}\right]}{\Delta{t}}=\frac{\Delta\left[\text{B}\right]}{\Delta{t}}$$

So if we were given this general reaction:

$$a\text{A}+b\text{B}\longrightarrow{c}\text{C}+d\text{D}$$

we can get this general expression:

$$\text{R}_\text{OA}=-\frac{1}{a}\frac{\Delta\left[\text{A}\right]}{\Delta{t}}=-\frac{1}{b}\frac{\Delta\left[\text{B}\right]}{\Delta{t}}=\frac{1}{c}\frac{\Delta\left[\text{C}\right]}{\Delta{t}}=\frac{1}{d}\frac{\Delta\left[\text{C}\right]}{\Delta{t}}$$

## Other Means to Measure Reaction Rate
Depending on the nature of your reaction, other means and methods to measure reaction rates become available.

For example: in an aqueous solution, molecular bromine reacts with formic acid ( $\text{HCOOH}$) as:

$$\text{Br}_2(aq)+\text{HCOOH}(aq)\longrightarrow{2\text{H}^{+}}(aq)+2\text{Br}^{-}(aq)+\text{CO}_2(g)$$

Molecular bromine is reddish brown and all other species present in the reaction are colorless. As the reaction progresses, the concentration of $\text{Br}_2$ steadily decreases alongside its color.

![[Bromine Visual Reaction Rate.jpg]]

In this scenario, the reaction rate can me measured with the use of a spectrometer. In this reaction, we can plot the concentration of bromine versus time; and the reaction rate is the slope of our tangent ( $\frac{\Delta\left[\text{Br}_2\right]}{\Delta{t}}$ ).

If one of our products or reactants in a reaction is a gas, we can use a manometer to determine the reaction rate. We can do this using a modification of the Ideal Gas Law:

$$PV=nRT\rightarrow{P=\frac{n}{V}RT}\rightarrow{P=MRT}$$

We can modify it further to be used in determining molarity:

$$P=MRT\rightarrow{M=\frac{1}{RT}P}$$

with this final equation, we can turn our concentration ( $M$ ) into a reaction rate ( $\text{M}/\text{s}$ ) and our pressure ( $P$ ) into pressure per unit of time ( $\text{atm}/\text{s}$ ):

$$\text{rate}=\frac{\Delta\left[\text{A}\right]}{\Delta{t}}=\frac{1}{RT}\frac{\Delta{P}}{\Delta{t}}$$
# The Rate Laws
One way to study the effects of reactants concentration ( $\text{M}$ ) is to measure its relationship with your reaction's initial reaction rate ( $\text{M}/\text{s}$ ). We measure the initial rate because as the reactant concentrations decreases over time it may make the measurement of the rate difficult.

If given the following reaction:

$$\text{F}_2(g)+2\text{ClO}_2(g)\longrightarrow2\text{FClO}_2(g)$$

Alongside the following table of data:

| Experiment | $\left[\text{F}_2\right]$ | $\left[\text{ClO}_2\right]$ | Initial Rate ( $\text{M}/\text{s}$ ) |
| ---------- | ------------------------- | --------------------------- | ------------------------------------ |
| 1          | $0.10\text{M}$            | $0.010\text{M}$             | $1.2\times10^{-3}\text{M}/\text{s}$  |
| 2          | $0.10\text{M}$            | $0.040\text{M}$             | $4.8\times10^{-3}\text{M}/\text{s}$  |
| 3          | $0.20\text{M}$            | $0.010\text{M}$             | $2.4\times10^{-3}\text{M}/\text{s}$  |

With the data table below, we can observe the following:
- in experiment 2, we can observe that when we quadruple $\left[\text{ClO}_2\right]$ while keeping $\left[\text{F}_2\right]$ the same, our initial rate is also quadrupled;
- in experiment 3, we can observe that when we keep $\left[\text{ClO}_2\right]$ the same while doubling $\left[\text{F}_2\right]$, our initial rate is also doubled;

From our observation, we can make the claim that the initial rate is proportional to both its reactants' concentrations.

$$\text{initial rate}\propto\left[\text{F}_2\right]\left[\text{ClO}_2\right]$$

This expression can be turned into an equation if we add a rate constant ( $k$ ). 

$$\text{initial rate}=k\left[\text{F}_2\right]\left[\text{ClO}_2\right]$$

The rate constant is a constant of proportionality and is added for the case where the product of reactant concentrations does not equate to the rate.

The previously given equation is not enough to apply to all reactions, because the weight in changing a reactant's concentration varies. In simpler terms: changing the concentration of one reactant affects the rate more than changing the concentration of the other reactant/s.

This is why the proper generic rate law has the exponents $x$ and $y$ as the reactant's respective reaction orders.

$$\text{initial rate}=k\left[\text{A}\right]^{x}\left[\text{B}\right]^{y}$$

If all right-hand values are known ( $k$, $\left[\text{A}\right]$, $\left[\text{B}\right]$, $x$, $y$ ), then we can calculate the rate of our reaction using the rate law.
## Case: Reaction Orders are Unknown
When given a reaction where your reaction orders are unknown, we can use the following formula below:

![[Formulas#Generic Rate Law - Reaction Order Formula]]

If your reaction has two or more reactants, repeat the process for each reactant to obtain all reaction orders.
## Case: Rate Constant is Unknown
In a scenario where all values are known except for your rate constant, use the following formula below:

![[Formulas#Generic Rate Law - Rate Constant Formula]]
## Overall Reaction Order
When using the rate law to calculate different values, it is essential to know what your reaction's overall reaction order. 

A reaction's overall reaction order is calculated using the formula below:

![[Formulas#Overall Reaction Order Formula]]
## The Unit of the Rate Constant
Unlike other variables, the reaction rate constant ( $k$ ) has a unit that changes depending on your reaction order.

To get your appropriate unit, you can use the formula below:

![[Formulas#Rate Constant Unit Formula]]

Or refer to the table below:

| Overall Reaction Rate       | Rate Constant Unit                               |
| --------------------------- | ------------------------------------------------ |
| 0 ( zero-order reaction )   | $\text{M}^1\text{s}^{-1}$ or $\text{M}/\text{s}$ |
| 1 ( first-order reaction )  | $\text{s}^{-1}$                                  |
| 2 ( second-order reaction ) | $\text{M}^{-1}\text{s}^{-1}$                     |
# Relation Between Reactant Concentration and Time
Since the rate laws allows us to calculate the rate of a reaction from its rate constant and reactant concentrations, we can also modify the equation to calculate the concentrations of our reactants at any time during the course of a reaction.

Reactions are classified into orders depending on their overall reaction order, which can be calculated by summing up all of the reactants' reaction orders;

Below is a table containing all the reaction-orders, their rate laws, their concentration-time equations, and their half life equations;

| Order | Rate Law                               | Concentration-Time Equation                                              | Half-Life                                                            |
| ----- | -------------------------------------- | ------------------------------------------------------------------------ | -------------------------------------------------------------------- |
| 0     | $\text{rate}=k$                        | $\left[\text{A}\right]_t=\left[\text{A}\right]_0-kt$                     | $t_{\frac{1}{2}}=\frac{1}{2}\times\frac{\left[\text{A}\right]_0}{k}$ |
| 1     | $\text{rate}=k\left[\text{A}\right]$   | $\left[\text{A}\right]_t=\left[\text{A}\right]_0e^{-kt}$                 | $t_\frac{1}{2}=\frac{0.693}{k}$                                      |
| 2     | $\text{rate}=k\left[\text{A}\right]^2$ | $\frac{1}{\left[\text{A}\right]_t}=kt+\frac{1}{\left[\text{A}\right]_0}$ | $t_\frac{1}{2}=\frac{1}{k\left[\text{A}\right]_0}$                   |
# Activation Energy and Temperature Dependence of Rate Constants
A lot of things in our every day life has its process sped up or slowed down in relation to temperature; for example: much less time is required to hard-boil an egg at higher temperatures, and food stored in cold and low temperature environments take more time to go bad.

This truth also applied to reactions; the reaction rate constant of your reaction is dependent on the initial temperatures.
## The Collision Theory of Chemical Kinetics
The kinetic molecular theory of gases states that gas molecules move and collide with one another frequently, it is also safe to assume that chemical reactions occur per collision between reacting molecules.

In collision theory of chemical kinetics, we expect the rate of a reaction to be directly proportional to the number of molecular collisions per second or to the frequency of molecular collisions:

$$\text{rate}\propto\frac{\text{number of collisions}}{s}$$

But is it necessary to note that not all collisions lead to reactions; calculations on kinetic molecular theory show that at ordinary pressures and temperature ( $1\text{atm}$ and $298\text{K}$ ) there are about $1\times10^{27}$ binary collisions ( collisions between two molecules ) in $1\text{mL}$ of volume every second, in the gas phase, and even more occur in liquids. If all binary collisions led to a product then all reactions would be instantaneous, but they are not in reality.

Any molecules in motion, such as gases, possess kinetic energy; the faster they move, the greater the kinetic energy. Upon the collision of molecules, part of their kinetic energy is converted into vibrational energy. 

If the initial kinetic energies are large then the colliding molecules will vibrate so strongly as to break some of their chemical bonds. This bond fracture is the first step that leads to product formation. On the other hand, if the initial kinetic energies are weak, the molecules will simply bounce off each other. 

Energetically speaking, there is some minimum collision energy below which no reaction occurs.

We postulate, that in order for reactions to occur during molecular collisions, the molecules must have an equal or greater amount of activation energy ( $E_a$ ) in order to exhibit reactions upon collisions; energies below this threshold will leave the molecules intact and no change resulting from the collisions. The species temporarily formed by a binary collision of reactant molecules before a product if formed is called the activation complex or transition state.

![[Reaction Progress - Potential Energy Graph.jpg]]

In the given graphs above, the following can be observed:
- If the reactants has less potential energy than the products, then after reaching the transition state, the reaction will retain some of the energy from the activation energy ( $E_a$ ); this is an endothermic reaction;
- If the reactants has more potential energy than the products, then after reaching the transition state, the reaction will release the excess energy from the activation energy ( $E_a$ ); this is an exothermic reaction;

![[Activation Energy and Change in Enthalpy.jpg]]

In the given diagram, we can see a noticeable hill in our graph, this is our activation energy barrier; the shorter the height of your activation energy barrier, the faster the reaction will take place.
# Reaction Mechanisms
***To be added***
# Catalysis
***To be added***
# Key Definitions
- **Reaction Rate**
	- the rate of a reaction measures how fast a reactant is consumed or how fast a product is formed;
	- the unit of rate is expressed in molars per unit of time ( $\text{M}/\text{s}$ , molars per second );
- **Overall Reaction Rate**
	- the reaction rate of the entire reaction;
	- can be determined by dividing the reaction rate of the reaction's product or reactant by its respective coefficient;
- **Reaction Order**
	- the influence that a reaction's concentration gas on the reaction rate;
- **Rate Constant**
	- the proportionality constant that exists in all generic rate law equations but with varying value;
	- its unit varies and depends on the overall reaction order of the reaction.
- **Rate Laws**
	- due to experimental data, rate laws were made to express the process in simpler terms;
	- it is expressed as the relationship of the rate constants, concentration, and rate order;
	- rate laws are used to determine concentration after a set amount of time as well as a reaction's half life;
- **Temperature Dependence of Rate Constants**
	- in reactions, equal or greater reaction energy is needed;
	- rate constants is directly proportional to the temperature;
- **Activation Energy**
	- The minimum amount of energy needed for molecules to have reactions upon collision.