# IT2030_PageRank_Demo
PageRank demonstration for IT2030


Link : https://ducnm517.github.io/IT2030_PageRank_Demo/

# Library used
- d3.js for self-balancing graph in data visualization
- TailwindCSS to save time (this was done on short notice)

# Note
- Algorithm follows PageRank, initial weight for each node is calculated with `max(1,round(2^(log2(nodeCount)-1))) / N` (Formula was chosen by student for visual clarity, this is not standard convention and is not representative of actual PageRank)
- 0.8 CTR (clickthrough rate) is an optimistic assumption to avoid popularity decay during demonstration
