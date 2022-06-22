# An-Economic-Approach-for-Federated-learning-Designing-a-Dynamic-Incentive-Mechanism-Using-Yardstick 
Designing incentive mechanisms to incentivize computing nodes is an interesting topic in the literature on federated learning. In this work, we aim to design a cost-efficient incentive mechanism that minimizes the total cost of the master node that determines the price for each participating node based on the allocated task load. We consider two static and dynamic scenarios. In static scenario worker nodes are pricing based on a linear function of the allocated task load. We assumed selfish workers who aim to maximize their own payoff. Maximizing the pay of function we determined an upper bound for the coefficient α to be able to optimally allocate the tasks. In the dynamic case, our aim is to maximize the social welfare function when the pricing method of the worker is based on the yardstick pricing rule. We used this pricing method because it is proven in the literature that provides the first best solution when we consider symmetric users with the same cost functions. As it is illustrated in the previous section the total cost of the master node is decreased significantly in the dynamic yardstick pricing case compared to the static case. Further in the dynamic case task completion time is decreased compared to the static case.
# Static Scenario
Total cost of master node is determined using the following formula:


<img width="167" alt="image" src="https://user-images.githubusercontent.com/87864575/175113566-0db50372-4b47-4f8c-86d4-51cdec8102c7.png">


where rewards are given using the following equation:



<img width="95" alt="image" src="https://user-images.githubusercontent.com/87864575/175113981-e3fb2129-9255-41d3-823f-93f424ba7a5e.png">



to quarantee the convex payoff maximization problem of workers, alpha should satisfy the following inequality:


<img width="66" alt="image" src="https://user-images.githubusercontent.com/87864575/175114900-7f40a53a-790a-4d1b-b6ae-4cdc078499a7.png">


where cost function and the total completion time for each worker are given as follows:



<img width="92" alt="image" src="https://user-images.githubusercontent.com/87864575/175113385-54ebb7aa-c9df-4d7d-a556-b54a478c4058.png">


<img width="140" alt="image" src="https://user-images.githubusercontent.com/87864575/175113448-4e4f8862-3a82-40a6-8ded-93bd840ba1ef.png">

In the implementation part the total cost of master node and the task completion time for workers considering different allocated task loads to workers are implemented for static case.

# Dynamic Scenario

In the dynamic scenario it is considered that workers are rewarded using yardstick pricing method as follows:

<img width="127" alt="image" src="https://user-images.githubusercontent.com/87864575/175115969-3c8f7795-73f8-4ca2-a2ce-a7e77424587a.png">


For this section considering symmetric workers with the same transmitting power and cost function, the task completion time considerring different allocated task load also total cost of master node is implemented.

# Implementation





