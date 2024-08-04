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
	- $T_1$ - First / Initial Temperature ( $K$ )
	- $T_2$ - Second / Final Temperature ( $K$ )
- Formula: $$\frac{P_1V_1}{T_1}=\frac{P_2V_2}{T_2}$$
# Ideal Gas Law Formula
- Use case:
	- When one of the following variables are desired, while the rest are given:
		- Pressure ($P$)
		- Temperature ($T$)
		- Volume ($V$)
		- Number of moles ($n$)
- Variables:
	- $P$ - Pressure
	- $V$ - Volume
	- $T$ - Temperature ($K$)
	- $n$ - Number of moles ($mol$)
	- $R$ - Gas constant ($0.08206L\cdot atm/mol\cdot K$)
- Formula: 
	- $$PV=nRT$$
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
	- $P_2$ - Second Pressure / Final Pressure
	- $T_1$ - First Temperature / Initial Temperature ($K$)
	- $T_2$ - Second Temperature / Final Temperature ($K$)
- Formula: $$\frac{P_1}{T_1}=\frac{P_2}{T_2}$$
# Charles' Law Formula
- Use case:
	- Pressure is constant / Isobaric
	- Pressure is not given.
- Variables:
	- $V_1$ - First / Initial Volume
	- $V_2$ - Second / Final Volume
	- $T_1$ - First / Initial Temperature
	- $T_2$ - Second / Final Temperature
- Formula: $$\frac{V_1}{T_1}=\frac{V_2}{T_2}$$
# Avogadro's Law Formula
- Use case: 
	- Pressure and Temperature are constant / Isobaric and Isothermal
- Variables: 
	- $V_1$ - First / Initial Volume
	- $V_2$ - Second / Final Volume
	- $n_1$ - First / Initial Number of Moles
	- $n_2$ - Second / Final Number of Moles
- Formula: $$\frac{V_1}{n_1}=\frac{V_2}{n_2}$$
# Van der Waal's Real Gas Formula
- Use case:
	- When the problem concerns real gases
- Variables:
	- $R$ - Gas Constant ( $0.08206L\cdot atm/mol\cdot K$ )
	- $P$ - Pressure
	- $n$ - Number of moles of the given gas.
	- $an^2$ - Internal Pressure per mole
	- $nb$ - Incompressibility
- Formula: $$(P+\frac{an^2}{V^2})(V-nb)=nRT$$
# Dalton's Law Formula
- Use case:
	- When asked the partial pressure of a gas
	- Mole fraction is given
	- Total pressure is given
- Variables:
	- $P_T$ - Total Pressure
	- $\chi$ - Mole fraction ( $\frac{n_x}{n_T}$ )
		- $n_x$ - Moles of a particular gas
		- $n_T$ - Total moles within a gas
	- $P_x,P_y,P_z$ - Partial pressure of a particular gas
- Formula for total pressure: $$P_T=P_z+P_y+\cdots P_x$$
- Formula for partial pressure: $$P_x=P_T\chi$$
# Raoult's Law Formula
- Use case:
	- For calculating the vapor pressure of a solution
	- Solvent pressure is given
	- Solvent mole fraction is given
- Variables:
	- $P_\text{solution}$ - Vapor pressure of the solution
	- $\chi_\text{solvent}$ - Mole fraction of the solvent ( $\frac{n_\text{solvent}}{n_\text{solvent}+n_\text{solute}}$ )
		- $n_\text{solvent}$ - Moles of the solvent
		- $n_\text{solute}$ - Moles of the solute
	- $P_\text{solvent}^0$ - Vapor pressure of the pure solvent
- Formula: $$P_\text{solution}=(\chi_\text{solvent})(P_\text{solvent}^0)$$
# Graham's Law Formula
- Use case:
	- To compare the rates of diffusion between two gases
- Variables:
	- $\text{Rate}_1$ - Rate of the first gas
	- $\text{Rate}_2$ - Rate of the second gas
	- $MW_1$ - Molecular weight of the first gas
	- $MW_2$ - Molecular weight of the second gas
- Formula: $$\frac{\text{Rate}_1}{\text{Rate}_2}=\sqrt{\frac{MW_2}{MW_1}}$$
# Fick's 1st Law Formula
- Use case:
	- When asked the flux of a given gas
- Variables:
	- $J$ - Flux (amount of substance per unit area per unit of time)
	- $D$ - Diffusivity (diffusion coefficient)
	- $\varphi$ - Concentration gradient (difference in concentration)
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
- Formula: $M_\text{Total}=M_\text{Ocular}\times M_\text{Objective}$
# Mole Conversion Between Different Molecules Formula
- Use case:
	- When converting from the moles of element $x$ to moles of element $y$ and a balanced chemical equation is given.
- Variables:
	- $Cf_x$ - Coefficient of element $x$ in the balanced chemical equation.
	- $Cf_y$ - Coefficient of element $y$ in the balanced chemical equation.
- Formula: 
	- $$\frac{Cf_x}{Cf_y}$$
