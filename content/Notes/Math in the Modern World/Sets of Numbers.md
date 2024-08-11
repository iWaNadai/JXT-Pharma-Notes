---
title: Sets of Numbers
tags:
  - mathematics-in-the-modern-world
date: 2024-08-11
---
# Basic Properties of Sets
Sets are an attempt to better understand the world around us; we humans have a knack and preference for classifying similar objects in the same group. Astronomers saw related stars and deemed them part of the same constellations, zoologists saw related animals and deemed them parts of the same family, and etc.

Sets can be designated with two methods:
1. describe the set using words; or ^eb8222
2. write down every member between two curly braces ( $\left\{\dots\right\}$ ), otherwise known as the Roster Method.

Method 1 can be done by simply describing the contents of your set. Some examples of this are: 
- The set of all even numbers.
- The set of all negative numbers.
- The set of all number divisible by 5.

## Basic Number Sets
There are a basic set of numbers and they are often represented by a specific letter written in blackboard bold ( $\mathbb{A, B, C}\dots$ ).

Natural or Counting Number - $\mathbb{N}=\{1,2,3,\dots\}$

Whole Numbers - $\mathbb{W}=\{0,1,2,\dots\}$

Integers - $\mathbb{Z}=\{\dots,-1,0,1\dots\}$

Rational Numbers - $\mathbb{Q}=\text{the set of all terminating or repeating decimals}$

Irrational Numbers - $\mathbb{I}=\text{the set of all nonterminating, nonrepeating decimals}$

Real Numbers - $\mathbb{R}=\text{the set of all rational and irrational numbers}$
## Definition Regarding Sets
A set is well defined if it is possible to determine whether any given item is an element of the set. The set of all letters in the english alphabet is an example of a well defined set because you can easily define its members, whereas the set of all great songs is not a well defined set because it has no standard method to identify its members.

To write in the mathematical language that the number 4 is a natural number, we would write the following:

$$4\in\mathbb{N}$$

To write that an element is not a member of the set, we would write the following:

$$-1\notin\mathbb{N}$$

## Set Builder Notation
Another way to performing [[#^eb8222|method 1]] is to use the mathematical language in a the set builder notation.

An example of a set made with set builder notation is the following: 

$$\{x|x\in\mathbb{N}\text{ and }x>7\}$$

The breakdown for the parts of this expression is the following:

![[The set of all elements x such that x is a natural number and is grater than 7.png]]

# Universal Sets and the Complement of a Set
There exists a set that contains all possible values called the universal set ( denoted as $\mathbb{U}$ ). The opposite of the universal set is the null set ( denoted as $\varnothing$ or $\{\}$ ) and is a set containing nothing.

A complementary set is simply all elements that a particular set needs to become equal to the universal set.

Complementary sets are denoted with prime notation ( ex. the complementary set of set $A$ is $A^\prime$ ).

With this definition for complementary set, we can say that the complementary set of the universal set is a null set.

$$\mathbb{U}^\prime=\varnothing$$

# Subsets
Subsets are sets that are found within another set, this relationship is denoted using the subset operator ( $\subseteq$ ).

If we have a set $A$ and $B$ with the following values:

$$A=\{1,2,3,4,5\}\text{ and }B=\{2,4\}$$

Then we can say that the set $B$ is a subset of set $A$.

$$B\subseteq{A}$$
## The Number of Subsets of a Set
To calculate the number of subsets in a set, count the number of elements in that set and raise 2 to that power.

![[Formulas#The Number of Subsets in a Set]]
