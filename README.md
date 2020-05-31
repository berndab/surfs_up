# Surfs Up

## Purpose

The purpose of this project is to determine how seasonal daily temperature variations will affect the sales volume and customer type of a proposed “Surf and Shake” shop business on the island of Oahu, Hawaii. 

## Methodology

The project uses the historical daily temperature observations from the 9 weather stations on the island of Oahu to determine the seasonal variation of the daily temperature on the island. The project performs a statistical analysis on the historical daily temperature observations for June and December the compares the statistical measures generated for these month to define the seasonal variation of the daily temperature on the island. 
This seasonal temperature variation data is then used to predict how this seasonal variation would influence the "Surf and Shake" shop’s sales volume and the customer types that would frequent the shop

## Weather Data June and December Oahu, Hawaii

|   Value Type  |  June |December|
|---------------|-------|--------|
|Temp Obs Count |1700   |1517    |
| Mean          |74.944 |71.042  |
| Std           |3.257  |3.746   |
| Min           |64.00  |56.00   |
| 25%           |73.00  |69.00   |
| 50%           |75.00  |71.00   |
| 75%           |77.00  |74.00   |
| Max           |85.00  |83.00   |

|        Oahu Weather Station Information        |   |
|------------------------------------------------|---|
| Number of Oahu Weather Stations                | 9 |
| Daily Number of Temp Observation per Station   | 1 |

<img src="https://github.com/berndab/surfs_up/blob/master/june_avg_daily_temp_all_years.png" />
<img src="https://github.com/berndab/surfs_up/blob/master/december_avg_daily_temp_all_years.png" />
<img src="https://github.com/berndab/surfs_up/blob/master/june_daily_temp_all_years_boxplot.png" />
<img src="https://github.com/berndab/surfs_up/blob/master/december_daily_temp_all_years_boxplot.png" />

## Analysis of Seasonal Weather Variations

The comparison of statistical temperature measure for June and December, show only a slight variance in most of the the statistical temperature measures. The mean temperature difference between June and December is 3.9 degrees. The maximum temperature difference between June and December is 3 degrees. 75% of the temperatures for June are 73 degrees and above while 75% of the temperatures for December are 69 degrees and above. For most of the statistical temperature measures for June and December, the seasonal variation of their values is 3 - 4 degrees.

However, the bottom quartile of daily temperatures data for June and December show a more significantly seasonal variation. The minimum temperature difference between June and December is 6 degrees which is twice the difference between the maximum temperature for these two months. In addition, December's minimum temperature of 56 degrees is significantly lower than beach goers’ preferred beach going temperature. December has more days with temperatures below this preferred beach going temperature since it has a significant amount of outlier temperatures below 60 degrees. The December graph of average daily temperature show that these outlier temperatures tend to occur during last week of December.

The data shows that the significant seasonal weather variation between June and December is that December has a significant number of day where with temperatures below the preferred temperature for beach going.  

## Impact of Seasonal Weather Variation on the "Surf and Shake" Shop Business

There are four types of customers that the proposed "Surf and Shake" shack would serve
* Local island beach goer who purchase ice cream and shakes
* Local island surfers who purchase surfing equipment and supplies
* Tourist beach goers who purchase ice cream and shakes
* Tourist surfers who purchase surfing equipment and supplies

The major seasonal weather variation between June to December is the increase in the number of days in December where the temperature is below the preferred beach going temperature. Based on this, the following conclusions can be made about how Surf and Shake" shop’s sales volume and customer type frequency would change do to this seasonal variation characteristic.

The “Surf and Shake” shop would see a decrease in the number of the local island beach goer customers and a decrease in the sales volume for ice cream and shakes purchased by this customer type in December due to the high number of days with unfavorable beach going temperatures. The local beach goer would choose something else to do on the days in December with unfavorable beach going temperatures and will choose to wait for the days in December where the temperature is preferable for spending the day at the beach.

The “Surf and Shake” shop would also see a decrease in the number of the tourist beach goer customers type and a decrease in sales volume for ice cream and shakes purchased by this customer type in December. Tourists beach goers can choose when to come to Oahu and would not choose to come in December, particularly at the end of the month, due to the high number of days with unfavorable beach going temperatures. Tourist beach goers would choose to come during other months of the year when the occurrence of days with unfavorable beach going temperatures are rare.  

The “Surf and Shake” shop would not see a decrease in the number of the local surfer customers and not see a decrease in sales volume of surfing equipment and supplies purchased by this customer type in December.  Local surfer are motivated and prepared to surf year round. There decision-making process to go surfing on a particular day is more influenced by wave conditions than the air temperature As long as wave conditions are favorable for surfing, local surfer will go surfing and will use wetsuits to stay warm on lower temperature days. The higher number outlier, low temperature days in December would not negatively the local surfing activity. 

The “Surf and Shake” shop would see a decrease in the number of the tourist surfer customers and a decrease in sales volume for surf equipment and supplies purchased buy this customer type in December. The tourist surfer customer can choose when to come to Oahu to surf. Unlike local surfer customers, tourist surfer customers are influence by air temperatures. It is preferable to the tourist surfer customer to come to surf when low temperature day do not occur. They would avoid coming in December since it has a high number of outliers, low temperature days 


## Further Analysis

### Analysis Using Hourly Temperature Reading Per Day

Currently the temperature data set only has one temperature observations per day per station. In addition, this temperature observation only had date information. Typically surfing and beach going activity occurs between 9am and 4pm. Local and tourist beach goers, and tourist surfers make decision to choose to go to the beach based on the temperature at those times of the day. Having hourly temperature data would focus the analysis of the seasonal variation in temperatures to the time of day which that most influences beach goers' and surfers' decision to go to the beach.  

### Analysis of Seasonal Temperature Variations at the Station Level

There may be significant differences in seasonal variation of temperatures at different part of Oahu. Weather on Oahu varies significantly due to the trade winds and their interaction with Oahu's mountains. The weather on Oahu's south and west shore is usually drier and sunnier than on the island's east shore. This is because the predominant trade winds are blowing from the northeast about 90% of the time amd they get stuck on the mountains. The weather on Oahu's east shore is therefore usually a lot wetter and colder than on the west shore. 
Generating general information about the seasonal weather variation for the island may not be the right method to use to predict the effects of seasonal weather variation on the “Surf and Shake” shops business. This is due to the significant differences in weather patterns depending on what side to the Oahu's mountain the “Surf and Shake” shop may be located. 
Analyzing seasonal weather variations at the station level would may show that the weather and seasonal variation of the weather on certain part of the island may have a significantly more favorable affect on the shops sales and the customer type the shop will attract. 

### Seasonal Variation in Ocean Water temperature

Beach going is not just influence by air temperature. It is also influence by water temperature. Including data on the seasonal variation of water temperature would increase the accuracy of the predicted effects of seasonal weather variation on the sales volume and customer type frequence for the “Surf and Shake” shop.

### Analysis of Seasonal Variations in Wave Conditions

The local surfer follows the waves. Data on the seasonal variation in wave conditions would be more useful in predicting the effects of seasonal weather variation on the sales of surfing equipment and supplies to the local surfer customer then data on the the seasonal variation of air temperatures/ 
