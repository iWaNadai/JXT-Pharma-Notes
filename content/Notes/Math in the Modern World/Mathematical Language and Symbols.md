---
title: Mathematical Language and Symbols
tags:
  - mathematics-in-the-modern-world
date: 2024-08-11
---
# The Language of Mathematics
Mathematics is a language with its own notation that we are very well acquainted with; but it is often neglected to teach the origin of this notation.

A long time ago, mathematicians used full sentences to express their formulas.

$$\text{ex. The sum of two real numbers is also a real number.}$$ ^396dcf

We can clearly see the problem with this notation– it's a hassle to write down ––and that is the reason our modern mathematical notation was born.

## The Characteristics of the Mathematical Language
The language of mathematics makes it easy to express the kinds of thoughts that mathematicians like to express; it is inherently intuitive to the group that uses them most.

Mathematics' language is often described as the following:
- Precise
	- It is able to make very fine distinctions.
- Concise
	- It is able to say things briefly.
- Powerful
	- It is able to express complex thoughts with relative ease.

If we were to use our previous [[#^396dcf|example]] and translate it into mathematical notation, we would get the following expression:

$$\forall a,b\in\mathbb{R},a+b\in\mathbb{R}$$

The following are the equivalent meanings of the following parts of the expression above.
- $\forall a,b\in\mathbb{R}$
	- This portion translates to "For all real numbers a and b..."
		- The first symbol ( $\forall$ ) stands for "for all" or "for any". 
		- The second and third symbols ( $a$ and $b$ ) are variables that refer to hypothetical numbers involved in the expression.
		- The fourth symbol ( $\in$ ) stands for "is in" or "is a member of". 
		- The fifth symbol ( $\mathbb{R}$ ) refers to the set of real numbers. ( You may refer [[Sets of Numbers#Basic Number Sets|here]].).
- $a+b\in\mathbb{R}$
	- This portion translates to "...the sum of $a$ and $b$ is a real number".
		- The first three symbols ( $a+b$ ) refers to the sum of $a$ and $b$.
		- The last two symbols ( $\in\mathbb{R}$ ) functions the same way it did in the previous section. It can be read as "is in the set of real numbers" or "is a member of the set of real numbers".
# Expressions vs Sentences
When formulating a sentence one must contain a complete though, the same is true in mathematics; a mathematical sentence must state a complete thought.

An expression, on the other hand, refers to a mathematical object of interest.
## Truth of Sentence
Mathematical sentences may either be **True** or **False**, but never **Both**.
# Unary and Binary Operations
We are mostly familiar with binary operators in mathematics, which are operators that require two operands ( addition for example needs one value on each side ). But there are such things as unary operators which only needs one value (usually on the operator's right).

## Unary Operations
These are operations that only need one value.

A well known example of unary operators is the negative sign.

$$-5$$

Another example of unary operators are trigonometry functions.

$$\sin{\theta},\cos{\theta},\tan{\theta}$$

## Binary Operations
These are operations that only need one value.

An operations is considered binary if it takes two real numbers as arguments to produce another real number.

### Properties of Binary Operations (Addition and Multiplication)
#### Closure of Binary Operations
- The product and the sum of any two real numbers is also a real number.

Expression for Addition: $$\forall a,b\in\mathbb{R},a+b\in\mathbb{R}$$

Expression for Multiplication: $$\forall a,b\in\mathbb{R},a\cdot b\in\mathbb{R}$$

#### Commutativity of Binary Operations
Expression for Addition: $$\forall a,b\in\mathbb{R},a+b=b+a$$

Expression for Multiplication: $$\forall a,b\in\mathbb{R},a\cdot b=b\cdot a$$

#### Associativity of Binary Operations
Expression for Addition: $$\forall a,b,c\in\mathbb{R},(a+b)+c=a+(b+c)$$

Expression for Multiplication: $$\forall a,b,c\in\mathbb{R},(a\cdot b)\cdot c=a\cdot (b\cdot c)$$

#### Distributivity of Binary Operations

$$\forall a,b\in\mathbb{R},c(a+b)=ca+cb$$

#### Identity Elements of Binary Operations
Expression for Addition ( $e$ is equivalent to $0$ ): $$\forall a\in\mathbb{R},a+e=e+a=a$$

Expression for Addition ( $e$ is equivalent to $1$ ): $$\forall a\in\mathbb{R},a\cdot e=e\cdot a=a$$

### Inverse of Binary Operations
$$\forall a\in\mathbb{R},a+(-a)=-a+a$$