# Smart data center cooling
-   30% of power consumed by data centers (DCs) is used for cooling   
-   Cooling is the biggest hindrance in achieving a Power Usage Effectiveness (PUE) < 1.5 (average of 1.7 across India)

### Efficiency is the need of the hour
Data centers want to reduce energy consumption. There is an observed trend for data centers to move towards
- Buying green power
- Reducing IT costs and efficiently distribute load
- Using best practices and buying A1 class Heating, Ventilation and Air Conditioning (HVAC) systems

Our conversations with data center owners suggest that HVAC systems are managed by manual setpoints. All data centers have ways to control cooling, but aren't trying to optimize cooling.


[Studies]([https://www.osti.gov/servlets/purl/1249186](https://www.osti.gov/servlets/purl/1249186)) across data centers in India suggest that, for a variety of options with potential to reduce energy consumption, 100% of data centers owners prioritized cooling distribution optimization over others as an area with significant energy consumption savings opportunities.
|Level of possibility for energy saving opportunity| Responses received from data center owners |
|--|--|
|Power distribution architecture|42.90%|
|Power conversions|42.90%|
|Harmonics and loss reduction|57.10%|
|Cooling distribution|100%|
|Network architecture|28.60%|
|Server utilization|100%|

### But why aren't they doing it? Why is it difficult to optimize cooling?
-   Optimizing the setpoints/policies for target PUE is difficult
-   Various non-linear feedback loops and interactions happen in a data center, making simulations difficult and inaccurate
	- e.g. if you up the chiller temperature by a degree, what impact will it have on the differential pressure (dp)? This delta dp will cause a change in server fan speeds. How will this affect PUE in the end?
-   It takes dedicated effort from a team of people who know thermal management and optimization techniques

### What are we proposing?
We are proposing to replace manual policies with learnt policies. Two ways to do that:
- Use data to learn the actual behavior of a data center. Use it as a proxy for simulations:
	- Deep networks can model long term dependencies, and non-linear behavior
	- With large enough data set (3-6 months), they can predict PUE better than physics based simulations
	- The simulation can be used to compare manually generated strategies OR
	- Explore and exploit the learnt network through reinforcement learning to automatically come up with policies
- Explore and exploit live in a data center, within constraints
	- We can automatically explore control strategies live in a data center
	- These explorations will be safe, well within defined constraints
	- Learner will model the environment as it explores. Come up with strategies dynamically
-   Compute strategies at the edge, no dependency on external network connections
-   Both approaches improve the performance as more data comes in over time

An example simulation with and without smart control systems show energy expenditure below:

Energy expenditure without smart controls
**![Energy expenditure without smart controls](https://lh5.googleusercontent.com/1r2-6kAN-sgxU4B85OUIFus2w9kTPvuDPyUrX4ZXn2ldPcXuLfaXqwdX2GApdG18VVJmBDOVlqaXEzH-6Lf_nFWk-2Za9heNhpCOunFfO8cnIE_kSntabwmNMggxYxjKha9r_-zEdaU)**

Energy expenditure with smart controls
 **![Energy expenditure with smart controls](https://lh4.googleusercontent.com/8N7zfjcbFshgT41FbniJce6mot2-oOhjU7TVNvTIiOKqd4oB38497N40TsD79kvv9qfGxA-HB-grpPs9dRJ6ZSUJ4ScEupmPBgiCEMUiRNO50R5mOmLHAnadmxYaye1nJQngbAhgz7U)**
### What are we doing now?
- We are creating a miniature data center, to test the strategies in real (miniature) life
- Requesting access to a test data center for experimentation to test our Proof of Concept (PoC) and MVP
- Requesting access to past control and sensor data from real data centers
- Working with a tech adviser from the data center world to help us

### What do we solve for you?
- We Reduce your cooling bill by > 30%
- We are raising external funding: You won’t spend a single penny on our experiments or for the PoC, MVP. We will only ask to be paid when we actually launch the product and it ends up saving money for you
- All data centers are made differently, we wish to work with only 1 real data center in the beginning
- We understand this is a very long process, but we are dedicated to solving this problem, and will put whatever grunt work has to be done to solve it
### Ok, but isn’t it too risky?
## No gain, no pay
We have the perfect zero risk strategy for launch for you! Launch happens in two stages,
-   Stage 1
	-   Person in loop policy
	-   Infrequent policy updates, everything is verified and applied by the person
- Stage 2
	-   If decisions made by system are 5 sigma, system can take over
	-   Person can revert any decision made by system
	-   Detailed monitoring and failover
	-   Fallback to old policies always available
-   Continuous Monitoring and Modelling : All models, decisions will be verified by us
- Clear attribution model
-   Detailed logging
-   Decision attribution will be a part of model and launch

### How can you help us?
- ## Be our advisor!!
We are looking for
- Past sensor and control data from your data center
- Data center industry is very hard for newcomers to crack. Any contacts that can help us !!
- No one listens to two newbies, specially data centers who are mission critical!! We want to build a crack PoC to show this can work! We are looking for your guidance on buidling that perfect PoC
- We need a test data center and compute resources. We are raising external funds for same.
- ### Help us raise funds with your a Letter of Intent :)
If you are trying to reduce data center costs, and would buy our system, a Letter of Intent (LoI) saying so would be very helpful to raise funds. Let us know all the information you need so you can help us with an LoI.

# Roadmaps
**![Product and Technology Roadmap](https://lh5.googleusercontent.com/yaRqGEJNqjP4MWpnE5ZMtS-7sh78cnB3I7gQ5uSY85wjkysUHrhS7ZUgXFq4YrMAHAWlV79w_xMzH6e8JyrgPP53qIp2vRMic0YiPb1HzYdm7RcUi5Iheq9DypjYGeXxq8He5WbvT0w)**
