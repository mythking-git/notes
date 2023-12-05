---
description: >-
  "Great things are not done by impulse, but by a series of small things brought
  together." - Vincent Van Gogh 1882
---

# Chapter 4 - Sequences and series

{% hint style="info" %}
Builds on GCSE knowledge of sequences. New notation and terminology is introduced.&#x20;
{% endhint %}

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

## 4.3 - Method of differences

For a sum of a series that can be split into a term by subtracting another term, you can use the method of differences. For example:

$$\frac{1}{r} - \frac{1}{r+1} = \frac{1}{r(r+1)}$$ can be used to calculate a sum of series: $$\sum^{30}_{r=1} \frac{1}{r(r+1)}$$

<figure><img src="../../.gitbook/assets/image (1).png" alt="" width="444"><figcaption></figcaption></figure>

We can see that most of the terms will cancel and we can simply take the first and last terms and solve only them.

## 4.4 - Proof by induction

Proof by induction can be confusing but it is simple if you follow these steps:

* Step 1: Prove that both the left and right-hand sides of the equation will be true when $$n=1$$.
* Step 2: Assume that $$n=k$$ so that it is true for any value of k.
* Step 3: Assume that $$n=k+1$$, so that any value $$n \geq 1$$ is true.
* _(optional)_ Step 4: Write a target expression in terms of $$k+1$$ so you know what to aim for.

Example:

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### Matrices and deductive sums

You may also be asked to prove by induction different types of sums, i.e.,

<figure><img src="../../.gitbook/assets/image (3).png" alt="" width="526"><figcaption><p>Example of deduction proof by induction</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (4).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (5).png" alt="" width="375"><figcaption><p>Example of matrix induction</p></figcaption></figure>
