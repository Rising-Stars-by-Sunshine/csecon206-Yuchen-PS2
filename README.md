# # Problem Set 2: Decipher Game Theory
## Project information
- **Author**: Yuchen Song, Computation and Design with tracks in Computer Science, Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set No.2 for [COMPSCI/ECON 206 Computational Microeconomics, 2023 Spring (Seven Week - Second)](https://ce.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: [How to Acknowledge?](https://www.scribbr.co.uk/thesis-dissertation/acknowledgements/)
[notes: please include all professors, students, and staff who have contributed to your completetion of the project.]
- **Project Summary**: 
  - General introduction of Game Theory: In the Overleaf.zip file, some concepts including history of Game Theory, some important formula of Bayesian Nash Equilibrium, and some glossaries are introduced.
  - Game simulation: In the Code generated from Google Colab, two games with the type of normal/strategic form matrix & extensive form are simulated by Python package Nashpy and Game Theory Explorer respectively.
  
   
Note: please insert the screenshot of the answers to your research question by ChatGPT. The methodology that you use to address the research questions must be more innovative than both the current literature and ChatGPT. 

## Table of Contents

- structure
- spotlight
- more about the author

### Structure
- This project has two parts. The first part is the introduction of some important concepts in Game Theory. In the Overleaf file, the project first summarizes the milestones in Game Theory. Then, it provides the definition, theorem, and proof of Bayesian Nash Equilibrium and some basic discussion about the concepts. Finally, it shows the definition of several important glossaries in Game Theory by citing the original publication. The second part is the simulation of two games in the .ipynb file. The first game is the Chicken Game, which is a classical normal/strategic form matrix game. By using the Python package Nashpy, the project calculates and elaborates the mixed and pure Nash Equilibrium of the game. The second game is the Ultimatum game, which is a typical extensive form game. By using the website Game Theory Explorer, the project generates and discusses strategies.

### Spotlight
[Game theory reflection and exploration in Overleaf](https://github.com/Rising-Stars-by-Sunshine/csecon206-Yuchen-PS2/blob/main/code/CSECON206_ProblemSet2_Spring2023_Yuchen%20(1).pdf)

The Overleaffile, includes the introduction of Game Theory history, some important formula, definitions, theorems and proofs of Bayesian Nash Equilibrium, and Game Theory Glossary Table.

[Normal and extensive form games in Colab]()

Reflection

- Based on the simulation of two games, and the elaboration of their solutions, here are some limitations of the Nash Equilibrium: 
1.	In some games, Nash Equilibrium may not always exist, and in some games, there are several Nash Equilibrium, which is difficult for analysis and predictions. For instance, in Chicken Game, there are three Equilibriums, two are pure strategies and one is mixed strategies. 
2.	Nash Equilibrium assumes that participants are completely rational. However, in real-world scenarios, players cannot perfectly calculate their opponents’ strategies. It may be because of their lack of mathematical ability and the influence of some behavioral, cultural, and other factors. For example, in Chicken Game, to achieve pure strategies, one player should choose to avoid risks, and the other should choose to maximize profits. However, in real situations, participants’ strategies are dynamic and can be influenced by their opponent’s decisions.
3.	Nash Equilibrium does not consider the possibility of cooperation between players. In some games, if players can cooperate with their opponents, they can reach better payoffs, and avoid the risk of retaliation for the annoying decisions. For example, in the Ultimatum game, the Subgame Perfect Nash Equilibrium suggests the payoff of 8 and 2 for players A and B separately, which assumes that Player A is self-interested and won’t choose to equally distribute the money (payoff of 5 and 5). However, if A makes an unfair decision, in real-world situations, B may choose to retaliate, which may lead to 0 payoff for both.


### More about the Author
- headshot
- self-introduction

  Yuchen Song is a sophomore student majored in Computation and Design with tracks in Computer Science at DKU, who is intereted in the intersection between Computer Science and other subjects.


### References

- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

