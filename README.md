# Surfs Up

## Purpose

The purpose of this project is determine how a proposed “Surf and Shake” shop business on the island of Oahu, Hawaii would be affected by sessional weather variations on the island. The goal is to determine how seasonal temperature variations on the island would affect the shop’s sales volume and how it would change the customer type that the shop would serve during different seasons 
## Methodology
The project uses a data set that consists of multiyear daily temperature reading from 9 weather stations the island of Oahu. The project generated statistical measures for multiyear daily temperature measures for June and December and compares these statistical measures to determine the sessional variation of these measure. 
This seasonal temperature variation data is used to predict how sales volume and customer type would be change based to the seasonal temperature variation. 

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

From the statistical temperature measure for June and December, there appears to be only a slight variance in the majority of the statistical temperature values. The mean temperature difference between June and December is 3.9 degrees. The maximum temperature difference for June and December is 3 degrees. 75% of the temperatures for June are above 73 degrees while 75% of the temperatures for December are above 69 degrees. In the aggregate, the seasonal temperature variation from June and December temperature is expressed by a 3 degrees difference for the majority of the statistical weather measures.

However, the Bottom quartile daily temperatures data for June and December show a more significantly seasonal variation. The minimum temperature difference for June and December is 6 degrees which is twice the difference in the maximum temperature for June and December. In addition, the minimum temperature for December is 56 degrees is significantly lower than the preferred beach going temperature. Also, December has more outlier temperatures at the low end of the temperature scale and these additional outlier temperatures are below 60 degrees. This mean that December has more days with temperatures below the preferred beach going temperature. This increase in low temperature outlires is futher represented by the declining average temperature displayed on the December temperature chart during last week of December. This should be expected, since daily temperatures for the northern hemisphere reach their lowest values during this time frame.

The data shows that the major sesonal variation of temperature data for June and December occurs within the bottom quartile of daily temperatures for these months. December has on average has more days with marginal temperatures for beach going. 

## Impact of Seasonal Weather Variation on the "Surf and Shake" Shop Business

There are four types of customers that the "Surf and Shake" shack would attract
* Local island beach goers who purchase ice cream and shakes
* Local island surfers who purchase surfing equipment and supplies
* Beach going tourist who purchase ice cream and shakes
* Beach going surfers who purchase surfing equipment and supplies

The “Surf and Shake” show would see a decrease in the number of the local island beach goer customer types and a decrease in the sales volume for ice cream and shakes purchased by this customer type in December. Due to the higher number of low temperature outliers in December, December has less days where the temperature is in the preferred temperature range of local beach goers. Local beach goer will choose to wait for those days where the temperature is not an outlier and preferable for spending a day at the beach.

The “Surf and Shake” shop would also see a decrease in the number of the beach going tourist customer type and a decrease in sales volume for ice cream and shakes purchased by this customer type in December. Beach going tourists can choose when to come to Oahu for beach going. Due to the higher number of low temperature outliers particularly in the last week of December, beach going tourist would choose to come when the chances that the daily temperatures are favorable for beach going is much higher. 

The “Surf and Shake” shop would not see a decrease in the number of the local surfer customer type and not see a decrease in sales volume of surfing equipment and supplies purchased by the local surfer customer type in December. Even though December has a higher number of low temperature outlier days this does not affect the frequency of days the local surfer customer type chooses to surf. Local surfer are motivated and prepared to surf year round and are more influenced by wave conditions than the temperature when making the choice to go surfing on a particular day. Generally, as long as wave conditions are favorable for surfing, local surfer will go surfing and will use wetsuits to stay warm on lower temperature days.

The “Surf and Shake” shop would see a decrease in the in the number of the surfing tourist customer type and a decrease in sales volume for surf equipment and supplies purchased in December. Even surfing tourist's decision to go surfing is more influence by wave condition than temperature and they usually have wet suits to use when during lower temperature days. However, surfing tourist have a choice of when to come to Oahu to surf and significantly less surfing tourist would choose to come to Oahu in December with it higher number of low temperature outlier days. they would choose to come during months like June when there is more consistent daily temperatures 


## Further Analysis

### Hourly Temperatue Reading Per Day
Currently the temperature data set only has one temperature obervation per day per station and the temperture observation only had date information and not time of day information. Typically surfing and beach going activity occurs between 9am and 4pm. Local and tourest beach goers, and tourest surfers make decision to choose to go to the beach based on the temperature at those time of the day. Having hourly temperature date would enhance the ability to predict the affect of seasonal weather variation on the "Surf and Shake" shop sales and customer types. This would be particularly helpful when analizing the impact of low temperature ouliers in December on sales and customer type becasue time of day these lower temperatures occured would be known. It may be that the lowest temperature for December is 56 degrees but that temperature observation may have occured at 6am which would make it much less useful in predicting beach going and surfing activity. 

### Analized Sesonal Temperature Variations at the Station Level

There may be sigificant differences in seasonal variation of tempertures at different weather stations. Weather on Oahu varies significantly due to the trade winds and their interaction with Oahu's montains. The weather on Oahu's south and west shore is usually drier and sunnier than on the island's east shore. That's because the predominant tradewinds are blowing from the northeast about 90% of the time they get stuck on the mountains. The weather on Oahu's east shore is therefore usually a lot wetter and colder than on the west shore. Looking at seasonal weather variation for the island as a whole may be the correct granularity to analize this seasonal weather variation due to the significant differences in typical weather patterns depending on what side to the Oahu's montain the the weather station is on. 

A specific location must be chosen for location the "Surf and Shake" shop. The local seasonal weather variation may be significantly differend depending on which side of Oahu's montain the shop is located. Out current general analysis of the seasonal weather variation 
on Oahu may be significantly different the the seasonal variation for each local weather station. Out current variation data is ased on the assumption that this if the variation the shop would be subject to no matter where it is located on Oahu. This may be a incorrect assumption. 
Wave conditions

### Analized Seasonal Variation in Ocean Water temperature
Beach going is not just influence by air temperature. It is also influence by water temperature. Included analysis of the seasonal variation of Oahu water tempertature would make our predicions of seasonal variation on the sales volume for ice cream and shakes from beach goer more accurate.

### Analizing Seasonal Variations on Wave Conditions
The local sufer follow the waves with almost no consideration for the air temperature. Seasonal varation in temperature is not sifnificantly useful in predicting the sales volume of surfing equipment and supplies purchaes by the local surfer customer type. Analizing the seasonal variation of wave conditions, would enable a much more accurate prediction of the exprected demand for surfing equipment and supplies from the local surfing population.
