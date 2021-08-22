# Kickstarting with Excel

## Overview of Project
Louise has a play, "Fever", that was able to come close to reaching her fundraising goal in a short time period. She would like to use data analysis to visualize campaign outcomes to better understand if she can improve her fundraising strategies.


### Purpose
Louise would like to use Kickstarter data to understand how different campaigns faired in relation to their launch dates and their funding goals. Being able to visualize the 'ifs' and 'hows' of other play campaigns can provide insight into future kickstarter fundraisers.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A pivot table was created and used to understand how successful 'Theater' campaigns were as a function of time. The following [pivot Table](/Resources/Pivot_Table.png) compares theater campaign successes & failures as a function of time. The result was a [line graph](/Resources/Theater_Outcomes_VS_Launch.png) that visualizes numerical data over time. 

### Analysis of Outcomes Based on Goals
The use of "COUNTIFS" statements were used to understand how successful subcategory play campaigns were as a function of pledge goals. This analysis would be helpful for Louise as she could find her pledge goal limits when fundraising in the future. This [plot](/Resources/Outcomes_Vs_Goals.png) illustrates the relationship between fundraiser success and pledge goals. As you may expect, the higher the pledge goal, the more difficult it will be for Louise to be successful. This plot allows Louise to see this relationship indepth. 

### Challenges and Difficulties Encountered
There were no particular difficulties or challenges with this analysis. The most difficult part was to create repetitive "COUNTIFS" statements via copy and pasting. Creating an array/matrix of values and the use of a "for" loop would be more practical.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    * Overall there are more successful theater campaigns than cancelled or failed ones.  There are about 41% more successful campaigns than failed ones, and 96% more successes than cancellations. The most successful campaigns start between May and June, while failed campaigns remain fairly consistent throughout the year. There were no cancellations during the month of October.     
    
    * Based on monthly data, Louise should launch her campaign during May or June. On average, Louise is about two times more likely to succeed during those months (May & June) than if she launched her campaign on any other months.

- What can you conclude about the Outcomes based on Goals?
    * The highest success from all play campaigns (~70% success rate) occurs when the pledge goal is less tha $1,000. There is a reciprocating trend between campaign success and failure as the pledge goal increases. As the pledge goal increases, the campaign has a higher chance of failing and not meeting its target. At $15-$19.9K, there is a 48% chance that the outcome is either a success or failure. There are two data points between $35K and $44.9K pledge goals that do not follow this trend where the success is greater than the failure. This should be examined closer. 'Cancelled' campaigns have no role in this analysis activity as no play campaigns were cancelled. There is not enough data regarding current/live campaigns to make any conclusions as they make up on average less than 4% of the total data inwhich two data points are outliers ($25K-$29.9K and >$50K). 
    
    * Louise should attempt to make her pledge goal as minimum as possible to increase her odds of making her play, specifically less than $15K.

- What are some limitations of this dataset?
    * This data is just limited to Kickstarter. There are multiple platforms, some which may be better or worse for Louise to use. This may be worth exploring.
    
- What are some other possible tables and/or graphs that we could create?
    * Additional tables/graphs that may be helpful:
        * Create an additional "Plays" subcategory filter on the launch date pivot chart. You could compare the "Theater" parent and "Plays" subcategory to see if the subcategory follows a similar trend to the rest of theater. 
    *  You can additionally look at the trends over each year. Do plays fundraise as well in 2020 as they did 2016? This may help push us to explore different fundraising platforms/options.
