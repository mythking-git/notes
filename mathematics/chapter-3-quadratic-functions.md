---
description: >-
  "SH: 'The skilful workman will have nothing but the tools which may help him
  in doing his work, but of these, he has a large assortment, and all in the
  most perfect order.'" - Arthur Doyle (1859-1930)
---

# Chapter 3 - Quadratic Functions

{% hint style="info" %}
Chapter 3 requires some manipulation of surds ([chapter-2-surds-and-indices.md](chapter-2-surds-and-indices.md "mention"))
{% endhint %}

## 3.1 - Quadratics graphs and equations

The name _quadratic_ comes from the Latin _quadratus_ and _quad_ meaning 'fourth' or 'made square'. This is because the variable in a regular quadratic expression $$ax^2 + bx + c =0$$, is squared.

### Factorising quadratic expressions

Factorising a quadratic can help you solve for the roots of the graph. It is a key skill and involves finding a way of splitting the middle $$x$$term to factorise, for example:\
$$x^2 + 7x + 12 \\ = x^2 + 4x + 3x + 12 \\ = x(x+4) + 3(x+4) \\ = (x+3)(x+4)$$

***

## 3.2 - The completed square form

A quadratic has the shape of a **parabola**, they will always have:

* A maxima or a minima, which are known as the vertex of the graph.
* A line of symmetry, x = (x-position of vertex).

![](https://assets-global.website-files.com/621ca7b6009267905d98302b/62f2b1f4d0973703b4c0b664\_Vertex%20of%20Parabola%20Maximum.png)

### General formula

To complete the square, you want to get your expression in the form:\
$$ax^2+bx+c \text{ into form } d(x + e)^2 + f \\ ... \\\ a(x^2+\frac{bx}{2a}) +c \\ a[(x+\frac{b}{2a})^2 - (\frac{b}{2a})^2] +c \\ a(x+\frac{b}{2a})^2 - a(\frac{b^2}{4a^2}) + c  \\ \therefore \\a(x+\frac{b}{2a})^2 + (c -\frac{b^2}{4a})$$

```
1. Divide the first 2 terms by a.
2. Factorise by dividing the bx term by 2, and squaring the first 2 terms
3. You must subtract the bx/2a term all squared from this new expression to get
   rid of the C value that would come from expanding it.
4. You can then multiply the out the a from the bracket and add/subtract that from
   the original c value, completing your square.
```

### Roots of graph

When you have completed the square of a quadratic, you can solve for its roots like so:\
$$a(x+b)^2 + c = 0 \\ (x+b)^2 = - \frac{c}{a} \\ x =  \pm\sqrt{\frac{-c}{a}} - b$$

### Vertex/Turning point

The turning point can be found from the completed square...\
$$\text{where } x = -b \\ \text{and } y = c$$\
or in column vector form:\
$$(x,y) \impliedby \begin{pmatrix} -b\\c\end{pmatrix}$$

***

## 3.3 - The quadratic formula

$$x = \frac {-b \pm \sqrt{b^2 -4ac}} {2a}$$

The quadratic formula can easily help you solve the roots of a quadratic.

### The discriminant

The discriminant is the $$b^2-4ac$$ part of the quadratic formula, it tells you that if:\
$$b^2-4ac > 0 \text{, there are two real roots} \\ b^2-4ac = 0 \text{, there is one repeated real roots} \\ b^2-4ac < 0 \text{, there no real roots}$$

#### 16 October 2023
