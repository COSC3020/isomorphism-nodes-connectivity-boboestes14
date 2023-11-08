[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12764694&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


To start this proof let's say that graph $A$ and $B$ have n many nodes, and 
are completely connected. Since it is a completely connected graph the amount 
of edges each node has would be the same as any other node. Since all nodes 
share the same amount of connections this means that any node would be 
indistinguishable from any other node. Since this is the case for both graphs 
this means we can map any one node from $A$ to any other node in $B$. After we 
do this we can do this again for any new set of nodes, since they would still 
have the same amount of connections and would have no differences We can do 
this n many times until we have mapped every node in A to every node in B which 
means that it has to be isomorphic since all the nodes have been mapped to.