# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

To disprove that two isomorphic graphs must be completely connected, observe graphs A and B below:

![Isomorphism Connectivity Example](https://github.com/user-attachments/assets/a44d2efe-a87a-4185-9c1a-0a1033ef126d)



In each of the two graphs above, there are disconnected nodes within them (Nodes C and F). This means that neither graph above is completely connected. Despite this, the two example graphs are able to meet the definition of isomorphism. Each node in graph A can be mapped to a node in graph B and vice versa. Node A maps to node D, node B maps to node E, and node C can be mapped to node F. This means there is a one-to-one and onto function between the two graphs since each node in each graph is mapped to by a node in the other graph and each node is only mapped to once. Therefore the two graphs are isomorphic which proves that isomorphic graphs need not be completely connected.
