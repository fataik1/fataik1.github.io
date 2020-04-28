---
layout: post
published: false
title: Jain University
---
## College is Right Around the Corner!

![Jain-University-Bangalore.jpg]({{site.baseurl}}/img/Jain-University-Bangalore.jpg)


Anyone who has ever been through the process of applying to college knows how stressful this time period can become. From the anxiety of waiting on the school of your dreams to answer on your admission or, to freaking out about choices you are unsure about. This process can hold a weight on you without even knowing it. The college process is definetly not an easy one. Now, we begin to think about the what gets us in these universities. Is it our work ethic, how much education knowledge we have, is there a placement test? All of these things can factor whether your likely to get into a school or not.


## Data

I found my data off the website  [Kaggle](https://www.kaggle.com/benroshan/factors-affecting-campus-placement). In this dataset, there was 215 observations and 15 columns, we use all of the columns to evaluate a student's education history and to see if they are on the track to finally getting their masters.  The observations were a little low if you ask me. First I wanted to look at how gender compares to all of the columns. 

![project 1.png]({{site.baseurl}}/img/project 1.png)

From the image above, we notice that in this dataset, there are more Male observations than Females. Also to find interesting, Women in this dataset were found to have a higher: 2nd Education Percentage,	Higher 2nd Education, Degree Percentage, and Master Percentage then men. But Men had higher, employability test and	 the salary they receieve are higher than the women. From doing outside research and prior knowledge, I've heard about the gender wage gap. The wage gap is the average difference between the payment for men and women who are working. Women are generally considered to be paid less than men. 

I started off playing with the data. I wanted to do some feature engineering so I changed renamed most of the columns to get a better understanding of the data and then I wanted to see the correlation between salary and the other columns. 

![featurees.png]({{site.baseurl}}/img/featurees.png)
![corr.png]({{site.baseurl}}/img/corr.png)

The correlations are showing how much your salary can increase by. Based on the results above, if you have a 2nd education (high school) your salary can jump up 53.8%. If you have graduated and are going back for your masters, you can earn an additional 14%. Based on experience, you might see your wage increase when applying for different jobs by maybe 30%. Seeing these numbers rise definetly shows how important education is to your salary. Without an education, it is very hard to make good money unless you have a concrete plan that has helped you. 

So, what can help determine the type of degree you'd like to get?

While working on my code, I ran a permutation importance graph. The degree type you would like to Specialise in will help increase you determine the degree type you'll get. Specialization happens after you complete your undergrad. The MBA percentage tells you the likelihood of a person to finish off school and get their masters. 

![Perm Graph.png]({{site.baseurl}}/img/Perm Graph.png)

We can see that higher 2nd education & how close you are getting your MBA can factor the degree type as well. Surprised that your regular degree percentage would matter less than your MBA percentage. Since, some people don't continue on with school. 




Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help. 
