---
title: Units and Conversions
tags:
  - others
date: 2024-07-23
---
# Units 
- Units for Mass
	- SI Units
		- Kilograms ( $\text{kg}$ )
		- Hectograms ( $\text{hg}$ )
		- Dekagrams ( $\text{dag}$ )
		- Grams ( $\text{g}$ )
		- Decigrams ( $\text{dg}$ )
		- Centigrams ( $\text{cg}$ )
		- Milligrams ( $\text{mg}$ )
- Units for Volume
	- Derived Units 
		- Cubic Centimeter ( $\text{cc}\space\text{or}\space\text{cm}^3$ )
	- SI Units
		- Kiloliters ( $\text{kL}$ )
		- Hectoliters ( $\text{hL}$ )
		- Dekaliters ( $\text{daL}$ )
		- Liters ( $\text{L}$ )
		- Deciliters ( $\text{dL}$ )
		- Centiliters ( $\text{cL}$ )
		- Milliliters ( $\text{mL}$ )
- Units for Pressure
	- Derived Units
		- $\text{N}/\text{m}^2$
		- $\text{kg}/\text{m}\cdot\text{s}^2$
	- SI Units
		- Kilopascals ( $\text{kPa}$ )
		- Hectopascals ( $\text{hPa}$ )
		- Dekapascals ( $\text{daPa}$ )
		- Pascals ( $\text{P}$a )
		- Decipascals ( $\text{dPa}$ )
		- Centipascals ( $\text{cPa}$ )
		- Millipascals ( $\text{mPa}$ )
- Units for Time
	- Seconds ( $\text{s}$ )
	- Minutes ( $\text{m}$ )
	- Hours ( $\text{h}$ )
# Converting Similar SI Units
SI Units share a base10 system, simply multiplying and dividing a number by your current unit and desired unit will be enough for a conversion.

Multiplying value with the appropriate power of 10 is enough for a conversion. (grams are used below but is applicable to all SI Units)

$$0.001\text{kg}=0.01\text{hg}=0.1\text{dag}=1\text{g}=10\text{dg}=100\text{cg}=1000\text{mg}=1000000\mu\text{g}$$

It is recommended to convert back to the base unit if you want to convert from a left-hand unit ($\text{kg}–\text{dag}$) to a right-hand unit ($\text{dg}–\text{mg}$) or vice versa; this recommendation is for the sake of clarity.

Another recommendation is to use dimensional analysis and multiply the given using the following conversion factors ( grams are used as an example).

Note: To convert from grams to other units, just reciprocate the conversion factor.

$\text{kg}\rightarrow\text{g}$ : $$\left(\frac{1000\text{g}}{1\text{kg}}\right)$$

$\text{hg}\rightarrow\text{g}$ : $$\left(\frac{100\text{g}}{1\text{hg}}\right)$$

$\text{dag}\rightarrow\text{g}$ : $$\left(\frac{10\text{dag}}{1\text{g}}\right)$$

$\text{dg}\rightarrow\text{g}$ : $$\left(\frac{1\text{g}}{10\text{dg}}\right)$$

$\text{cg}\rightarrow\text{g}$ : $$\left(\frac{1\text{g}}{100\text{cg}}\right)$$

$\text{mg}\rightarrow\text{g}$ : $$\left(\frac{1g}{1000mg}\right)$$

$\mu\text{g}\rightarrow\text{g}$ : $$\left(\frac{1\text{g}}{1000000\mu\text{g}}\right)$$
# Converting Different SI Units
## Grams to Moles
- Variable:
	- $n_x$ - Moles of the given element $x$
	- $MW_x$ - Molecular weight of the given element $x$
	- $g_x$ - Grams of the given element $x$
- Formula: $$n_x=\frac{g_x}{MW_x}$$
## Moles to Grams
- Variables:
	- $n_x$ - Moles of the given element $x$
	- $MW_x$ - Molecular weight of the given element $x$
	- $g_x$ - Grams of the given element $x$
- Formula: 
	- $$g_x=n_xMW_x$$
## Liters to Volume
- Variables:
	- $V_x$ - Volume of given element $x$.
	- $n_x$ - Number of moles of given element $x$.
	- $R$ - Gas constant ($0.08206L\cdot atm/mol\cdot K$)
	- $T$ - Temperature ($K$)
	- $P$ - Pressure
- Formula: 
	- $$V_x=\frac{n_xRT}{P}$$

See also: [[Formulas#Ideal Gas Law Formula|Ideal Gas Law]]
## Moles to Volume
- Variables:
	- $V_x$ - Volume of given element $x$.
	- $n_x$ - Number of moles of given element $x$.
	- $R$ - Gas constant ($0.08206L\cdot atm/mol\cdot K$)
	- $T$ - Temperature ($K$)
	- $P$ - Pressure
- Formula: 
	- $$n_x=\frac{PV_x}{RT}$$

See also: [[Formulas#Ideal Gas Law Formula|Ideal Gas Law]]
## Number of Particles to Moles
- Variables:
	- $n_x$ - Number of moles of given element $x$.
	- $N_A$ - Avogadro's Number ($6.022\times10^{23}$).
	- $a_x$ - Number of atoms of a given element $x$
- Formula: 
	- $$n_x=\frac{a_x}{N_A}$$
## Moles to Number of Particles
- Variables:
	- $n_x$ - Number of moles of given element $x$.
	- $N_A$ - Avogadro's Number ($6.022\times10^{23}$).
	- $a_x$ - Number of atoms of a given element $x$
- Formula: 
	- $$a_x=n_xN_A$$
# Converting Non SI Units
## Pressure
Formula: $$1atm=760mmHg=760torr=101.3kPa$$
## Temperature
## $\degree F\rightarrow\degree C$ 
Formula: $$\degree C=(\degree F-32)\times\frac{5}{9}$$
## $\degree C\rightarrow K$
Formula: $$K=\degree C+273.15$$


