# Machine Learning: Improving Auto Insurance Assigning Strategy
- Created an insurance designation model in Python which boosted 2% increase of expected profit 
- Built a two-layer logistic regression model using decision factors analyzed from classification models, simulated expected insurance acceptance rates under different policies

## Executive Summary
In this project, we tried to improve the auto insurance offer assigning strategy so as to reach higher profit for the insurance company. The dataset used contained both the customers personal information and the auto insurance attributes. After experimenting with classification models, we developed a two-layer multinomial logistic regression model with Python, the first layer was to model the process of assigning insurance offer from the company’s perspective, and second layer was to model whether to accept the assigned offer from the customers’ view. Having built up the two-layer logistic regression model, we obtained both the customized probabilities of assigning different insurance offers and the probabilities for a specific customer to accept the offer given. Then we structured two simulation processes for the two layers respectively to get the expected profit for the company under current policy. At last, the expected profit can be increased by 2% by adjusting the feature weights in the logistic regression model. And we recommended that the company should incorporate the factors concerned with accepting offers and adjust their offer products.
