---
title: Formulas
tags:
  - others
date: 2024-07-23
---
# Combined Gas Law Formula
- Use case:
	- When one of the following variables are desired, while the rest are given:
		- Pressure ($P$)
		- Temperature ($T$)
		- Volume ($V$)
- Variables: 
	- $P_1$ - First / Initial Pressure
	- $P_2$ - Second / Final Pressure
	- $V_1$ - First / Initial Volume
	- $V_2$ - Second / Final Volume
	- $T_1$ - First / Initial Temperature ( $\text{K}$ )
	- $T_2$ - Second / Final Temperature ( $\text{K}$ )
- Formula: $$\frac{P_1V_1}{T_1}=\frac{P_2V_2}{T_2}$$
# Ideal Gas Law Formula
- Use case:
	- When one of the following variables are desired, while the rest are given:
		- Pressure ($P$)
		- Temperature ($T$)
		- Volume ($V$)
		- Number of moles ($n$)
- Variables:
	- $P$ - Pressure ( $\text{atm}$ )
	- $V$ - Volume ( $\text{L}$ )
	- $T$ - Temperature ( $\text{K}$ )
	- $n$ - Number of moles ($mol$)
	- $R$ - Gas constant ($0.08206L\cdot atm/mol\cdot K$)
- Formula: $$PV=nRT$$
# Boyle's Law Formula
- Use Case: 
	- Temperature is constant / Isothermal
	- Temperature is not given or will not be used.
- Variables:
	- $V_1$ - First / Initial Volume 
	- $V_2$ - Second / Final Volume
	- $P_1$ - First / Initial Pressure
	- $P_2$ - Second / Final Pressure
- Formula: $$V_1P_1=V_2P_2$$
# Gay-Lussac's Law Formula
- Use case:
	- Volume is constant / Isovolumetric
	- Volume is not given
- Variables:
	- $P_1$ - First Pressure / Initial Pressure
	- $P_2$ - Second Pressure / Final PressurE
	- $T_1$ - First Temperature / Initial Temperature ( $\text{K}$ )
	- $T_2$ - Second Temperature / Final Temperature ( $\text{K}$ )
- Formula: $$\frac{P_1}{T_1}=\frac{P_2}{T_2}$$
# Charles' Law Formula
- Use case:
	- Pressure is constant / Isobaric
	- Pressure is not given.
- Variables:
	- $V_1$ - First / Initial Volume
	- $V_2$ - Second / Final Volume
	- $T_1$ - First / Initial Temperature ( $\text{K}$ )
	- $T_2$ - Second / Final Temperature  ( $\text{K}$ )
- Formula: $$\frac{V_1}{T_1}=\frac{V_2}{T_2}$$
# Avogadro's Law Formula
- Use case: 
	- Pressure and Temperature are constant / Isobaric and Isothermal
- Variables: 
	- $V_1$ - First / Initial Volume
	- $V_2$ - Second / Final Volume
	- $n_1$ - First / Initial Number of Moles ( $\text{mol}$ )
	- $n_2$ - Second / Final Number of Moles ( $\text{mol}$ )
- Formula: $$\frac{V_1}{n_1}=\frac{V_2}{n_2}$$
# Van der Waal's Real Gas Formula
- Use case:
	- When the problem concerns real gases
- Variables:
	- $R$ - Gas Constant ( $0.08206L\cdot atm/mol\cdot K$ )
	- $P$ - Pressure ( $\text{atm}$ )
	- $n$ - Number of moles of the given gas  ( $\text{mol}$ )
	- $an^2$ - Internal Pressure per mole ( $\text{L}^2\cdot\text{atm}$ )
	- $nb$ - Incompressibility ( $\text{L}/\text{mol}$ )
	- $V$ - Volume ( $\text{L}$ )
	- $T$ - Temperature ( $\text{K}$ )
- Formula: $$(P+\frac{an^2}{V^2})(V-nb)=nRT$$
# Dalton's Law Formula
- Use case:
	- When asked the partial pressure of a gas
	- Mole fraction is given
	- Total pressure is given
- Variables:
	- $P_T$ - Total Pressure ( $\text{atm}$ )
	- $\chi$ - Mole fraction ( $\frac{n_x}{n_T}$ )
		- $n_x$ - Moles of a particular gas ( $\text{mol}$ )
		- $n_T$ - Total moles within a gas ( $\text{mol}$ )
	- $P_x,P_y,P_z$ - Partial pressure of a particular gas ( $\text{atm}$ )
- Formula for total pressure: $$P_T=P_z+P_y+\cdots P_x$$
- Formula for partial pressure: $$P_x=P_T\chi$$
# Raoult's Law Formula
- Use case:
	- For calculating the vapor pressure of a solution
	- Solvent pressure is given
	- Solvent mole fraction is given
- Variables:
	- $P_\text{solution}$ - Vapor pressure of the solution ( $\text{atm}$ )
	- $\chi_\text{solvent}$ - Mole fraction of the solvent ( $\frac{n_\text{solvent}}{n_\text{solvent}+n_\text{solute}}$ )
		- $n_\text{solvent}$ - Moles of the solvent ( $\text{mol}$ )
		- $n_\text{solute}$ - Moles of the solute ( $\text{mol}$ )
	- $P_\text{solvent}^0$ - Vapor pressure of the pure solvent ( $\text{atm}$ )
- Formula: $$P_\text{solution}=(\chi_\text{solvent})(P_\text{solvent}^0)$$
# Graham's Law Formula
- Use case:
	- To compare the rates of diffusion between two gases
- Variables:
	- $\text{Rate}_1$ - Rate of the first gas ( $\text{m}^2/\text{s}$ )
	- $\text{Rate}_2$ - Rate of the second gas ( $\text{m}^2/\text{s}$ )
	- $MW_1$ - Molecular weight of the first gas 
	- $MW_2$ - Molecular weight of the second gas
- Formula: $$\frac{\text{Rate}_1}{\text{Rate}_2}=\sqrt{\frac{MW_2}{MW_1}}$$
# Fick's 1st Law Formula
- Use case:
	- When asked the flux of a given gas
- Variables:
	- $J$ - Flux; amount of substance per unit area per unit of time 
	- $D$ - Diffusivity; diffusion coefficient 
	- $\varphi$ - Concentration gradient; difference in concentration 
	- $x$ - Path length 
- Formula: $$J=-D\frac{d\varphi}{dx}$$
# Formal Charge Formula
- Use case:
	- For determining formal charge
- Variables:
	- $\text{formal charge}$ - The integer charge of the element.
	- $\text{Ve}^-$ - The valence electron of the element.
	- $\text{bond}$ - The number of bonds of the element.
	- $\text{unpaired e}^-$ - The number of unpaired electrons of the element
- Formula: $$\text{formal charge}=\text{Ve}^--\text{bond}-\text{unpaired e}^-$$
# Calculation of Microscope Magnification
- Use case:
	- For logging the magnification used when conducting microscopy.
- Variables:
	- $M_\text{Ocular}$ - Magnification value of the ocular lens ( usually $10\times$  magnification )
	- $M_\text{Objective}$ - Magnification value of the objective lens
		- Scanning Lens = $4\times$
		- Low Power Lens = $10\times$
		- High Power Lens = $40\times$
		- Oil Immersion Objective Lens = $100\times$
	- $M_\text{Total}$ - Total magnification used in your experiment
- Formula: $$M_\text{Total}=M_\text{Ocular}\times M_\text{Objective}$$
# Mole Conversion Between Different Molecules Formula
- Use case:
	- When converting from the moles of element $x$ to moles of element $y$ and a balanced chemical equation is given.
- Variables:
	- $Cf_x$ - Coefficient of element $x$ in the balanced chemical equation ( $\text{mol}$ )
	- $Cf_y$ - Coefficient of element $y$ in the balanced chemical equation ( $\text{mol}$ )
- Formula: $$\frac{Cf_x}{Cf_y}$$
# Grams to Moles Conversion Formula
- Use case:
	- When converting from grams of the element $x$ to moles of the element $x$, and the molecular weight of the element $x$ is given.
- Variables:
	- $n_x$ - Moles of element $x$ ( $\text{mol}$ )
	- $MW_X$ - Molecular weight of element $x$ ( $\text{g}$ )
	- $g_x$ - Grams of element $x$ ( $\text{g}$ )
- Formula: $$n_x=\frac{g_x}{MW_x}$$
# Moles to Grams Conversion Formula
- Use case:
	- When converting from moles of the element $x$ to grams of the element $x$, and the molecular weight of the element $x$ is given.
- Variables:
	- $g_x$ - Grams of element $x$ ( $\text{g}$ )
	- $n_x$ - Moles of element $x$ ( $\text{mol}$ )
	- $MW_X$ - Molecular weight of element $x$ ( $\text{g}$ )
- Formula: $$g_x=n_xMW_x$$
# Moles to Volume Conversion Formula
- Use case:
	- When converting from moles of the element $x$ to volume of the element $x$, and the temperature and pressure is given or is assumed as STP.
- Variables:
	- $V_x$ - Volume of element $x$ ( $\text{L}$ )
	- $n_x$ - Moles of element $x$ ( $\text{mol}$ )
	- $R$ - Gas constant ( $0.08206\text{L}\cdot\text{atm}/\text{mol}\cdot\text{K}$ )
	- $T$ - Temperature ( $\text{K}$ ) { STP: $273.15\text{K}$ }
	- $P$ - Pressure ( $\text{atm}$ ) { STP: $1\text{atm}$ }
- Formula: $$V_x=\frac{n_xRT}{P}$$
# Volume to Moles Conversion Formula
- Use case:
	- When converting from volume of the element $x$ to moles of the element $x$, and the temperature and pressure is given or is assumed as STP.
- Variables:
	- $n_x$ - Moles of element $x$ ( $\text{mol}$ )
	- $P$ - Pressure ( $\text{atm}$ ) { STP: $1\text{atm}$ }
	- $V_x$ - Volume of element $x$ ( $\text{L}$ )
	- $R$ - Gas constant ( $0.08206\text{L}\cdot\text{atm}/\text{mol}\cdot\text{K}$ )
	- $T$ - Temperature ( $\text{K}$ ) { STP: $273.15\text{K}$ }
- Formula: $$n_x=\frac{PV_x}{RT}$$
# Number of Particles to Moles Conversion Formula
- Use case:
	- When converting from number of particles of the element $x$ to moles of the element $x$, and the temperature and pressure is given or is assumed as STP.
- Variables:
	- $n_x$ - Number of moles of element $x$ ( $\text{mol}$ )
	- $a_x$ - Number of atoms of a given element $x$ 
	- $N_A$ - Avogadro's Number ($6.022\times10^{23}\text{mol}^{-1}$).
- Formula: $$n_x=\frac{a_x}{N_A}$$
# Moles to Number of Particles Conversion Formula

- Use case:
	- When converting from number of particles of the element $x$ to moles of the element $x$, and the temperature and pressure is given or is assumed as STP.
- Variables:
	- $a_x$ - Number of atoms of a given element $x$ 
	- $n_x$ - Number of moles of element $x$ ( $\text{mol}$ )
	- $N_A$ - Avogadro's Number ($6.022\times10^{23}\text{mol}^{-1}$).
- Formula: $$a_x=n_xN_A$$
# The Number of Subsets in a Set
- Use case:
	- When calculating the number of subsets in a set
- Variables:
	- $|A|$ - Number of elements in a set
- Formula: $$\text{Number of subsets}=2^{|A|}$$
# Calculating the Change of Variable formula
- Use case:
	- When calculating the value of a variable with a leading capital delta symbol ( $\Delta$ ).
- Variables:
	- $\Delta{a}$ - The change in variable $a$;
	- $a_\text{final}$ - The final value of variable $a$; the last value;
	- $a_\text{initial}$ - The initial value of variable $a$; the starting value;
- Formula: $$\Delta{a}=a_\text{final}-a_\text{initial}$$
# Reaction Rate of a Reactant Formula
- Use case:
	- when determining the reaction rate of a reactant $\text{A}$ in terms of molars per second ( $\text{M}/\text{s}$ )
- Variables:
	- $\Delta\left[\text{A}\right]$ - the change in concentration of the reactant $\text{A}$. ( $\text{M}$ )
	- $\Delta t$ - the change in time; the time elapsed. ( $\text{s}$ )
- Formula: $$-\frac{\Delta\left[\text{A}\right]}{\Delta{t}}$$
# Reaction Rate of a Product Formula
- Use case:
	- when determining the reaction rate of a product $\text{B}$ in terms of molars per second ( $\text{M}/\text{s}$ )
- Variables:
	- $\Delta\left[\text{B}\right]$ - the change in concentration of the product $\text{B}$. ( $\text{M}$ )
	- $\Delta t$ - the change in time; the time elapsed. ( $\text{s}$ )
- Formula: $$\frac{\Delta\left[\text{B}\right]}{\Delta{t}}$$
# Overall Reaction Rate with a Reactant Formula
- Use case:
	- When determining the overall reaction rate ( $\text{M}/\text{s}$ ), given the full balanced equation or the coefficient of one of the reactants;
- Variables:
	- $Cf_\text{A}$ - The coefficient of reactant $\text{A}$ in the balanced equation
	- $\Delta\left[\text{A}\right]$ - The change in concentration of the reactant $\text{A}$. ( $\text{M}$ )
	- $\Delta{t}$ - The change in time; the time elapsed. ( $\text{s}$ )
- Formula: $$\text{R}_\text{OA}=-\frac{1}{Cf_\text{A}}\frac{\Delta\left[\text{A}\right]}{\Delta{t}}$$
# Overall Reaction Rate with a Product Formula
- Use case:
	- When determining the overall reaction rate ( $\text{M}/\text{s}$ ), given the full balanced equation or the coefficient of one of the products;
- Variables:
	- $Cf_\text{B}$ - The coefficient of product $\text{B}$ in the balanced equation.
	- $\Delta\left[\text{B}\right]$ - The change in concentration of the product $\text{B}$. ( $\text{M}$ )
	- $\Delta{t}$ - The change in time; the time elapsed. ( $\text{s}$ )
- Formula: $$\text{R}_\text{OA}=\frac{1}{Cf_\text{B}}\frac{\Delta\left[\text{B}\right]}{\Delta{t}}$$
# Modified Ideal Gas Law using Molarity
- Use case:
	- For determining Ideal Gas Law variables with molarity as a given or desired value;
- Variables:
	- $P$ - Pressure ( $\text{atm}$ ) { STP: $1\text{atm}$ }
	- $M$ - Concentration; molarity ( $\text{M}$ );
	- $R$ - Gas Constant ( $0.08206\text{L}\cdot\text{atm}/\text{mol}\cdot\text{K}$ )
	- $T$ - Temperature ( $\text{K}$ ) {STP: $273.15\text{K}$ }
- Formula: $$P=MRT$$
# Modified Ideal Gas Law for Determining Pressure Change Rate
- Use case:
	- For determining the change in pressure per change of $\text{A}$ in time when given the reaction rate.
	- For determining the reaction rate of $\text{A}$ when given the change in pressure per change in time.
- Variables:
	- $\frac{\Delta{P}}{\Delta{t}}$ - The change in pressure per change in time ( $\text{atm}/\text{s}$ )
	- $\frac{\Delta\left[\text{A}\right]}{\Delta{t}}$ - The reaction rate; the change in concentration per change in time ( $\text{M}/\text{s}$ )
	- $R$ - Gas Constant ( $0.08206\text{L}\cdot\text{atm}/\text{mol}\cdot\text{K}$ );
	- $T$ - Temperature ( $\text{K}$ ) { STP: $273.15K$ }
- Formula: $$\frac{\Delta{P}}{\Delta{t}}=\frac{\Delta\left[\text{A}\right]}{\Delta{t}}RT$$
# Generic Rate Law Formula
- Use case:
	- For calculating the rate of a reaction ( $\text{M}/\text{s}$ ) using rate constant and the given reactant's concentrations and reaction orders;
	- This formula is applicable for reactions any one or more reactants
- Variables:
	- $\text{rate}$ - Reaction rate ( $\text{M}/\text{s}$ );
	- $k$ - Rate constant ( value varies per reaction );
	- $\left[\text{A}\right]$ - Concentration of first reactant ( $\text{M}$ );
	- $\left[\text{B}\right]$ - Concentration of second reactant ( $\text{M}$ );
	- $\left[\text{N}\right]$ - Concentration of nth reactant ( $\text{M}$ );
	- $x$ - Reaction order of your first reactant;
	-  $y$ - Reaction order of your second reactant;
	-  $n$ - Reaction order of your nth reactant;
- Formula: $$\text{rate}=k\left[\text{A}\right]^x\left[\text{B}\right]^y\cdots\left[\text{N}\right]^n$$
# Generic Rate Law - Reaction Order Formula
- Use case:
	- For calculating the reaction order of a reaction using the generic rate law;
	- Use two sets of experimental data where the values of the other reactants are equal on both experiments.
- Variables:
	- $x$ - Reaction order of reactant;
	- $\text{rate}_1$ - Reaction rate of your first experiment ( $\text{M}/\text{s}$ )
	- $\text{rate}_2$ - Reaction rate of your second experiment ( $\text{M}/\text{s}$ )
	- $\left[\text{A}\right]_1$ - Concentration of your reactant in the first experiment ( $\text{M}$ )
	- $\left[\text{A}\right]_2$ - Concentration of your reactant in the second experiment ( $\text{M}$ )
- Formula: $$x=\frac{\log\left(\frac{\text{rate}_1}{\text{rate}_2}\right)}{\log\left(\frac{\left[\text{A}\right]_1}{\left[\text{A}\right]_2}\right)}$$
# Generic Rate Law - Rate Constant Formula
- Use case:
	- For calculating the rate constant of a reaction using the generic rate law;
	- use one set of experimental data;
- Variables:
	- $k$ - Reaction rate constant;
	- $\text{rate}$ - Reaction rate ( $\text{M}/\text{s}$ )
	- $\left[\text{A}\right]$ - Concentration of first reactant ( $\text{M}$ )
	- $\left[\text{B}\right]$ - Concentration of second reactant ( $\text{M}$ )
	- $\left[\text{N}\right]$ - Concentration of nth reactant ( $\text{M}$ )
	- $x$ - Reaction order of your first reactant ( $\text{M}$ )
	- $y$ - Reaction order of your second reactant ( $\text{M}$ )
	- $n$ - Reaction order of your nth reactant ( $\text{M}$ )
- Formula: $$k=\frac{\text{rate}}{\left[\text{A}\right]^x\left[\text{B}\right]^y\cdots\left[\text{N}\right]^n}$$
# Overall Reaction Order Formula
- Use case:
	- For calculating the overall reaction order when all reaction orders are known.
- Variables:
	- $\text{RO}_\text{OA}$ - Overall Reaction Order;
	- $\sum$ - "the sum of all—";
	- $x$ - reaction order; the exponent of your reactant's concentration
		- $x_1$ - first reactant's reaction order;
		- $x_2$ - second reactant's reaction order;
		- $x_n$ - nth reactant's reaction order;
- Formula: $$\text{RO}_\text{OA}=\sum{x}\quad\text{or}\quad\text{RO}_\text{OA}=x_1+x_2+\cdots+x_n$$
# Rate Constant Unit Formula
- Use case:
	- For determining the unit of your rate constant ( $k$ ).
- Variables:
	- $\text{RO}_\text{OA}$ - Overall reaction rate;
- Formula: $$\text{unit}=\text{M}^{1-\text{RO}_\text{OA}}\text{s}^{-1}$$
# Least Weighable Quantity Formula
- Use case:
	- For calculating the least weighable quantity.
- Variables:
	- $\text{LWQ}$ - Least weighable quantity.
	- $\text{sens req}$ - Sensitivity requirement of weighing device.
	- $\text{err\%}$ - Acceptable percentage of errors.
- Formula: $$\text{LWQ}=\frac{100\times\text{sens req}}{\text{err\%}}$$
# Aliquot Amount Formula
- Use case:
	- Calculating amount of aliquot.
- Variables:
	- $\text{a}_\text{aliqot}$ - amount of aliquot.
	- $\text{a}_\text{desired}$ - desired amount.
	- $\text{f}$ - aliquot factor
- Formula: $$\text{a}_\text{aliquot}=\text{a}_\text{desired}\times{f}$$
# Total Aliquot Mixture Formula
- Use case:
	- Calculating amount of total aliquot mixture.
- Variables:
	- $\text{a}_\text{total}$ - Total amount of mixture.
	- $\text{a}_\text{aliquot}$ - amount of aliquot.
	- $\text{f}$ - aliquot factor
- Formula: $$\text{a}_\text{total}=\text{a}_\text{aliquot}\times{f}$$
# Aliquot Diluent Formula
- Use case:
	- Calculating amount of total aliquot mixture.
- Variables:
	- $\text{a}_\text{diluent}$ - amount of diluent.
	- $\text{a}_\text{total}$ - total amount of mixture.
	- $\text{a}_\text{aliquot}$ - amount of aliquot
- Formula: $$\text{a}_\text{diluent}=\text{a}_\text{total}-\text{a}_\text{aliquot}$$
# Aliquot Ratio Formula
- Use case:
	- Calculating the fraction of the total mixture that contains the desired amount of substance.
- Variables:
	- $a_\text{weighed}$ - amount of total mixture to be weighed that contains desired amount of substance.
	- $a_\text{desired}$ - desired amount of substance
	- $a_\text{total}$ - total amount of mixture
	- $a_\text{aliquot}$ - amount of aliquot.
- Formula: $$\frac{a_\text{weighed}}{a_\text{desired}}=\frac{a_\text{total}}{a_\text{aliquot}}$$
# Percentage Error Formula
- Use case:
	- for calculating the percentage of error in a measurement.
- Variables:
	- $\text{err\%}$ - percentage of error.
	- $\text{err}_\text{measurement}$ - the amount of error in a measurement
	- $q_\text{desired}$ - desired or expected quantity.
- Formula: $$\text{err\%}=\frac{\text{err}_\text{measurement}}{q_\text{desired}}\times100\%$$
# Density Formula
- Use case:
	- for calculating the density of a substance.
- Variables:
	- $\rho$ - density of a substance
	- $m$ - mass of a substance
	- $V$ - volume of a substance
- Formula: $$\rho=\frac{m}{V}$$
# Specific Gravity Formula
- Use case:
	- for calculating specific gravity of a substance
- Variables:
	- $\text{sp gr}$ - specific gravity of a substance
	- $m_\text{substance}$ - weight of a volume of substance
	- $m_\text{water}$ - weight of equal volumes of water
- Formula: $$\text{sp gr}=\frac{m_\text{substance}}{m_\text{water}}$$
# Specific Volume Formula
- Use case:
	- for calculating specific volume of a substance
- Variables:
	- $\text{sp vol}$ - specific volume of a substance
	- $v_\text{substance}$ - volume of a weight of substance
	- $v_\text{water}$ - volume of equal weight of water
- Formula: $$\text{sp vol}=\frac{v_\text{substance}}{v_\text{volume}}$$