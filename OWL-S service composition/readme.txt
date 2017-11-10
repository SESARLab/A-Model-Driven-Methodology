Set of OWL-S service composition used in the experimental session


Service composition. Upon service selection, the final user manually composes a subset of the selected services to build her 
Big Data campaign. There is, however, a subtlety to consider when services are composed: selections made at declarative level 
could also pose restrictions on the way in which services can be composed. Let us consider again the case for the selection of 
constraint km of k-means. 

• Single value.  ( Comp_sequential_workflow.owls)  When the value of km is a single value, no optimization services will be 
retrieved and composed. This case is supported by our service selection step ). 

• No value. (Comp_while_workflow.owls)  When km is not defined, optimization algorithms are retrieved in the service selection step. In this case, 
a do-while loop must be used to build our OWL-S services selection, where at each step two kmeans executions are followed
by an optimization step (e.g., elbow method). The loop ends according to the optimization function ).

• Range. ( 	Comp_parallel_workflow.owls)  When km is defined as a range, optimization algorithms are retrieved in the service 
selection step. Similarly to the previous case, a do-while loop can be used, though it could be not effective. 
In fact, knowing the different km, a parallel structure can be used to execute km times the k-means algorithm with increasing
km, evaluating the optimization function at the join node of the parallel structure ).

