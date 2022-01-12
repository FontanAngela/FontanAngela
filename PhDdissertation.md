# PhD Dissertation #
> **A. Fontan**, Collective decision-making on networked systems in presence of antagonistic interactions, Linköping Studies in Science and Technology. Dissertations, No. 2166, 2021.

## Selected publications ##
The following three selected publications show best the progress of my work as a Ph.D. student.

1. **A. Fontan** and C. Altafini, [Multiequilibria Analysis for a Class of Collective Decision-Making Networked Systems](https://ieeexplore.ieee.org/document/8110687), IEEE Transactions on Control of Network Systems, vol. 5 (4), pp. 1931-1940, 2018.

1. **A. Fontan** and C. Altafini, [The role of frustration in collective decision-making dynamical processes on multiagent signed networks](https://ieeexplore.ieee.org/document/9591259), IEEE Transactions on Automatic Control, to appear, 2022. 

1. **A. Fontan** and C. Altafini, [A signed network perspective on the government formation process in parliamentary democracies](https://www.nature.com/articles/s41598-021-84147-3), Scientific Reports, vol. 11 (5134), 2021. 

Papers 2 and 3 formulate a collective decision-making problem over cooperative and antagonistic networks, respectively, as a bifurcation problem, where the crossing of a pitchfork bifurcation corresponds to the achievement of a common decision. The results of Paper 2 admit a natural interpretation in the context of social networks, and Paper 1 proposes a concrete example of political decision-making.

## Research overview
The main research focus of my Ph.D. dissertation (see selected publications) is the study of collective decision-making processes in multiagent systems.

### **Background** ###
The idea of networks of interacting agents exchanging opinions or preferences in order to achieve a common decision as a community is not specific of a particular discipline, and examples of collective behaviors can be observed in everyday life. Typical examples range from collective behaviors in animal groups, such as selection of nest location, food source or migration mechanisms [[1,2,3,4](#references)], to coordination and formation control or task-allocation problems in robotics [[5,6,7](#references)],to opinion formation [[8,9](#references)]. 
The common factor between these examples is that an agreement isreached through collaboration between the agents. However, this assumption may be too restrictive or not very realistic in other scenarios, such as e.g. social networks, trade markets, sport games, or parliamentary systems, where competition among the agents is intrinsic and unavoidable [[10](#references)]. 
In these cases, not only the outcome of the interaction is less clear, but also achieving some form of agreement is not guaranteed. The aim is then to model and investigate decision-making processes in presence of antagonism. Focusing on opinion dynamics on social networks, a natural framework to represent how the agents interact/communicate with each other is given by a state space model with state variables representing the agents’ opinions and a signed network representing the (collaborative and antagonistic) interactions among the agents. To describe how the opinions of the agents evolve in time, several dynamical models have been proposed in the literature (see for instance [[11,12](#references)]).


### **Contributions of selected publications** ###
In my research work, a decision-making process in presence of antagonism is formulated as a nonlinear interconnected dynamical model over signed networks. 
As linear models may fail to capture complex behaviors, the adoption of nonlinearities is motivated by an effort to make the models more realistic. In particular, the selected publications use the model for collective decision-making introduced in [[4](#references)], which is characterized by saturated nonlinearities (describing how the agents transmit their opinion to their neighbors in the network). To extend this model to include competition between the agents (which is not considered in [[4](#references)]), the proposed idea is to consider **signed networks**, i.e., graphs whose edges have positive or negative weight [[13](#references)]), to model cooperation/friendship/trust or competition/antagonism/distrust between the agents. 

The aim is to investigate the behavior of this multiagent system, and to understand how it is affected by the presence of antagonism. Indeed, when competition is taken into account, it may lead to conflicts or social tensions during the decision-making process. To quantify the amount of "disorder" or "social tension" introduced by the antagonistic interactions among the agents, the notion of **"frustration"** of the signed network representing the community is introduced. 
Real-world signed networks, from e.g., biological networks [[14,15,16](#references)] to social networks [[17,18](#references)] and (multi-party) parliamentary networks [[19](#references)], have in general nonzero frustration, which further motivates the analysis. 

In the selected publications, it is shown that the behavior of the nonlinear model can be described by means of **bifurcation analysis**, with the equilibria of the system encoding the possible decisions. From a deadlock situation (i.e., no decision is taken), a decision is reached only if the agents have the **"right" amount of social effort/commitment** (represented as a bifurcation parameter in the model).
While the qualitative bifurcation behavior of the model does not change when antagonistic interactions between the agents are taken into account, at the same time it is shown that **the higher is the "frustration" of the signed network, the higher is the social effort required from the agents to break the deadlock**.

The government formation process in countries with a parliamentary system is a good example of collective decision-making applied to the field of Political Sciences, with parliamentary members (MPs) acting as agents, and vote of confidence given to the post-election candidate cabinet coalition as decision.
The post-election government negotiation talks might be a long and complex process, and the research question is whether it is possible to use the proposed model for collective decision-making to explain this behavior. The approach is to treat the government formation processas a collective decision-making system over a **signed "parliamentary" network** (mapping the post-election parliament), where the **social effort required from the MPs is a proxy for the duration of the government negotiation talks**. 
The hypothesis, supported by the analysis of legislative elections in 29 European countries in the last 40 years, is that **the frustration of the parliamentary network should correlate well with the duration of the government negotiation talks: a long period of negotiations is to be expected when the social tension in the parliament is high**.

## References ##

1. Leonard, *Multi-agent system dynamics: Bifurcation and behavior of animal groups*,Annu. Rev. Control, 2014.
1. Couzinet al., *Uninformed individuals promote democratic consensus in animal groups*,Science, 2011.
1. Swain, Couzin, & Leonard, *Real-Time Feedback-Controlled Robotic Fish for Behavioral Experiments With Fish Schools*, Proceedings of the IEEE, 2012.
1. Gray, Franci, Srivastava, & Leonard, *Multiagent Decision-Making Dynamics Inspired by Honeybees*, IEEE TCNS, 2018.
1. Fax & Murray, *Information Flow and Cooperative Control of Vehicle Formations*, IEEE TAC, 2004.
1. Ren & Beard,Distributed Consensus in Multi-vehicle Cooperative Control. Springer London, 2008.
1. Ren & Cao,Distributed Coordination of Multi-agent Networks. Springer London, 2011.
1. Hegselmann & Krause, *Opinion Dynamics and Bounded Confidence*, J. Artif. Soc. Soc. Simul., 2002.
1. Jia et al., *Opinion Dynamics and the Evolution of Social Power in Influence Networks*, SIAM Review, 2015.
1. Easley & Kleinberg, *Networks, Crowds, and Markets: Reasoning about a Highly Connected World*. Cambridge University Press, 2010.
1. Proskurnikov & Tempo, *A tutorial on modeling and analysis of dynamic social networks. Part I*, Annu. Rev. Control, 2017.
1. Proskurnikov & Tempo, *A tutorial on modeling and analysis of dynamic social networks. Part II*, Annu. Rev. Control, 2018.
1. Zaslavsky, *Signed graphs*, Discrete Applied Mathematics, 1982.
1. Sontag, *Monotone and near-monotone biochemical networks*, Systems and Synthetic Biology, 2007.
1. Iacono et al., *Determining the distance to monotonicity of a biological network: a graph-theoreticalapproach*, IET Systems Biology, 2010.
1. Facchetti, Iacono, & Altafini, *Computing global structural balance in large-scale signed social networks*, PNAS, 2011.
1. Kunegiset al., *Spectral Analysis of Signed Graphs for Clustering, Prediction and Visualization*, in 2010 SIAM International Conference on Data Mining, 2010.
1. Kunegis, *Applications of Structural Balance in Signed Social Networks*, arXiv:1402.6865v1, 2014.
1. Fontan & Altafini, *A signed network perspective on the government formation process in parliamentary democracies*, Scientific Reports, 2021.
