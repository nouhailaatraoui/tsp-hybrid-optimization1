Traveling Salesman Problem – Hybrid Optimization Approach

📌 Project Overview
The Traveling Salesman Problem (TSP) is one of the most studied problems in combinatorial optimization and operations research. The objective is to determine the shortest possible route that visits a set of cities exactly once and returns to the starting city.
Because the TSP is an NP-hard problem, exact algorithms become computationally expensive for large instances. Therefore, heuristic and metaheuristic approaches are commonly used to obtain high-quality approximate solutions.
This project proposes a hybrid optimization approach that combines constructive heuristics, local search, and metaheuristics in order to improve solution quality while maintaining reasonable computation times.
________________________________________

⚙️ Methods Used

The proposed hybrid approach combines three complementary techniques:
1️⃣ Nearest Neighbor (NN)
A constructive heuristic used to quickly generate an initial feasible solution.
2️⃣ 2-opt Local Search
A local improvement heuristic that iteratively removes edge crossings and reduces the total tour distance.
3️⃣ Simulated Annealing (SA)
A metaheuristic inspired by thermodynamics, used to escape local minima by probabilistically accepting worse solutions during the search process.
The combination of these methods allows the algorithm to benefit from:
•	fast solution construction
•	efficient local optimization
•	global exploration of the solution space
________________________________________

📊 Dataset
Experiments were conducted using benchmark instances from the TSPLIB library, a well-known dataset for evaluating algorithms for the Traveling Salesman Problem.
Examples of instances used:
•	eil51
•	berlin52
•	kroA100
________________________________________

🧪 Experimental Results
The hybrid approach significantly improves the quality of the initial solution produced by the Nearest Neighbor heuristic.
Main observations:
•	Reduction in total tour distance
•	Efficient improvement using the 2-opt local search
•	Ability of Simulated Annealing to escape local optima
•	Reasonable computation times for medium-size instances
________________________________________

🚀 How to Run the Project
1.	Clone the repository:
git clone https://github.com/your-username/tsp-hybrid-optimization.git
2.	Navigate to the project directory:
cd tsp-hybrid-optimization
3.	Run the main program:
python main.py
________________________________________


🎯 Academic Context
This project was developed as part of a Master's program in Artificial Intelligence and Operations Research, focusing on the study and implementation of heuristic and metaheuristic methods for combinatorial optimization problems.

