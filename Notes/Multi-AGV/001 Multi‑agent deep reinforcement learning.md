# Introduction

- **What is a multi-agent system?**
	A multi-agent system describes multiple distributed entities—so-called agents—which 
	take decisions autonomously and interact within a shared environment (Weiss 1999).

- **How do agents work?**
	Each agent seeks to accomplish an assigned goal for which a broad set of skills might be required to build intelligent behavior. Depending on the task, an intricate interplay between agents can occur such that agents start to collaborate or act competitively to excel opponents. 

- **Why RL?**
	Specifying intelligent behavior a-priori through programming is a tough, if not impossible, task for complex systems. Therefore, agents require the ability to adapt and learn over time by themselves.

- **RL history**
	**The ML epoch**
	Stone and Veloso (2000) 
	analyzed multi-agent systems from a machine learning perspective and classified the reviewed literature according to heterogeneous and homogeneous agent structures as well as communication skills. 
	discussed issues associated with each classification. 
	
	Shoham et al. (2003) 
	criticized the ill-posed problem statement of MARL which is in the authors’ opinion unclear and called for more grounded research. 
	proposed a coherent research agenda which includes four directions for future research.
	
	Yang and Gu (2004) 
	reviewed algorithms and pointed out that the main difficulty lies in the generalization to continuous action and state spaces and in the scaling to many agents. 
	
	Busoniu et al. (2008) 
	presented selected algorithms and discussed benefits as well as challenges of MARL. Benefits include computational speed-ups and the possibility of experience sharing between agents. In contrast, drawbacks are the specification of meaningful goals, the non-stationarity of the environment, and the need for coherent coordination in cooperative games. 
	posed challenges such as the exponential increase of computational complexity with the number of agents and the alter-exploration problem where agents must gauge between the acquisition of new knowledge and the exploitation of current knowledge. 
	
	Matignon et al. (2012b) 
	identified challenges for the coordination of independent learners that arise in fully cooperative Markov Games such as non-stationarity, stochasticity, and shadowed equilibria. analyzed conditions under which algorithms can address such coordination issues. 
	
	Tuyls and Weiss (2012) 
	accounted for the historical developments of MARL and evoked non-technical challenges. 
	criticized that the intersection of RL techniques and game theory dominates multiagent learning, which may render the scope of the field too narrow and investigations are limited to simplistic problems such as grid worlds. 
	claimed that the scalability to high numbers of agents and large and continuous spaces are the holy grail of this research domain.
	
	**The DL epoch**
	Nguyen et al. (2020) 
	presented five technical challenges including nonstationarity, partial observability, continuous spaces, training schemes, and transfer learning. They discussed possible solution approaches alongside their practical applications.
	Hernandez-Leal et al. (2019)
	concentrated on four categories including the analysis of emergent behaviors, learning communication, learning cooperation, and agent modeling. Further survey literature focuses on one particular sub-field of MADRL.
	Oroojlooyjadid and Hajinezhad (2019) 
	reviewed recent works in the cooperative setting 
	Da  Silva and Costa (2019) and Da Silva et al. (2019)
	focused on knowledge reuse
	Lazaridou and Baroni (2020) 
	reviewed the emergence of language and connected two perspectives, which comprise the conditions under which language evolves in communities and the ability to solve problems through dynamic communication. 
	Zhang et  al. (2019)
	focused on MARL algorithms and presented challenges from a mathematical perspective.

# Analysis of multi-agent's training schemes
# Emergent patterns of agent behavior
# Current challenges and methods
# Conclusion