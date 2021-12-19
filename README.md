# Kickstarter Analysis
Challenge 1 for Butler Data Science

## 1. Overview of project
### 
* There are over 4000 Kickstarter projects in our dataset and our subject's campaign is in theater and more specifically a play. "Theater" is the most prevalent parent category (30% of all projects in dataset) and "Plays" is the most prevalent subcategory (26% of all projects in dataset). 
![Count of Parent Category](https://github.com/coxjack/ExcelChallenge1/blob/main/AdditionalSupportingImages/ParentCategoryTotal.png)
![Count of Subcategory](https://github.com/coxjack/ExcelChallenge1/blob/main/AdditionalSupportingImages/SubcategoryTotal.png)
This gives us an opportunity to draw conclusions about the successfulness of campaigns in these subsets. To take it a step further it is now time to look how "Launch Date" and "Goal" determine the successfulness of a campaign.

## 2. Analysis and Challenges
###
* The two breakdowns of the data we will look at are viewing the different outcomes of theater kickstarters based on their launch dates and viewing the different outcomes of theater kickstarters based on their goal amounts. This will give our subject a good idea on when it best to launch her campaign and for how much to launch it for. While our data only encompasses 9 years of campaigns it is still a good enough time frame for our subject to make a decision.
* I did not face any specific challenges during this analysis but particular challenges that could be faced are a lack of familiarity in excel or a smaller less encompassing dataset.
![Theater Outcomes by Launch Date](https://github.com/coxjack/ExcelChallenge1/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
![Outcomes Based on Goals](https://github.com/coxjack/ExcelChallenge1/blob/main/Resources/Outcomes_vs_Goals.png)
## 3. Results
###
* May & June are the most successful months to launch a campaign and it continues to drop as the year goes on, until October where is the an uptick in successful and failed campaigns. Our subject should launch her campaign in the early summer May or June.
* December is the worst month to launch a campaign as the successful and failed campaigns are almost equal to each other. If our subject cannot launch in May or June she should absolutely avoid doing it in December as it is the only month where success and failure are almost equal as likely to occur.
* Campaigns are more successful than failed up to the range of $15000-$19999 where a campaign failing becomes more likely than it succeeding. This holds true until the range of $35000-$39999 as well for the range of $40000-$44999. Anything above $44999 is highly likely to fail. Our subject should either keep her campaign goal below $15000 or make it from the range of $35000-$44999. Avoiding the middle ground of $15000-$34999 and the high end of $45000+ gives her the best chance of success.
* Limitations of the dataset
  - The dataset is skewed with data from the parent category "Theater" and the subcategory "Plays" while this helpful for our analysis with our subject I am not sure if it paints the most accurate picture of Kickstarters on the whole and perhaps jeopardizing the accuracy of our conclusions. 
  - A box and whisker plot of the Outcomes Based on Goals sheet would help us view mean, median, and mode goals as well as the IQR of the goal outcomes. This would give us additional, specific information about our dataset.




