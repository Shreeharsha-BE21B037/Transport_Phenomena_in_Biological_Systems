# C-F-A Exercise: Gossip Spread Analysis in Social Networks  

## Overview  
This project focuses on analyzing the spread of gossip within a friend group using principles of graph network analysis and Fick’s law of flux. The goal is to model and quantify gossip propagation based on factors such as popularity, closeness, trust levels, and information flux.

---

## 1. Choose  
- **Problem**:  
  Understanding and quantifying the dynamics of gossip spread in a social group.  
- **Relevance**:  
  - Gossip affects group cohesion, trust, and social hierarchies.  
  - Insights can be applied to organizational dynamics, rumor control, and marketing campaigns.  

---

## 2. Focus  
- **Objective**:  
  To model gossip spread as a graph network and analyze the information flow using metrics such as:  
  - Popularity (node degree).  
  - Closeness (shortest path or centrality).  
  - Trust levels (edge weights).  
  - Information flux (Fick’s law of diffusion).  
- **Key Questions**:  
  - Who are the most influential individuals in spreading gossip?  
  - How do trust levels impact the rate and extent of gossip propagation?  
  - What role does network structure play in the diffusion of information?  

---

## 3. Analyze  

### Methodology  
1. **Graph Network Creation**:  
   - **Nodes**: Represent individuals in the friend group.  
   - **Edges**: Represent relationships, weighted by trust levels.  
   - **Popularity**: Quantified by node degree.  

2. **Metrics Calculated**:  
   - **Closeness Centrality**: Identifies nodes that spread information fastest.  
   - **Betweenness Centrality**: Highlights nodes acting as bridges.  
   - **Trust-Weighted Paths**: Shortest paths adjusted for trust levels.  

3. **Flux Analysis Using Fick’s Law**:  
   - Formula:  
      J = -D x dC/dx
     where:  
     - J: Gossip flux (rate of information spread).  
     - D: Diffusion coefficient (based on trust and network density).  
     - dC/dx: Concentration gradient of gossip.  
   - Simulated gossip diffusion to identify hotspots and bottlenecks.  

4. **Simulation**:  
   - Implemented using Python and NetworkX.  
   - Modeled scenarios with varying trust levels and network densities.  

5. **Visualization**:  
   - Graph structures, heatmaps of centrality, and propagation animations.  

## Tools and Technologies  
- **Languages**: Python.  
- **Libraries**: NetworkX, Matplotlib.  
- **Concepts**: Graph theory, Fick’s law of diffusion.  


