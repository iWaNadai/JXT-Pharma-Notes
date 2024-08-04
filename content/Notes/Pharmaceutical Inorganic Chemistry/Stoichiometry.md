---
title: Stoichiometry
tags:
  - pharmaceutical-inorganic-chemistry
date: 2024-08-02
---
# What is Stoichiometry
Stoichiometry is defined as the relationship between the relative quantities of substances taking part in a reaction or forming a compound, typically a ratio of whole integers.

In simple terms, it is the proportions in which specific elements and/or compounds react with one another.

$$N_2+H_2\longrightarrow NH_3\quad\text{when balanced is}\quad N_2+3H_2\longrightarrow 2NH_3$$
# Solving for the Values of a Chemical Reaction
When solving for values of measurements in a chemical reactions, there are two ways to do so; for both methods one must be mindful of the term STP.

STP, stands for Standard Temperature and Pressure. When one is told to assume STP, this means all values not explicitly given a value will get their corresponding values below
- Pressure ($P$) - $1atm$
- Temperature ($T$) - $273.15K$

It is usual to have an understanding and to be familiar with the web of conversions shown below.

![[Web of Conversions.png]]

This web of conversion allows us to visualize the indirect links between units of our reactants and products. Through this web, we can see the conversions we have to conduct in order to get our desired value.

Usually, we first need to draw a path from our given value ( ex. the grams of our reactant, $\text{gram}_x$ ) to our desired value ( ex. the volume of our product, $\text{volume}_y$ ). This will give us an outline of our conversion process.

$$\text{gram}_x\rightarrow\text{mol}_x\rightarrow\text{mol}_y\rightarrow\text{volume}_y$$ ^7baca7

After this step, we then decide on which method we use to get our desired value. We have a choice between the [[#Via Formula Method|Formula Method]] and [[#Via Dimensional Analysis|Dimensional Analysis]].
## Via Formula Method
This method uses formulas for each step in the conversion. It is easy to digest but takes longer to solve.

Each step in our conversion will use the appropriate formula from the collection given below:

![[Units and Conversions#Grams to Moles]] ^7a9279

![[Units and Conversions#Moles to Grams]]

![[Units and Conversions#Liters to Moles]]

![[Units and Conversions#Moles to Liters]] ^ebc0b9

![[Units and Conversions#Number of Particles to Moles]]

![[Units and Conversions#Moles to Number of Particles]]

![[Formulas#Mole Conversion Between Different Molecules Formula]] ^dc5feb

If we were to use the formula method on our previous [[#^7baca7|example]], we would use the following formulas in this order:
1. [[#^7a9279|Grams to moles]] 
2. [[#^dc5feb|Mole conversion between different molecules]]
3. [[#^ebc0b9|Moles to volume]]
## Via Dimensional Analysis
This method has no set formula and relies on the analysis of the units and their proportions to get the final answer. Ideal for efficiency but requires extra effort in the formulation.
### Reinterpreting Derived Units 
Derived units can be expressed in a compact form but it can be reinterpreted as a relationship or a fraction.

$$1g/mol\quad\text{can be interpretted as}\quad\frac{1g}{1mol}$$
Derived units are often use as [[#Conversion Factors]]
### Conversion Factors
Conversion factors are a fractional value that represents the proportional relationship between two units.

In conversion, your given unit would be the unit of your conversion factor's denominator, and your desired unit would be the unit of your conversion factor's numerator.

Below is the gram to mole conversion factor for water.

$$\left(\frac{1mol_{H_2O}}{18.02g_{H_2O}}\right)$$

Below are the conversion factors commonly used dimensional analysis:

Legend:
- $MW_x$ - Molecular weight of element $x$.
- $P_x$ - Pressure of element $x$. ( equal to $1atm$ when assuming STP )
- $V_x$ - Volume of element $x$.
- $T_x$ - Temperature of element $x$. ( equal to $273.15K$ when assuming STP )
- $n_x$ - Number of moles of element $x$.
- $R$ - Gas constant ( $0.08206L\cdot atm/mol\cdot K$ )
- $N_A$ - Avogadro's Number ($6.022\times10^{23}$).
- $Cf_x$ - Coefficient of element $x$.
- $Cf_y$ - Coefficient of element $y$.

- Mole to grams 

 $$\left(\frac{1mol_x}{MW_x}\right)$$ 
  
- Grams to mole

$$\left(\frac{MW_x}{1mol_x}\right)$$

- Mole to volume

$$\left(\frac{RT_x}{P_x}\right)$$

- Volume to mole

$$\left(\frac{P_x}{RT_x}\right)$$

- Particles to mole

$$\left(\frac{n_x}{N_A}\right)$$

- Mole to particle

$$\left(\frac{N_A}{n_x}\right)$$

- Mole to mole

$$\left(\frac{Cf_x}{Cf_y}\right)\text{ or }\left(\frac{Cf_y}{Cf_x}\right)$$

Note: When choosing a conversion factor, remember that your desired unit is the numerator, and your given unit is the denominator.
### Dimensional Analysis Process
Solving using dimensional analysis involves multiplying the given value with all the conversion factors that fit the outline.

If we were to use dimensional analysis on our previous [[#^7baca7|example]], our formula would look like this:

$$\text{grams}_x\left(\frac{1mol_x}{MW_x}\right)\left(\frac{Cf_y}{Cf_x}\right)\left(\frac{RT_y}{P_y}\right)=\text{volume}_y$$

