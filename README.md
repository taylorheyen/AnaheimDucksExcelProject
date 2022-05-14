**ANAHEIM DUCKS EXCEL PROJECT**

This is a quick Excel project I put together using NHL data from the Kaggle dataset(<https://www.kaggle.com/datasets/open-source-sports/professional-hockey-database>)

The project was more of less me wanting to practice what I had learned in AlexTheAnalyst Bike Sales Excel Project, but putting it towards some data that was interesting to me.

My goals for this is to essentially keep updating the project as I practice more and learn more ways to show off the data and answer more questions that may come up.

My first steps were to clean the data that I was planning on using. The data starts in the early 1900’s, but the Ducks did not become a team until 1993. To keep this project pretty simple, I filtered the years of data for 2000-2011. The other thing I needed to do was change the name for the Ducks, as they were known as the Mighty Ducks of Anaheim until 2006. I basically just did find and replace to change the name to strictly “Anaheim Ducks”.

From the beginning I wanted to see how goals scored and goals scored against influenced wins, losses, and playoff finishes. If you take goals for and subtract goals against, you get essentially a “goal differential”. This is a stat that is usually reported but was not included in this dataset. To get this, I inserted a new column and did the proper calculation to get our goal differentials.

The last cleaning that I did for the data was in regards to the “playoffs” column. The column lists the teams best finish in playoffs for that season. However, if the team did not make the playoffs it was just left blank. For cleanliness purposes, I changed the blank to saying “Missed Playoffs”

[![Screenshot-128.png](https://i.postimg.cc/VsZ44B4S/Screenshot-128.png)](https://postimg.cc/F1cjHSMm)

On to pivot tables, I spent a lot of time trying to compare different columns to get the desired output. I essentially took the Ducks data and organized it by the year, and then would go by either Goals For, Goals Against, Wins, Losses, and Goal Differential.

[![Screenshot-129.png](https://i.postimg.cc/NfWDvs3B/Screenshot-129.png)](https://postimg.cc/9rYZGhXn)

Lastly, I included the following charts in the dashboard. I added the splice option for the ability to individually look at how the Ducks did based on their playoff finish that year.

As an example, the years the Ducks did not make the playoffs, they had a negative goal differential. The year they won the Stanley Cup, they had a goal differential of plus 50. That was essentially the data I was trying to show for when starting this simple Excel project!

[![Screenshot-130.png](https://i.postimg.cc/TPxchk2s/Screenshot-130.png)](https://postimg.cc/QF67yJTg)
