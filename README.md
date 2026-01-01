# ICPC 2025 Online Winter Challenge: OXC Ports Arrangement

**Global Rank:** Top 200 (Global Finalist)  
**Peak Rank:** 9th globally during the contest  
**Final Score:** 66,677.164 (Passed 23/23 test cases)

##  Project Summary itself.
This repository contains a solution in C++ PL for the NP-hard network optimization problem. The challenge was asking to determine the optimal configuration for **OXC which is Optical Circuit Switches** in a large-scale AI computing cluster to minimize flow conflicts and adjustment costs.



# 💡 Key Algorithmic Features I used while solving the task
**First what i did**: Tried to deep explicitly into OXC and optimization more precisely, to not miss anything and solve more versatilely
 **Randomized Heuristics:** For this I implemented a custom fast hashing function (`hmix`) and a randomized search engine to explore the solution space within the 5-second time limit.(because, task was demanding time limit per test in 5 seconds)
 **Dynamic Load Balancing:** Developed a system to track real-time load on Leaf-Spine, Spine-OXC, and internal OXC links to prevent bottlenecks.
 **Optimization for Adjustment Cost:** Created a `stealAndConnect` logic to minimize the "edit distance" between physical topology changes, which significantly boosted the final score.

# Performance
 **Maximum Flow Conflict:** Efficiently minimized through greedy flow assignment.
 **Stability:** Successfully handled all queries for N=25 groups and M=288 OXCs.

Developed by Dias Dosanbekov, 10th-grade student at NSPHM.
