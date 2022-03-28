# AB Testing 
## About the Problem  : - 
<p><i>
    As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention and game rounds.
  </i>
</p>

## Solution :- 
<p>
  Firstly I analyzed the data and there was no missing value but there was one outlier in the data. Summary stats and plots help us to understand the data and problem. 
  <br>
   we shared some details about game. 
  <br>
  After applying A/B Testing, the analysis result gives us some important information. Shapiro Testing rejected H0 for Normality assumption. Therefore we needed to apply a Non-parametric test as called Mann Whitney U to compare two groups. As a result, Mann Whitney U Testing rejected H0 hypothesis and we learned A/B groups are not similar! 
  <br>
  Briefly, There are statistically significant difference between two groups about moving first gate from level 30 to level 40 for game rounds.
</p>

## Language used: - 
Python

## FrameWorks and Modules: -
Numpy,Pandas, Seaborn, matplotlib, Scipy  


## Want to contribute ?
1. Fork the project and clone it.
2. create a different branch.
3. Install the required libraries.
4. change the code.
5. Make sure to follow the [PEP-8](https://www.python.org/dev/peps/pep-0008/) style guide. 
6. Push the code and make a Pull requests with a brief introduction of the changes made. 

 <p align="center">Made with :heart: by Nilavya Das</p>
