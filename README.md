[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer

To prove this proposition, it suffices to show an example of two graphs that are isomorphic and not completely connected. Let $A = (V_A , E_A)$ and $B = (V_B , E_B)$ be the two graphs visuallized here:

![image](https://github.com/COSC3020/isomorphism-connectivity-cadenmcfate/assets/113316495/f215d5ed-3751-42c2-9e61-352e8b651fef)

We can clearly see that, although both graphs are not completely connected, there exists a bijection from $V_A$ to $V_B$ such that $(u,v) \in E_A$ iff $(f(u),f(v)) \in E_B$. This function is as follows:

$$
\begin{align}
f: V_A &\to V_B \\
    0 &\mapsto c \\
    1 &\mapsto d \\
    2 &\mapsto e \\
    3 &\mapsto a \\
    4 &\mapsto b
\end{align}
$$

Therefore, if two graphs are isomorphic, they don't have to be completely connected.
