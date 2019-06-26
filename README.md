# Supply_Chain_Optimization_with_Gurobi

## Data
* Forecast Demand
* Plant Capacity
* Inbound/Outbound/Handling Cost
* Transit Time and Next Day Air Cost

## Questions to Answer
* Does CRS have the right number of DCs and are they in the best locations?
* Does it ever make sense to use Next Day Air?
* What is the tradeoff between customer service and cost?

## Methodology
*Linear Programming with Gurobi*

* Objective Function: 
	* Minimize Total Logistic Cost
* Decision Variables:
	* Inbound decision: From Plant to Distribution Center
	* Outbound decision: From Distribution Center to Customer Zone
* Special Constraints:
	* Number of DCs
	* Maximum Transit Time (days)
	* Customer Demand Satisfied

## Results
For results, please go to my presentation [slides](Supply_Chain_Optimization_Plan.pdf).
