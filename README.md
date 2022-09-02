# Module 9 Challenge 
We will be using Jupyter Notebook, VS Code, and SQLite for this project

## Overview of the statistical analysis:

The purpose of the analysis is to compare seasonality trends between June and December in Oahu to support making business decision of opening the Surf shop and Ice cream ships in Hawaii. We will need to determine if the surf and ice cream shop business is sustainable year-round.

## Results:

Key differences betwee June and December temperature:

![dataframe](https://github.com/siqiou/surfs_up/blob/259aeee7562d8a27ae8952055c78c2cb59d10fa3/june%20vs%20dec.png)
- Min temperature in June is 64, in December it is only 56, this means that the ice cream business might be most significantly impactes due to colder weather.
- The mean temperture in June is 74.9, and it is only 71 in December, it is almost 4 degrees colder on average in December. In the 25%, 55% and 75% quartile, we are seeing the same trend, June is 3-4 degrees higher in temperature in each quartile.
- However, we are seeing less temperature counts in December than June, only 1517 records vs. 1700 records. This indicates that the we have more data to rely on for June rather than December, maybe there was less business in the past years during December due to weather challenges.


## Summary:

Overall, June and December weather are very alike, June temperatre are distributed mostly within 70-80 degrees, and December temperature are distributed within 60-80 degrees. As shown in the line chart, June temperatures have more ups and downs, but it rarely drops under 65 degrees. The december temperature can go as low as 55 degrees, and it could also be very warm as we can see the most lines are around 70 degrees. It is suggested to open the Surf shop in June, the lower temperature in December might impact both Surf and Ice cream shops.

![junechart](https://github.com/siqiou/surfs_up/blob/259aeee7562d8a27ae8952055c78c2cb59d10fa3/june%20temp.png)
![decchart](https://github.com/siqiou/surfs_up/blob/259aeee7562d8a27ae8952055c78c2cb59d10fa3/dec%20temp.png)

