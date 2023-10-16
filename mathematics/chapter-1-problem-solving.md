---
description: '"Where there are problems, there is life" - Aleksandr Zinoviev (1922-2006)'
---

# Chapter 1 - Problem Solving

{% hint style="info" %}
The work in Chapter 1 pervades the whole book
{% endhint %}

## 1.1 Number Systems

| Number System          | Values                                                                                     | Symbol                        |
| ---------------------- | ------------------------------------------------------------------------------------------ | ----------------------------- |
| Counting Numbers       | $$1,2,3,4,5$$                                                                              | $$\Bbb{Z^+}$$                 |
|                        |                                                                                            |                               |
| Counting Numbers and 0 | $$0,1,2,3,4,5$$                                                                            | $$\Bbb{N}$$ (Natural Numbers) |
| Integers               | $$-2,-1,0,1,2$$                                                                            | $$\Bbb{Z}$$(Cardinal Numbers) |
| Rational Numbers       | $$\frac{m}{n}$$ where $$m$$ and $$n$$ are integers                                         | $$\Bbb{Q}$$ (Quotient)        |
| Real Numbers           | irrational and rational numbers                                                            | $$\Bbb{R}$$                   |
| Complex                | <p>All real and complex numbers<br><em>i.e.</em> <span class="math">1+i\sqrt{3}</span></p> | $$\Bbb{C}$$                   |
| Epsilon                | $$\epsilon$$                                                                               | 'is a member of'              |

&#x20;                                                                **General Expression**

&#x20;                                                              $$$\text {$\Bbb{Z^+}$$\epsilon$ $\Bbb{N}$ $\epsilon$ $\Bbb{Z}$ $\epsilon$ $\Bbb{Q}$ $\epsilon$ $\Bbb{R}$ $\epsilon$ $\Bbb{C}$}$$$

## 1.2 Writing Mathematics

| Name                                    | Symbol                           | Note                              |
| --------------------------------------- | -------------------------------- | --------------------------------- |
| <p>A implies B<br>If A then B</p>       | A $$\implies$$ B                 | A is a sufficient condition for B |
| <p>A is implied by B<br>If B then A</p> | A $$\impliedby$$ B               | A is a necessary condition for B  |
| A implies, and is implied by, B         | A $$\iff$$ B                     |                                   |
| A does not implied B                    | A $$\rlap{\quad\not}\implies$$ B |                                   |



The converse of a theorem is where the $$\implies$$ symbol is flipped to $$\impliedby$$ to express an idea

Thus, the triangle $ABC$, Pythagoras' theorem states\
$$Angle {BCA} = 90^\circ \implies {AB}^2 = {BC}^2 + {CA}^2$$\
and its converse is\
$$Angle {BCA} = 90^\circ \impliedby {AB}^2 = {BC}^2 + {CA}^2$$\
As such, this can be defined as\
$$Angle BCA = 90^\circ \iff {AB}^2 = {BC}^2 + {CA}^2$$

* Necessary is used when giving the conditions under which a statement is true i.e., A living being is a spider$$\implies$$it has eight legs.
* Sufficient is used when a condition can make a certain statement true i.e., A living being has eight legs$$\impliedby$$it is a spider.

## 1.3 Proofs

### Disproving a conjecture

Find any example where this isn't true i.e.\
_All multiples of 3 are multiples of 6_\
$$3 \times 3 = 9$$\
$$9 \div 6 \neq \Bbb{Z}$$

### Proof by deduction

Step-by-step, usually algebraically, i.e.

_The sum of two consecutive squares is always odd._

Let $$n^2$$ be a square number, therefore\
$$(n+1)^2$$ is the next square number.\
The sum would be:

$$n^2+(n+1)^2 \\= n^2 + n^2 + 2n + 1 \\=2n^2 + 2n + 1 \\= 2(n^2+n) + 1$$

2 multiplied by any number is even.\
$$\therefore$$ an even number plus 1 is odd

### Proof by exhaustion

Test every single case. i.e.,&#x20;

_97 is a prime number._

$$97 \div 2 = 48.5 \\ 97 \div 3 = 19.4 \\ ... \\ 97 \div 9 = 10 \frac{7}{9}$$

$$\text{Since none of the numbers divides into 97 exactly, 97 must be prime}$$

### Proof by contradiction

Assume its false then prove you're wrong (so that it is correct).

_If 4 people share £100, one of them must receive at least £25._

```
Assume that the opposite is true that all 4 people receive less than £25.
The most each can receive is £24.99
The maximum total will be 24.99 x 4 = £99.96.
£100 > £99.96, we have a contradiction so the conjecture is true.
```
