---
description: >-
  "As for everything else, so for a mathematical theory - beauty can be
  perceived but not explained" - Arthur Cayley 1883
---

# Chapter 1 - Matrices

## Introduction

A matrix is a rectangular array of numbers called elements.

The order of a matrix is the number of rows and columns

They can be any size:

$$\begin{bmatrix} a & b & c \\ d & e & f \end{bmatrix} or \begin{bmatrix} a \\ b \\ c \end{bmatrix}$$

They are useful for **direct route diagrams**, these can tell you how many direct routes each location has to another, i.e.

$$\overbrace{ \begin{bmatrix} 0 & 2 & 1 \\ 2 & 0 & 0 \\ 1 & 0 & 0\end{bmatrix}}^\text{A B C}$$

***

## 1.1 - Working with Matrices

#### Addition:

$$\begin{pmatrix} 1&4\\ 6&3\end{pmatrix} + \begin{pmatrix} 2 & 5 \\ 9 & 7\end{pmatrix} = \begin{pmatrix} 3 & 9 \\ 15 & 10\end{pmatrix}$$

Matrix addition is both:

* commutative i.e. $$A+B = B+A$$
* associative i.e $$(A+B) + C = A + (B + C)$$

#### Subtraction:

$$\begin{pmatrix} 1&4\\ 6&3\end{pmatrix} - \begin{pmatrix} 2 & 5 \\ 9 & 7\end{pmatrix} = \begin{pmatrix} -1 & -1 \\ -3 & -4\end{pmatrix}$$

Matrix subtraction is similar as it has term-to-term correspondence

$$[A_{ij}] - [B_{ij}] = [A_{ij} - B_{ij}]$$

however, it is not commutative nor associative

***

## 1.2 - Multiplication of Matrices

#### Multiplication:

To multiply two matricies together the numbers of columns in the first matrix and the number of rows in the second matrix must be equal i.e.



&#x20;                                    $$\begin{pmatrix} A & B\\ C & D \end{pmatrix} \cdot \begin{pmatrix} x & y\\ j & k\end{pmatrix} = \begin{pmatrix} Ax + Bj & Ay + By \\ Cx + Cj & Dk + Dk\end{pmatrix}$$

&#x20;                                                               $$2 \times [2  : 2] \times 2$$

&#x20;                                   $$\begin{pmatrix} A & B & C \\ D & E & F\end{pmatrix} \cdot \begin{pmatrix} x \\ y\\ z \end{pmatrix} = \begin{pmatrix} Ax + By + Cz \\ Dx + Ey +Fz\end{pmatrix}$$&#x20;

&#x20;                                                               $$2 \times [3 : 3] \times 1$$\


&#x20;            $${\displaystyle {\begin{pmatrix}7&8\\9&10\\11&12\end{pmatrix}}.{\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix}}={\begin{pmatrix}7+32&14+40&21+48\\9+40&18+50&27+60\\11+48&22+60&33+72\end{pmatrix}}={\begin{pmatrix}39&54&69\\49&68&87\\59&82&105\end{pmatrix}}}$$

The middle two values must match for the matrices to be commutable.

The values on either end form the order of the resultant matrix.

#### Scalar:

Scalar multiplication is much simpler, you simply have to multiply every element in the matrix.

$${\displaystyle 3{\begin{pmatrix}7&8\\9&10\\11&12\end{pmatrix}}={\begin{pmatrix}21&24\\27&30\\33&36\end{pmatrix}}}$$

**Summary:**

$$AB \neq BA$$            $$(AB)C = A(BC)$$      $$A(B+C) = AB+AC$$      $$(B+C)A = BA + CA$$

***

## 1.3 Transformations

A coordinate shows the position of a point in either

$$\text{(3,1) or} \begin{pmatrix}3\\1\end{pmatrix}$$

A position vector shows how to get from the origin to that point

2D transformations can be represented by 2x2 matrices, by multiplying Matrix, _M_, by vector _p_ you can find the position vector, _p'_, of the image

$$\text{Mp = p'}$$

$$\begin{pmatrix}a & b \\ c & d\end{pmatrix} \begin{pmatrix}x \\ y\end{pmatrix} = \begin{pmatrix}x' \\ y'\end{pmatrix}$$

$$\text{x' = ax + by}$$

$$\text{y' = cx + dy}$$

The identity matrix is a matrix that maps a point to it's same position, it is often denoted by:

$${\displaystyle I_{1}={\begin{bmatrix}1\end{bmatrix}},\ I_{2}={\begin{bmatrix}1&0\\0&1\end{bmatrix}},\ I_{3}={\begin{bmatrix}1&0&0\\0&1&0\\0&0&1\end{bmatrix}},\ \dots ,\ I_{n}={\begin{bmatrix}1&0&0&\cdots &0\\0&1&0&\cdots &0\\0&0&1&\cdots &0\\\vdots &\vdots &\vdots &\ddots &\vdots \\0&0&0&\cdots &1\end{bmatrix}}}$$

### 2D Transformations

{% embed url="https://www.geogebra.org/material/iframe/id/FTBjg2bZ/width/980/height/420/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" %}
Geogebra - 2D transformations
{% endembed %}

![](https://upload.wikimedia.org/wikipedia/commons/2/2c/2D\_affine\_transformation\_matrix.svg)

_For shears phi_ $$\phi$$ _and psi_ $$\psi$$ _are used, this can be ignored it is just an integer_

### 3D Transformations&#x20;

For Example:\
From 2D to 3D the transformation matrix $$\begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$$ to reflect an object in the line $$y=x$$ would become $$\begin{pmatrix} 0 & 1 & 0 \\ 1 & 0 & 0 \\ 0 & 0 & 1 \end{pmatrix}$$where the $$x$$ and $$y$$ points are mapped to one another and the $$z$$ value is mapped to itself, in other words, it doesn't change.

\
This is because the line $$y=x$$ is a plane that extends through the $$z$$-plane so any points on that axis stay fixed.

{% embed url="https://www.geogebra.org/material/iframe/id/nfhwspsg/width/1000/height/700/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" %}
Geogebra - 3D Transformations
{% endembed %}

***

## 1.4 - Successive Transformations

A successive transformation is the resultant point after 2 or more transformations.

The transformations need to be multiplied in the reverse order so point P transformed by A, then B, then C, would be calculated via $$C \times(B \times(A \times(P))) = P'$$ or just $$CBA(P) = P'$$

This is sometimes known as the composition of transformations where transformation BA means 'carry out A, then carry out B'.

***

## 1.5 - Invariance

### Invariant Points

Points that are mapped to themselves under a transformation are called invariant points. The origin is always an invariant point under any transformation.

Generally, a point $$(x,y)$$is invariant if it satisfies the matrix equation:\
$$\begin{pmatrix}a & b \\ c & d\end{pmatrix} \begin{pmatrix}x\\y\end{pmatrix} = \begin{pmatrix}x\\y\end{pmatrix}$$\
This results in two simultaneous equations are formed:\
$$0=\begin{cases} x=ax+by \\ y = cd+dy \end{cases}$$

### Invariant Lines

A line AB is known as an invariant line under a transformation if the image of every point on AB is also on AB, as before:&#x20;

$$\begin{pmatrix}a & b \\ c & d\end{pmatrix} \begin{pmatrix}x\\y\end{pmatrix} = \begin{pmatrix}x\\y\end{pmatrix}$$$$\iff x' = ax+by$$ and $$y' = cx+dy$$

yet, as it is a line you can substitute x' for $$x$$ and y for $$mx+c$$, effectively saying:

$$\begin{pmatrix}a & b \\ c & d\end{pmatrix} \begin{pmatrix}x\\y\end{pmatrix} = \begin{pmatrix}x\\mx+c\end{pmatrix} \iff x' = ax+b(mx+c) \text{ and } y' = cx+d(mx+c) \\ \therefore cx+dmx+c = m(ax+bmx+c) + c \\ = cx + dmx + amx + bm^2x + mc = 0 \\ = (bm^2 + am +dm + c)x +m(c) = 0$$

#### October 16 2023
