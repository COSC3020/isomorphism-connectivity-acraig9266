# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

It can be easily disproven that two graphs do not need to be completely connected in order to be isomorphic. Take the two example graphs given below for example:

![example graph](graph.png)

In each of the two graphs above, there is a node that is entirely unattached to the rest of the graph, having no edges connecting it. Therefore, neither graph A or B are completely connected. Despite this, the two example graphs are able to meet the definition of isomorphism. Each node in graph A can be mapped to a node in graph B and vice versa. Node A maps to node D, node B maps to node E, and node C can be mapped to node F. This means there is a one-to-one and onto function between the two graphs and therefore they are isomorphic.
