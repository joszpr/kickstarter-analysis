# Kickstarter Campaigns Analysis  

### **Overview** ### 
Analysis of Theater Kickstarter campaigns by comparing their success or failures in relation to their Launch dates and Campaign Goals.Data of 
previous campaign outcomes was organized and analyzed in order to look for any helpful patterns that could aid in Louise current 
and future Kickstarter campaigns. 

### **Background and Challenges**
The analysis was performed with information on Kickstarter campaigns from 2009 until 2017 with a focus on the Theater category and how 
they fared based on the date that they were launched and initial funding requested. The amount of raw data is relatively large, and 
Microsoft Excel was used to organize, filter and employ statistical measurements in order to produce useful information. 
When working with big sets of data it is always important to review the processed and equations used in the analysis process for accuracy. 
This is even more critical when using nested equations and conversation of data (ex. Date from Linux to regular calendar). One issue that 
was encountered in the analysis process was Fixing the Value of equations. 

![Error Sample](https://user-images.githubusercontent.com/85839235/123565968-8879a980-d78c-11eb-9ccc-ffe8a7509833.png)

#### Example of Challenge
As example, when retrieving the counts for Successful campaigns from a different worksheet I originally missed Fixing the data on the 3rd 
and 4th criteria of an equation. It successfully worked in the first cell of data but returned different values from what was desired in the
original worksheet when the formula was passed to different cells. By fixing the value in the equation, I was able to use the same equation 
with minimal modifications when trying to use different criteria. 

### **Results**
The analysis for the relation between Theater Campaigns and Launch Dates provided insights that may be beneficial in organizing future campaigns. 

### Outcome based on Launch

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85839235/123565991-962f2f00-d78c-11eb-8b8c-abb58ac2471d.png)

First, although there is support for Theater campaigns for most of the year, the months between April and August show a bigger percentage of 
financial backing. With peak support on the month of May with a decline during the summer period. Second, December is the month with the least 
amount of financial backing, which is to be expected since it can be surmised that much of the population use their discretionary budget for 
holiday expenses. Lastly, the amounts of Successful backing for Theater campaigns surpasses the number of Failed campaigns consistently during 
most of the year. December being the only month where their outcome is similar. 

### Outcome based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85839235/123566001-9cbda680-d78c-11eb-887d-f37bc1937832.png)

When inspecting the relation between Theater campaigns and the goal of financial support requested, two insights were discovered. First, as 
reasonably expected, the success rate of the campaign decreases the bigger the goal is. Interestingly enough, there was a considerable number of 
Successful campaigns that had goals between $35,000 and $45,000 that were outside of the trend. Further research is suggested in order to identify 
what assisted the success rate for campaigns between those thresholds. 

### Data Considerations
The is no information regarding recent campaigns and information from 2018-2021 was not analyzed. The current socioeconomical climate and the 
offset of the pandemic of 2020 may influence, either positively or negatively, support received on Kickstarter. Although there has been reports 
of pent up demand for entertainment activities 1️⃣,2️⃣ that shows possibility of increase support for the production of new events, it is the concern 
of still being in public settings for some people should be taken into account. There is also reports about changes of media and entertainment 
consumption for digital mediums based on the habits developed during 20203️⃣.  

### Recommendation
With the limitations of the data previously shown, it may still be beneficial to look into more detail regarding the successful campaigns that 
had bigger goal backing. We could investigate any potential factors that may have help those campaigns be successful. It may provide insight to 
identify if there is any pattern on bigger support for specific regions countries, if it may have been related to the themes of the plays or the 
length the campaign was active.

### Reference Links

[1️⃣] https://morningconsult.com/2021/03/24/pent-up-demand-travel-restaurants-cruise-pandemic/

[2️⃣] https://variety.com/2021/music/news/live-nation-president-massive-concert-demand-1234992757/

[3️⃣] https://www.forbes.com/sites/bradadgate/2021/04/13/the-impact-covid-19-had-on-the-entertainment-industry-in-2020/?sh=41972121250f

