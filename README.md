![Uncovering Project Trends: Kickstarter](https://github.com/ruthhinkle/kickstarter-analysis/blob/main/Images/header-image.png)

## Description

I analyzed 4114 Kickstarter projects between 2009 and 2017 to uncover hidden trends for future project designers. This analysis is not intended to be shared on behalf of Kickstarter, just an exploration of my own. 

## Music & Games Lead the Pack
The games and music categories stood out from the crowd with both being successfully funded 77% of the time. The next closest category was 17% less likely to be funded. 

Of all the sub-categories, 12 of them earned the distinction of 100% of attempted projects being successfully funded. Be careful, though! Just because a sub-category is more likely to be funded, doesn't mean the parent category performs as well. 

![Successful Project Categories](https://github.com/ruthhinkle/kickstarter-analysis/blob/main/Images/subcats-vs-parents-edit.png)


## Avoid December Project Launches
Over 9 years, December project launches had the lowest counts of project success. In the same month, the counts of failed and canceled projects increased. It's possible that households have less cash to spare given holiday spending and end-of-year giving.

Based on the data, it's tempting to assume that May is the opposite of December. The big spike in project success, however, is accompanied by increases in failed and canceled projects. It would be more accurate to say that May is the more popular month for launches and all outcomes increase as a result.  

![Outcomes by Launch Month](https://github.com/ruthhinkle/kickstarter-analysis/blob/main/Images/success-by-month.png)

## The Bigger the Goal, the Riskier the Project
Overall, project success trended downward as the dollar amount of the goal increased. Projects with a goal under $1000 were 70% successful while projects with a goal above $50,000 were only 19% successful. 

![Outcomes by Goal Amount](https://github.com/ruthhinkle/kickstarter-analysis/blob/main/Images/outcome-by-amount.png)

## What about the backers?
This data does not analyze one of Kickstarter's defining features, which is the levels of rewards for project backers. Backers contribute to projects at increasing levels of funding which unlock increasing reward values. As a former fundraiser, I want to know the number of reward levels and the distribution of backers among those levels. This might tease up best practices for choosing the number and scale of reward levels. 

For example, 100% of tabletop games were funded in this dataset. Based on my own experience as a backer and without seeing any data, I'd hypothesize that most backers chose a reward level that included a copy of the game. I'd expect the distribution of backers to be clustered around that reward level. Based on my knowledge of fundraising for the arts, I imagine that plays would have a handful of high level backers with more backers clustered around lower reward levels regardless of the actual reward.

Per category, it would also be useful to see demographic data particularly location and income for the backers of these projects to get a sense of where to promote them in online spaces. 

## Statistical Analysis
The high level of variance demonstrates the values in this dataset are spread out, thus indicating that the median is a more useful summary of this dataset. Successful campaigns have a higher level of variance than unsuccessful campaigns. This makes sense – failed campaigns had fewer backers on average while successful campaigns were able to meet the goal with a wide range of backers. Some projects were able to meet their goal with a small number of backers while others were successful by attracting large numbers of backers. 

### Tools
* Microsoft Excel
* Canva
