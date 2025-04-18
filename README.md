                                 Project Review Summary
 5GNetOptima: Unified Processing, Latency, and Bandwidth Optimization in Next-Generation Networks

 Aim of the Project
 The aim of this project is to optimize the performance of 5G networks by focusing on three key aspects:
 1. Reducing latency
 2. Increasing processing efficiency
 3. Optimizing bandwidth usage

 We use simulation and smart algorithms to model how a 5G network behaves under varying traffic conditions.

 Why We Used This Code
 The MATLAB code simulates a virtual 5G network with:- 
 ->100 nodes and 3 slices
 ->Real-time traffic and latency models
 ->Routing with Dijkstra's algorithm
 ->Bandwidth optimization via WFQ and DBA
 ->Network coding for efficient data transfer
The code allows us to run multiple tests and pick the best route and slice under current traffic conditions.
 
 Methodology
 1. Initialize network (nodes, traffic, slices, bandwidth)
 2. For each slice and simulation step:
5GNetOptima: Project Review Summary
   - Update latency based on traffic
   - Combine data using network coding
   - Apply WFQ and DBA bandwidth allocation
   - Use Dijkstra to find the shortest path
 3. Save the best route and results
 4. Print final best latency, path, bandwidth, and slice
 We implemented both a basic modular version and an optimized parallel version of the code.
 
 Results & Observations
 - Latency reduced by up to 30%
 - Bandwidth usage improved through dynamic allocation
 - Increasing processing units from 2000 to 5000:
  * Reduced blocking probability
  * Improved performance under high load
  * Enabled efficient bandwidth per slice
 
 Bandwidth Optimization Using WFQ and DBA
 WFQ allocates bandwidth proportionally based on slice priority, ensuring fairness.
 DBA adjusts bandwidth in real-time based on demand, preventing waste.
 
 In the code, WFQ is represented by initial slice allocations and DBA is modeled through dynamic
 adjustments.

Conclusion
 5GNetOptima: Project Review Summary
 The project demonstrates how smart routing and bandwidth management can significantly improve 5G
 performance.
 Using simulation, we verified that our optimization methods reduce latency, balance load, and use bandwidth
 efficiently.

 Future work includes adding machine learning models for traffic prediction and scaling to larger networks
