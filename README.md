# An-Economic-Approach-for-Federated-learning-Designing-a-Dynamic-Incentive-Mechanism-Using-Yardstick 
Designing incentive mechanisms to incentivize computing nodes is an interesting topic in the literature on federated learning. In this work, we aim to design a cost-efficient incentive mechanism that minimizes the total cost of the master node that determines the price for each participating node based on the allocated task load. We consider two static and dynamic scenarios. In static scenario worker nodes are pricing based on a linear function of the allocated task load. We assumed selfish workers who aim to maximize their own payoff. Maximizing the pay of function we determined an upper bound for the coefficient α to be able to optimally allocate the tasks. In the dynamic case, our aim is to maximize the social welfare function when the pricing method of the worker is based on the yardstick pricing rule. We used this pricing method because it is proven in the literature that provides the first best solution when we consider symmetric users with the same cost functions. As it is illustrated in the previous section the total cost of the master node is decreased significantly in the dynamic yardstick pricing case compared to the static case. Further in the dynamic case task completion time is decreased compared to the static case.
# Static Scenario
Total cost of master node is determined using the following formula:


<img width="167" alt="image" src="https://user-images.githubusercontent.com/87864575/175113566-0db50372-4b47-4f8c-86d4-51cdec8102c7.png">


where rewards are given using the following equation:



<img width="95" alt="image" src="https://user-images.githubusercontent.com/87864575/175113981-e3fb2129-9255-41d3-823f-93f424ba7a5e.png">



<img width="92" alt="image" src="https://user-images.githubusercontent.com/87864575/175113385-54ebb7aa-c9df-4d7d-a556-b54a478c4058.png">
<img width="140" alt="image" src="https://user-images.githubusercontent.com/87864575/175113448-4e4f8862-3a82-40a6-8ded-93bd840ba1ef.png">


