---
title: Logic
tags:
  - mathematics-in-the-modern-world
date: 2024-08-12
---
# Logic
Originally a branch of philosophy that made its way into the field of mathematics with the introduction of boolean algebra.

In mathematics, logic is a useful concept to take advantage of in solving problems through logical reasoning.
## Essential Figures
### George Boole
George Boole was born in 1815 in Lincoln, England.

He was raised in poverty, but he was very industrious and had learned Latin and Greek by the age of 12. Later he mastered German, French, and Italian. 

His first profession, at the young age of 16, was that of an assistant school teacher. At the age of 20 he started his own school.

In 1849 Boole was appointed the chairperson of mathematics at Queens College in Cork, Ireland.

Many of Boole’s mathematical ideas, such as Boolean algebra, have applications in the areas of computer programming and the design of electronic circuits.
## Logic Statements
Every language has different types of sentences, such as statements, questions, and commands.

In the symbolic logic that Boole introduced applies only to declarative sentence that is either true or false, but not both true and false.
### Simple Statements and Compound Statements
A simple statement contains one idea and compound statements contain more than one.

This is common knowledge in linguistics but it is also a feature of mathematical logic. When in the context of logic, we can concatenate statements with Truth Values using boolean operators also known as connectives.
### Truth Value and Truth Tables
Truth values are the main focus of logic. The truth value of a variable or expression in logic answers the question: is it true or false?

Truth values are often visualized using truth tables. Truth tables are tabular representations of the truth values of a given expression for every combination of truth values of its variables.

Below is an example of a truth table: 

| $p$ | $q$ | $p\wedge q$ |
| --- | --- | ----------- |
| $T$ | $T$ | $T$         |
| $T$ | $F$ | $F$         |
| $F$ | $T$ | $F$         |
| $F$ | $F$ | $F$         |
### Connectives and Symbols
#### Negation ( $\sim$ )
Negation ( $\sim$ ) is an operation that reverses the truth value of a variable.

If a variable is true, its negated value is false, and vice versa.

| $p$ | $\sim p$ |
| --- | -------- |
| $T$ | $F$      |
| $F$ | $T$      |
#### Conjunction ( $\wedge$ )
Conjunction ( $\wedge$ ) is an operation that functions like the word "and". 

Your expression is only true if your first value and your second value is true.

| $p$ | $q$ | $p\wedge q$ |
| --- | --- | ----------- |
| $T$ | $T$ | $T$         |
| $T$ | $F$ | $F$         |
| $F$ | $T$ | $F$         |
| $F$ | $F$ | $F$         |
#### Disjunction ( $\vee$ )
Disjunction ( $\vee$ ) is an operation that functions like the word "or". 

Your expression is true if your first value or your second value is true.

| $p$ | $q$ | $p\vee q$ |
| --- | --- | --------- |
| $T$ | $T$ | $T$       |
| $T$ | $F$ | $T$       |
| $F$ | $T$ | $T$       |
| $F$ | $F$ | $F$       |
#### Conditional ( $\rightarrow$ )
Conditional ( $\rightarrow$ ) is an operation that functions like the phrase "if... then". 

Your expression is true only if it satisfy's an "if-then" statement.

| $p$ | $q$ | $p\rightarrow q$ |
| --- | --- | ---------------- |
| $T$ | $T$ | $T$              |
| $T$ | $F$ | $F$              |
| $F$ | $T$ | $T$              |
| $F$ | $F$ | $T$              |
#### Biconditional ( $\longleftrightarrow$ )
Biconditional ( $\longleftrightarrow$ ) is an operation that functions like the phrase "if... and only if". 

Your expression is true only if it satisfy's an "if... and only if" statement.

| $p$ | $q$ | $p\longleftrightarrow q$ |
| --- | --- | ------------------------ |
| $T$ | $T$ | $T$                      |
| $T$ | $F$ | $F$                      |
| $F$ | $T$ | $F$                      |
| $F$ | $F$ | $T$                      |
# Key Definitions
- **Logic**
	- A useful tool used to solve problems using logical reasoning.
- **George Boole**
	- A talented man who developed boolean algebra.
- **Statement**
	- In logic, a declarative sentence that is either true ( $T$ ) or false ( $F$ ) but not both.
- **Connective**
	- An alternative term for boolean operators
- **Truth Value** ^bb43cb
	- The truth of a variable or expression in logic; usually visualized using a truth table; can be either true ( $T$ ) or ( $F$ ) but not both.
- **Truth Table**
	- A tabular visualization of all the possible Truth values of a given expression for each possible value of its variables.
- **Negation**
	- $\sim$  ; A boolean operation that changes a variables truth value to its opposite ( true to false, and vice versa );
- **Conjunction**
	- $\wedge$ ; A boolean operation that functions like the word "and"; your expression is only true if both values are true.
- **Disjunction**
	- $\vee$ ; A boolean operation that functions like the word "or"; your expression is true if either or both values are true.
- **Conditional**
	- $\rightarrow$ ; A boolean operation that functions like an "if-then" phrase; your expression is true if it satisfies this format: "if p is true, then q is true".
- **Biconditional**
	- $\longleftrightarrow$ ; A boolean operation that functions like an "if... and only if" phrase; your expression is true if it satisfies this format: "p is true only if q is also true".