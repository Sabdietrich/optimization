# Optimization - Stable sets for fair communications


Description: Consider an undirected graph where each vertex represents a communicating node.
We have a unique transmission resource that can be used by these nodes (for example some part
of the radio spectrum). Some nodes are geographically close leading to interferences if they try to
communicate in the same time. An edge between two nodes means that they cannot simultaneously
use the transmission resource. The network operator wants to organize communications in a fair
way. The time is slotted, and during one time slot, only a subset of nodes can communicate, then
another subset of nodes use the resources during the next time slot, etc. We want to find the minimum
number of time slots we need to satisfy all nodes (i.e., each node should use the resource during one
of these time slots). This problem is equivalent to partition the vertex set into a minimum number of
stable sets (independent sets). We want to solve the problem using mixed-integer-linear-programming
techniques.

Technical tools: Julia, integer programming, linear programming, valid inequalities, semidefinite programming (possibly)
