---
description: >-
  "Probability theory is nothing but common sense reduced to calculation." -
  Pierre Simon Laplace (1749-1827)
---

# Chapter 2 - Discrete Random Variables

{% hint style="info" %}
Uses and required previous knowledge of probability from GCSE, with knowledge of variance and standard deviation.
{% endhint %}

## 2.1 - Notation and conditions for DRV

* A random variable is denoted by an upper case letter, such as X, Y, or Z.
* The values of the random variable are denoted by lowercase letters such as x, y, z or r.
* The sum of all of these lowercase letter values must sum to 1.\
  &#x20;                                                     _or formally:_\
  &#x20;                                            $$\sum_{k=1}^n P(X=r_k)=1$$

## 2.2 - Expectation and variance&#x20;

The expectation denoted by $$\text{E(X)}$$ is equivalent to the $$\sum rP(X=r)$$ it is the mean ($$\mu$$) of the data. It is the most useful measure of central tendency.

The variance denoted by $$\text{Var(X)}$$ is equivalent to the $$\sum r^2 P(X=r) - [\sum r P(X=r)]^2$$ or more simply $$\text{E(X}^2) - \text{[E(X)]}^2$$. The variance is also $$\sigma^2$$, the square of the standard deviation. It is the most useful measure of spread.

### E(X) and Var(X) of a linear function

Expectation: general results

$$\cdot \text{ E(aX+b) = aE(X) + b} \\ \cdot \text{ E(cX) = cE(X)} \\ \cdot \text{ E(d) = d}$$

Variance: general results

$$\cdot \text{ Var(aX) = a}^2\text{Var(X)} \\ \cdot \text{ Var(aX + b) = } a^2\text{Var(X)} \\ \cdot \text{ Var(c) = 0}$$

The reason the variance is not affected by the constant is it is a measure of spread, so there is no change in spread if all values are changed by a constant.

### Sums and differences of random variables

$$\cdot E(X_1 + X_2) = E(X_1) + E(X_2) \\ \cdot E(X_1 - X_2) = E(X_1) - E(X_2)$$

$$\cdot Var(X_1 + X_2) = Var(X_1) + Var(X_2) \\ \cdot Var(X_1 - X_2) = Var(X_1) + Var(X_2)$$

### Linear combinations of two or more random variables

$$E(aX+bY) = aE(X) + bE(Y) \\ Var(aX + bY)  =a^2Var(X) + b^2Var(Y)$$
