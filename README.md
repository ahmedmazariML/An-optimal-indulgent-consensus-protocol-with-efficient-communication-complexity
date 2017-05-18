# An-Optimal-Indulgent-Consensus-Protocol-with-Efficient-Communication-Complexity
This master thesis in computer science by research in the area of distributed systems and networking presents works and 
recent results obtained in the domain of asynchronous distributed systems based upon consensus problem. The study aims to 
propose an optimal indulgent consensus protocol with efficient communication complexity. An indulgent algorithm is a 
distributed algorithm that tolerates asynchronous periods when failure detectors are unreliable.In our work, we introduce a
new indulgent consensus protocol that optimally solves the problem of consensus. In order to achieve efficiency in term of
the number of exchanged messages and rounds needed, the developed protocol utilizes (t + 1) coordinators to send messages
in each round. The aforementioned protocol guaranties that at least one process decides at (t + 2) round with a complexity 
in number of exchanged messages of O(n.t) and O(t) rounds at most (t + 3).t is the maximum number of failures that a system
can tolerates.
However, the quest for an optimal indulgent algorithm regarding "early-deciding" and "early-stopping" is still open. We 
conclude with the following open problem : Can we find an optimal indulgent consensus algorithm which takes into consideration 
the above mentioned constraints with O(n.t) exchanged messages and O(t) rounds ?
