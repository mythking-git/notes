---
description: >-
  "Great things are not done by impulse, but by a series of small things brought
  together." - Vincent Van Gogh 1882
---

# Chapter 4 - Sequences and series

## 4.1 - Notation

A **sequence** is an ordered set of objects with an underlying rule.

$$2,5,8,11,14$$

A **series** is the sum of the terms of a numerical sequence.&#x20;

$$2+5+8+11+14$$

&#x20;$$S_n = u_1 +  u_2 + u_3 + ... + u_n = \sum^{n}_{r=1}u_n$$

### Series of positive integers

One of the simplest of all sequences in the sum of positive integers: $$1,2,3,4,5,...$$

$$\sum^{100}_{r=1} r = 1+2+...+100 \implies S_{100} = 1+2+3+...+98+99+100$$

This can be written in reverse and added to itself like so:

$$S_{100} = 1+2+3+...+98+99+100 \\ \underline{S_{100} = 100+99+98+...+3+2+1} \\ 2S_{100} = 101 \times 100 \\ 2S_{100} = 10100 \implies \underline{\underline{S_{100} = 5050}}$$

The general results of this are the sum of $$n$$ integers, $$S_n$$:\
$$S_n = \frac{1}{2}n(n+1)$$

## 4.2 - Standard results

$$\sum a = an \\ \sum r =  \frac{1}{2}n(n+1) \\ \sum r^2 = \frac{1}{6}  n(n+1)(2n+1) \\ \sum r^3 = \frac{1}{4}n^2(n+1)^2$$&#x20;

These can be used to split up compound series into their standard results:\
$$u_r = r^2 + 2r -1 \\ \sum u_r = \sum (r^2+2r-1) \\ = \sum r^2 + 2\sum r - \sum 1 \\ =\frac{1}{6}n(n+1)(2n+1) + 2 \times \frac{1}{2}n(n+1) - n \\ = \frac{1}{6}n(2n^2+9n+1)$$
