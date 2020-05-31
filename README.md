# Surfs Up

## Purpose

The purpose of this project is determine how a proposed “Surf and Shake” shop business on the island of Oahu, Hawaii would be affected by sessional weather variations on the island. The goal is to determine how seasonal temperature variations on the island would affect the shop’s sales volume and customer types the shop served.

## Methodology

The project uses a data set that consists of multiyear daily temperature reading from 9 weather stations the island of Oahu. The project generated standard statistical values using multiyear daily temperature observations for June and December. Then these statistical values for June and December are compared to determine the sessional variation in these values.

This seasonal temperature variation data is then used to predict how the "Surf and Shake" shop sales volume and customer type would be caffected  based to these seasonal variation. 

## Weather Data June and December Ohau, Hawaii

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

The comparison of statistical temperature measure for June and December, show only a slight variance in the majority of the statistical temperature measures. The mean temperature difference between June and December is 3.9 degrees. The maximum temperature difference between June and December is 3 degrees. 75% of the temperatures for June are 73 degrees and above while 75% of the temperatures for December are 69 degrees and above. For most of the statistical temperature measures for June and December, the seasonal variation of these mesures is 3 - 4 degrees.

However, the bottom quartile of average daily temperatures data for June and December show a more significantly seasonal variation. The minimum temperature difference between June and December is 6 degrees which is twice the maximum temperature difference for these two months. In addition, December's minumun temperature of 56 degrees is significantly lower than the preferred beach going temperature value. December has more outlier temperatures at the low end of the temperature scale that are below 60 degrees which caused December to have more days with temperatures below the preferred beach going temperature. the December average temperature graph show that the days with the outlier temperatures at the low end of the scale tend to occure during last week of December.

The analysis of June and December temperature data indicates that the significant seasonal variation between June and December is the increase in the number of days in December where the a daily average temperature is below the perfered temperature for beach going.  

## Impact of Seasonal Weather Variation on the "Surf and Shake" Shop Business

There are four types of customers that the proposed "Surf and Shake" shack would serve
* Local island beach goers who purchase ice cream and shakes
* Local island surfers who purchase surfing equipment and supplies
* Tourist beach goers who purchase ice cream and shakes
* Tourest surfers who purchase surfing equipment and supplies

Give the the major seasonal variation between June to December is the increase in the number of day in December where the temperature is below the peferrd beach going temperature value the folowing conclusions can be made about the seasonal variation in the sales volume of and the customer type frequence for "Surf and Shake" shop/

The “Surf and Shake” shop would see a decrease in the number of the local island beach goer customer types and a decrease in the sales volume for ice cream and shakes purchased by this customer type in December due to the increased number of days where the temperature is below the local beach goer's prefered temperature to decicde to go to the beach. Local beach goer will choose to wait for those days in December where the temperature preferable for spending the day at the beach.

The “Surf and Shake” shop would also see a decrease in the number of the beach going tourist customer type and a decrease in sales volume for ice cream and shakes purchased by this customer type in December. Beach going tourists can choose when to come to Oahu for beach going. Due to the higher number days with temperature below the perferred beach going temperature, beach going tourist would choose to come during a time period where the occurance of days with tempertures below the perferred beach going temperature is significantly less than it is during the month of December. 

The “Surf and Shake” shop would not see a decrease in the number of the local surfer customer type and not see a decrease in sales volume of surfing equipment and supplies purchased by this customer in December.  Local surfer are motivated and prepared to surf year round and are more influenced by wave conditions than the temperature when making the choice to go surfing on a particular day. Generally, as long as wave conditions are favorable for surfing, local surfer will go surfing and will use wetsuits to stay warm on lower temperature days. Therefore, the fact that December has a higher number of low temperature outlier days does not negatively affect the frequency of days the local surfer customer type chooses to surf.

The “Surf and Shake” shop would see a decrease in the number of the surfing tourist customer type and a decrease in sales volume for surf equipment and supplies purchased buy this customer type in December. Like the tourist beach going customer type, the surfing tourist custoemr type can choose when to come to Oahu to surf and these customer types would prefer to some to surf during months when the there is very little likely hood of days with temperatures below 70 degrees.


## Further Analysis

### Hourly Temperatue Reading Per Day

Currently the temperature data set only has one temperature obervation per day per station and this temperture observation only had date information and does not time of day information. Typically surfing and beach going activity occurs between 9am and 4pm. Local and tourest beach goers, and tourest surfers make decision to choose to go to the beach based on the temperature at those times of the day. Having hourly temperature data would focus the analysis of the seasonal variation in temperatures to the this time period which had the most influence on beach goers' and surfers'decision to go to the beach.  

In addition having hourly temperature observation would help to determine what time of day low temperature ourler values occur. This information would help to determine how relavent these temperature observation are to our analysis. As an example if the minimun temperature for December of 56 degrees occured a 6 AM, then this temperature would not be used in the analysis since temperatures between 9 AM and 4 PM are the most relavant in predicting the number of local beach goers, tourest beach goers, and tourest surfers that would go to the beach on that day.

### Analized Sesonal Temperature Variations at the Station Level

There may be sigificant differences in seasonal variation of tempertures at different weather stations and at different beaches on the island of Oahu. Weather on Oahu varies significantly due to the trade winds and their interaction with Oahu's montains. The weather on Oahu's south and west shore is usually drier and sunnier than on the island's east shore. That's because the predominant tradewinds are blowing from the northeast about 90% of the time they get stuck on the mountains. The weather on Oahu's east shore is therefore usually a lot wetter and colder than on the west shore. Looking at seasonal weather variation for the island as a whole may not be the correct granularity for meaningful analysis of seasonal variation in weather due to the significant differences in weather patterns depending on what side to the Oahu's montain the the weather station is on. 

A specific location must be chosen for the "Surf and Shake" shop on the island of Oahu. The local seasonal weather variation may be significantly differend depending on which side of Oahu's montain the shop is located. Our current general analysis of the seasonal weather variation is based on the assumption the analysis is applicable to the entire island of Oahu. This may be a incorrect assumption and could lead to locating the shop in an area of the island whose seasonal weather variation differes significantly from the values our general analysis produces.

### Analized Seasonal Variation in Ocean Water temperature

Beach going is not just influence by air temperature. It is also influence by water temperature. Adding data of the seasonal variation of water temperatures to our analysis ofthe seasonal variation in air temperature would make our predicions of the affect of seasonal variation on the sales volume and frequence of customer type more accurate.

### Analizing Seasonal Variations on Wave Conditions

The local sufer follow the waves with almost no consideration for the air temperature. Data on the seasonal varation in temperature is not significantly useful in predicting the sales volume of surfing equipment and supplies purchaes by the local surfer customer type and the frequency that the customer would come to the shop. Analizing the seasonal variation of wave conditions, would enable a much more accurate prediction of of the shoping behavior of the local surfer customer type. 
