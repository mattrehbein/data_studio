style/images/pop_MA_temp_practice

How many Syrian refugees are hosted by top-ten GDP countries:
                How many Syrian refugees are hosted by top-ten GDP per capita countries:


7.26
I'm realizing again that there appear to be different numbers out there on Syrian refugees, most notably with regards to US numbers. So I'm staying away from US stuff, by and large.


NEXT STEPS:

** color code bars by gdp (top ten or by percentile?) NO

1. graph who has the most syrian refugees right now (or from last year)
2. merge that shortened df with gdp numbers
3. graph top 20 and gdp -- how? together?
4. look into plotting over time the avg gdp of the top 20 (? or so) countries with most refugees -- maybe that will show a trend if wealthier countries got involved? Or will show they never did
5. Read Pew piece 

6. Maybe total refugees around the world not in syria (for 2017), then do something to visualize that most/more than half/whatever it is live in five nearby countries?

6. Try merging the two dataframes; aren't that many countries so can probably just hand fix name descrepancies tho not sure best way to find them
7. If step 6 is successful, do a scatter plot

GRAPHS:
1. top ten
2. US
3. number of refugees total since war began (take out Syria again to limit to refugees out of country?)
4. merged top ten with gdp
5. would be nice to graph total refugees in world, then in same graphy by continent
6. graph top five or so countries' refugee levels over the years (maybe rem to stick to gdp)



7.19
Realized error I had made in how I was looking at the refugee data: the yearly total is the population of refugees in the host country, not how many new refugees came to the country that year. That silly mistake led to fair bit of rethinking, as a lot of what I was planning to graph involved totalling the total pop column and analyzing the result by country.

As a way to make the analysis more interesting, today I pulled gdp data from the world bank, in order to see how it relates to Syrian refugee acceptance (how are the world's richest nations responding to one of the world's biggest and most publized crises?). Hoping a scatter plot will work well for that.


ERROR LOG:

-error reading in gdp csv. FIX: specified encoding="latin-1"
-repeatedly getting 'empty dataframe' error when trying to plot something. FIX: Cannot have str/object values in y axis






****ORIGINAL IDEA -- couldn't find data in form/categories I was envisioning, so dropped the idea for now.

Is it right to deem the US war on poverty "largely over"?

This has been a raging debate well before the White House released its report last week, but let's attempt to bottom line what some of the main numbers are to get a sense of what the debate is and so we can make up our own minds about it.

stats i can graph to measure poverty:
-poverty level, according to census
-poverty level, according to UN
-percentage of those with health insurance
-SNAP participation
-food scarcity
-child poverty
-racial breakdown of poverty
-fam v. single parent v. individual in poverty
-*****federal spending on safety net programs