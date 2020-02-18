# Smart data center cooling

One percent of world’s power is consumed by data centers, just to cool themselves. Though data centers use best in class air conditioning, these systems don’t capture a holistic picture of the thermal environment and end up over-cooling, by a whole lot of **35%.** That was a wastage of **11 billion dollars** in 2019, projected to increase at **20%** every year.

With an expertise ranging from managing thermal environments of worlds most complex aero-engines to using machine learning to make systems that learn from and operate on the real world, we aim to manage thermal environments using a system that dynamically controls cooling hardware and learns from its behaviors over time.

### Rapid DC Growth in India

Average Power Usage Effectiveness (PUE) of Data Centers (DCs) across India is [1.7](https://www.osti.gov/servlets/purl/1249186), and since most of them use best-in-class Heating, Ventilation and Air Conditioning (HVAC) systems, there is little that can be done using hardware mods to make cooling in data centers more efficient. On the contrary, with a compound annual growth rate (CAGR) predicted at [20%](https://www.datacenterdynamics.com/en/analysis/indias-data-centers-are-set-growth/), 25 new DCs are built every year (each with an average rack power density of around [8-10 kW](http://bwcio.businessworld.in/article/India-Data-Center-Market-2019-2024/06-02-2019-166872/)) and it is imperative for DCs to look for opportunities to improve their PUE numbers to make the most out of available equipment and have a competitive edge.

[Studies]([https://www.osti.gov/servlets/purl/1249186](https://www.osti.gov/servlets/purl/1249186)) across DCs in India suggest that, for a variety of options with potential to reduce energy consumption, 100% of DC owners prioritized cooling distribution optimization over others as an area with significant energy consumption savings opportunity.
|Level of possibility for enery saving opportunity| Responses received from DC owners |
|--|--|
|Power distribution architecture|42.90%|
|Power conversions|42.90%|
|Harmonics and loss reduction|57.10%|
|Cooling distribution|100%|
|Network architecture|28.60%|
|Server utilization|100%|

Though DCs today use best-in-class HVAC systems coupled with latest available DC management systems, recent advances in machine learning provide an opportunity to better integrate DC management systems and available cooling system controls using nothing more than all available, already recorded IT equipment temperature data.

### We reduce DC cooling energy costs by 40-50% using machine learning

Our company are that opportunity. We aim to understand your current DC architecture and save your DC cooling energy costs by 40-50% using machine learning. Building on [Google's](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/bb67802995f7af4c6ba948ede1acfc8756be7134.pdf) already tried application of reinforcement learning to optimize its DC cooling, we are working to make it possible for our software to understand your DC structure (the equipment you chose to install, the location you chose to set your DC in, the time of the day you want your DC to run most efficient) and cool your DC as needed using as little energy as possible. Our solution is software only and doesn’t require any modifications to hardware of your DCs.

### What do we do?

#### Our current state assumptions
1. Data centers use management [systems]([https://www.sunbirddcim.com/what-is-data-center-management](https://www.sunbirddcim.com/what-is-data-center-management))
2. Data centers read temperatures of servers
3. Data centers have control systems that are used to manage air flow and regulate temperature of servers

The simulation below gives an overview of how the current cooling systems work. Graphs show energy usage.

![Current state cooling](https://media2.giphy.com/media/Stx6jCkmdaxMs/giphy.gif?cid=790b761171a0e0e63bdcde7e95cf2cfd4a1e70200ed3606b&rid=giphy.gif)

#### Our solution
We aim to [apply]([https://arxiv.org/pdf/1908.06973.pdf](https://arxiv.org/pdf/1908.06973.pdf)) Reinforcement Learning (RL) to the control of real-world physical systems. Recent advances in RL emphasize one thing clearly, the ability to read-across the technology and solve problems with much technical complexity. RL provides us with an opportunity to better explore your DCs, understand and learn from your current deployed controls, your server usage statistic and derive better strategies that are proven to provide cooling energy savings of the order of 40-50%.

![enter image description here](http://www.vigilent.com/wp-content/uploads/2013/10/40-achievable-660x443.png)

![Future state cooling](https://media2.giphy.com/media/ijqQ1X9gXwcmc/giphy.gif?cid=790b761171a0e0e63bdcde7e95cf2cfd4a1e70200ed3606b&rid=giphy.gif)

### Heat Transfer meets Machine Learning

We are a team of 2 passionate engineers focused on developing applications that help organisations reduce energy consumption. My co-founder, [Apurva Gupta](https://www.linkedin.com/in/apurva-gupta-74229a30/) is a Mathematics and Computing graduate from IIT Kanpur with expertise in machine learning. I, [Vaibhav Rao](https://www.linkedin.com/in/vaibhavraov/), am a Computational Heat Transfer and Fluid Mechanics post-graduate from BITS Pilani with experience in simulating and optimising thermal environments of Rolls-Royce aero-engines. Together, with our combined expertise, we are looking forward to providing solutions that reduce energy consumption.
