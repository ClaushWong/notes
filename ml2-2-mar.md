# ML- 2 March 2020 - Notes (Chapter 2)

- Supervised Learning
- Unsupervised Learning
- Reinforced Learning

> Supervised Learning (SL)
> - Data points have known outcome
> - Goal : Learn a model labeled training data that allows us to make prediction about unseen or future data
> - Types : Regression, Classification
> - Example : Email spam filtering
> ![sl-definition](https://cdn.discordapp.com/attachments/346967448781717505/683834791832977436/unknown.png)

> Regression \[SL\] (RG)
> - Outcome is continuous
> - Numeric Answers
> - Given a number of predictor(explanatory) variable and continuous response variable(outcome/target)
> - Find out the relationship between those variables that allows us to predict the outcome

> Classification \[SL\] (CF)
> - Outcome is a category
> - Categorical Answers

> Overview \[SL\]
> ![overview-sl](https://cdn.discordapp.com/attachments/346967448781717505/683833113133973552/unknown.png)
> - Learn how to *build* the *model*

> Example \[SL\] \[RG\]
> ![rg-sl-overview](https://cdn.discordapp.com/attachments/346967448781717505/683833630363222026/unknown.png)

> Example \[SL\] \[CF\] 
> ![cf-sl-overview](https://cdn.discordapp.com/attachments/346967448781717505/683834078000054287/unknown.png)

> Target - Features - Example (Example of Terminology)
> - Target
> ![target-iris](https://cdn.discordapp.com/attachments/346967448781717505/683835817122070632/unknown.png)
>
> - Features
> ![features-iris](https://cdn.discordapp.com/attachments/346967448781717505/683835862991110194/unknown.png)
>
> - Example
> ![example-iris](https://cdn.discordapp.com/attachments/346967448781717505/683836815001649182/unknown.png)

> Unsupervised Learning (UL)
> - Data points have unknown outcome
> - Dealing with unlabeled data or data of unknown structure
> - Goal : Extract meaningful information without the guidance of a known outcome variable or reward function
> - Type : Clustering

> Clustering \[UL\] (CT)
> - Sometimes also called *unsupervised classification*
> - Organize a pile of information into meaningful subgroups(clusters) without having any prior knowledge of their group memberships
> - Great technique for structuring information and deriving meaningful relationship from data
> - Example: Discover customer groups based on their interests

> Reinforced Learning (RL)
> - Outcome known through the use of reward system
> - Goal : Develop a system(agent) that improves its performance based on interactions with the environment
> - Include a so-called *reward signal* (not a correct ground truth label or value)
> - Measure how well the action was measured by a *reward function*
> - Agent can use reinforcement learning to learn a series of actions that maximizes this reward via *exploratory trial-and-error* approach or *deliberative planning*

> Application \[RL\]
> ![agent-rl](https://cdn.discordapp.com/attachments/346967448781717505/683841843259113675/unknown.png)

#### Terminology
| Term | Description |
| :----: | :----: |
| Label | Target value for a single point data(outcome) |
| Supervised | Set of samples where the desired labels are already known |
| Target | Predicted category or value of the data(column to predict) |
| Features | Properties of the data used for prediction(non-target columns) |
| Example | A single data point within the data(one row) |


```python

```
