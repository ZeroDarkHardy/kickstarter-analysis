# Kickstarting with Excel

## Analysis of Theater Projects on Kickstarter

### Given a sample of data from existing kickstarter campaigns, our goal is to find useful datapoints that will guide our client toward a successful crowdfunding campaign for her play "Fever".

## Analysis and Challenges

### Analysis of Outcomes Based On Launch Date

- When we look at the data, correlating the success of theater productions with the launch date of their campaigns, we see the most promising results came from campaigns that were launched between May and June, which taper off dramatically for the remainder of the year.  There is a brief uptick in the number of successful campaigns in October, but a far higher uptick in the number of failed productions.  This that while a briefly higher number of campaigns are being launched in October, the success rate is much more volatile. By the time we reach December, the number of failed and successful plays is almost identical, suggesting an unacceptable 50% rate of failure.  One particular limitation of this data set is the designation of certain campaigns as "live" or "cancelled", which may have subtly impacted the analysis had they been included with "successful" or "failed" projects, respectively.
![OUTCOMES BASED ON GOALS](https://github.com/ZeroDarkHardy/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

- We see the most ideal conditions for success in campaigns with funding goals under $5,000 (slightly better under $1,000), with a success rate of 73%, then taper off dramatically and end up with the odds stacked heavily against success by the $25,000 mark.  What's interesting is that we see a drastic uptick in viability in campaigns with goals between $35,000 and $40,000, with a success rate of around 67%.  After that, beginning at $45,000, we see almost no viability for success, ranging from 87%-100% failure rates.
![OUTCOMES BASED ON GOALS](https://github.com/ZeroDarkHardy/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

- While we can easily see, based on the data we have, when the most successful campaigns are launched and at what funding goal, other data may be driving these trends.  The content of these productions, more than simply the genre, may be influencing the popularity of funding.

## Results

- Based on our visualization of the "Outcomes by Launch Date" data, we can see that while the most campaigns are launched in May, that month also shows the highest ratio of success to failure, by far.  We can also see that campaigns launched in December have the least likelihood of sucess.

- Our visualization of "Outcomes Based on Goals" shows that our client should probably set her funding goal at less than $5,000.  There is data that suggests a marginally favorable rate of success between $35,000-$40,000, but unless that type of large-scale funding is absolutely necessary, she has better odds of success below $5,000.

- As previously stated, there could be market forces beyond the launch date and funding goals of these campaigns that drive their success/failure.  For example, our data set doesn't include whether or not the owners of the campaigns have had previously successful campaigns, which could drive future projects to success on the shoulders of loyal contributers. 

- Pie charts showing longitudinal success rates of specific genres of plays may show our client whether the public even has an interest in her production, while a bar chart showing success rates among veteran campaigners comparitively to rookies could show her whether it would benefit her to collaberate with another organization.
