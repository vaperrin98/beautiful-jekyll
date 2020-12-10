---
layout: home
title: Life Satisfaction and Housing 
subtitle: Does housing has an influence on people's life satisfaction and happiness? Could the 33 boroughs of London allow us to uncover the housing and neighborhood conditions that make people happy?
---

Housing is an important component of everyone's life. After all, your home is where you spend most of your week, particularly in these trouble times. Does your neighborhood, that you now know by heart since lockdown, contribute to your happiness?

# Why this study?

Cattaneo and al., in their paper *Housing, Health and Happiness*, discuss the influence of housing on health and welfare by studying the impact of a large-scale household Mexican government program. They found that housing upgrades significantly improve adult welfare, as measured by increased satisfaction with their housing and quality of life, as well as lower depression and perceived stress. This raises an interesting point: how does their findings generalize to other cities? Is it possible to establish links between housing and life satisfaction in a big European city? We decided to extend their work by looking at data from housing in London.

We explore the possibility to find such housing influence through London boroughs. If our study context is certainly different from theirs (the housing conditions in these two countries are rather different), we also compare information of small closely related locations (London boroughs) to uncover the influence of housing in these neighborhoods on their inhabitants' life. 

What if we could establish the influence of numerous housing variables, such as prices, neighbourhoods (and conditions) on your life satisfaction and happiness in the city of London? We would be able to tell you where you should live to make your life great!
But also, can politicians use your housing and neighbourhood conditions to know if you will vote for them? We further extend our research on whether political opinion is defined by these conditions, to find which neighborhoods are won by which party.

## Index
1. [Does location define life satisfaction or is it defined by standard of living (job, house price)?](#part1)
    1.a. [What could influence your happiness?](#part1a)
    1.b. [Are you really happier if you live in inner London?](#part1b)
2. [Can we group neighborhoods by looking at well being, security and economic stability?](#part2)
    2.a. [Are neighborhoods really that different?](#part2a)
    2.b. [Borough groups](#part2b)
3. [Can we predict political control based on life satisfaction and housing conditions?](#part3)
    3.a. [Do people vote significantly differently based on their life satisfaction and housing?](#part3a)
    3.b. [Can politicians know your political preferences based on where you live?](#part3b)
[Conclusion](#conclusion)


Let's first have some insights on the data we have. 
-> put visualization such as borough number, number inner and outer london
-> pie plot with groups of political countrol, age groups across london as a whole, type of house possession in groups across London


<a name = "part1"></a>
# 1. Location and life satisfaction
Are you more satisfied with your life if you live in a particular borough of London? Do inhabitants of Kensington and Chelsea, the most expensive borough of London, are happier than others? Let's find out.

<a name = "part1a"></a>
## 1.a. 
To discover what makes people satisfied with their life, we think about what could make people happy with their housing conditions. Let's observe for instance the employment rate, the household income, the life satisfaction score, and the happiness score of Londong boroughs in relation to their location.
-> put the graphs investigating the variables used in this question + describe this and make the conclusions.

<a name = "part1b"></a>
## 1.b.
After some visual investigation, we could think that for instance people living in inner London boroughs are happier. So does your housing location really defines your happiness? To answer this, we use different linear regression models. In model 1, we only tried to predict life satisfaction in function of whether the borough was located in inner or outer London. In model 2, we added the possible influence of health and safety in the neighborhood. In model 3 we additionally used the influence of employment rates and income. From this, we conclude the significance and thus importance of parameters defining your life satisfaction, happiness, worthwhileness and anxiety. 
-> put graph with 100%-pvalue to show significance
Write conclusions

We can deduce that the life satisfaction score, the worthwhileness score as well as the happiness score can very well be predicted from location in all three models. Well, this means that all these scores can be predicted by location. Sorry folks, but people living in inner London are indeed happier!

However, anxiety is hardly predictable by your location, so maybe try some other things than moving to a new borough to reduce your stress (it will probably cost less anyway).

But could the standard of living be used to predict life satisfaction? We chose to test a prediction with the criteria of salary, median house price, crime rates and if the house was owned outright. Can any of these parameters predict the life satisfation score, happiness score, worthwhileness score or anxiety score? 

-> put results from second figure Q1

We see that the crime rates per thousand population alone cannot predict any of these scores, meaning that having high numbers of crimes in your neighborhood doesn't affect your personal life that much (well, until that happens to you).

For the median house price alone, FINISH THAT 

In terms of gross annual pay, it is not surprising to find that earning more money can help reducing your anxiety, as well as increasing your happiness. However, you're not more satisfied with your life if you earn more. 

But what's interesting here, is that how you own your house is a powerful predictor of Homes owned Outright is a credible variable to be able to predict all 4 scores.

CORRECT THIS: We can thus answer that by looking at the p-values, Life satisfaction can be defined by standard of living and more particularly by whether a home was owned outright or not more than by location. 

<a name = "part2"></a>
# 2. Neighborhoods
We found that location does define your happiness. But are neighboorhoods that different? Can we find some differences so important that they define clusters of boroughs?

<a name = "part2a"></a>
## 2.a. Finding borough groups
What could make your neighborhood so great compared to others? Let's visualize some infos for the boroughs.
-> put graphs/figures with 

<a name = "part2b"></a>
## 2.b. How are these groups defined?
It is quite possible to group neighborhoods by looking at well-being, security and economic stability. We were able to find 5 groups of boroughs. By going back to the original data, we can show the groups using a map of London. And well, we find that the boroughs clustered together were usually belonging to the same London region (inner/outer london, geographic location)!

#### But, what are these two lonely neighborhoods?
Two neighborhoods cannot be linked to any others? **Why?** 

If they are solo, it must be because they are very different from the others! Let's find out why ...

The first outlier is the **City of London**. This does not mean London Town, but rather the historical and central primary business of London. This a major business and financial center, mostly consisting of companies and business group headquarters. Its characteristics are quite different from other boroughs, but what makes it that different? Let's look at some numbers:
-> put numbers for that neighborhood, in comparison with other neighborhoods)

We see that the City is different on many aspects. For instance, -> put conclusions of numbers for the city of london

The second outlier is **Westminster**. A very touristic borough with high frequentation rates, where the Westminster abbaye and the Big Ben can be seen. But what makes it so different from others? Let's look at some numbers again.
-> put numbers 

If the large majority of parameters are within the normal range, one variable is particularly high in this borough: the crime rates. The crime rates per thousand population in Westminster is almost 3 times higher as the london mean crime rates per thousand population. (put small barplot for this). This added to the tourists everywhere, probably not a great place to live in London ...


<a name = "part3"></a>
# 3. Policital control in council
-> map with political control

<a name = "part3a"></a>
## 3.a. Influence of life satisfaction on political control

<a name = "part3b"></a>
## 3.b. What does this mean for a politician?

<a name = "conclusion"></a>
# Conclusion

[//]:#(---------- END OF WHAT IS VISIBLE ----------------)
