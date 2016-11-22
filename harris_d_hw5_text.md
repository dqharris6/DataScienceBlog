# Drinking vs. Graduating: A College Student's Guide to Staying In on Friday Night

It's no question that underage college drinking poses significant public health problems, and takes an enormous toll on the intellectual and social lives of students on campuses across the United States. Drinking has become ritual for America's college students, as many see it as an integral part of their higher education. Students either have seasoned drinking habits in place upon entering college, or are eager to experiment with what they've been sheltered from in their first 18 years. Our visualization compares per capita alcohol consumption among college-age students per state to average 4-year college graduation rates per state, to answer the fundamental question: “How do Alcohol Use and College Graduation Rates correlate by State?”.

### The States In Question

First, we took a look at which states report drinking the most. Rather than factoring in all states, we focused on Beer Marketer’s Insights’ “States That Drink the Most Beer” to narrow our scope to Maine, Mississippi, Montana, Nebraska, Nevada, New Hampshire, North Dakota, South Dakota, Texas, Vermont and Wisconsin. This decision eliminates factors such as religous affiliations (no suprise that Utah is one of the states with the lowest alcohol consumptions) and shipping costs of beer (taking out Hawaii and Alaska), and leaves us to analyze the states that we know are drinking the most. We note that New Hampshire (home of Dartmouth) is the only state containing an Ivy League school on our list, which consistently takes last place in overall academic performance comparitively.

![alt text](https://github.com/dqharris6/DataScienceBlog/map.jpg "Logo Title Text 1")

### Alcohol Consumption in the US

So, how do we know that this 20% of America is full of alcoholics? We turn to the National Survey on Drug Use and Health (NSDUH), which collects and aggregates drug, alcohol, tobacco and mental health information year after year. From their 2015 dataset, we pulled the table "Alcohol Use in the Past Month, by Age Group and State (Based on 2013 and 2014 NSDUHs)", which lines out confidence intervals of self-reported drinkers by age group by state. Since we're only intersted in college-age drinkers, we extracted only the 18-25 year-olds, and put this over the total population to calculate our state percentages.



This is all tied back to the original question, which prompts us to see if the states that have more college-age students drinking report higher or lower graduation rates from college.

I used 4 data sources for my analysis; NSDUH Table 9: Alcohol Use in the Past Month, by Age Group and State: Estimated Numbers (in Thousands, 2013), US Census Data from 2010, Beer Marketer’s Insights’ “States That Drink the Most Beer”, and the College Completion Chronicle’s graduation statistics from 2013.

The National Survey on Drug Use and Health (NSDUH) is a primary source of statistical information on the use of illegal drugs, alcohol, and tobacco by the U.S. civilian, noninstitutionalized population aged 12 or older. The survey also collects data on mental disorders, co-occurring substance use and mental disorders, and treatment for substance use and mental health problems.
