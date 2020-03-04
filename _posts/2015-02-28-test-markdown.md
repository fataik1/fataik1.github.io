---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge:
  - star
  - fork
  - follow
tags:
  - test
comments: true
published: true
---

A lot of people are not content with the amount of hours they sleep per night. Throughout your week, you might hear a few people complain that they are tired or they didn't sleep enough. You might even hear others express how energized they are for the day to begin. The truth is, sleep can dictate the way your day might lay out in front of you and even what you do before sleep contributes. 

I found my data off the website [https://www.kaggle.com/mlomuscio/sleepstudypilot](https://www.kaggle.com/mlomuscio/sleepstudypilot). This was a fantastic way to test my skills I've been learning. The csv.file I used contained a dataset with 104 observations and 6 columns of sleeping habits to determine if students were satisfied with the amount of sleep they get. Upon downloading this data and cleaning it up a bit, I was able to find out a few observations. It seems like most people are on their phone before they sleep and have their phone in arms reach. 

![head.png]({{site.baseurl}}/img/head.png)

After cleaning the data and assigning 0 or 1 for yes and no, I was able to get a graph to see all of this data. 

![Questions.png]({{site.baseurl}}/img/Questions.png)


In this image below, I wanted to see if people were content with the amount of hours they were getting. 64 people insisted that they did not recieve enough sleep while 38 insisted they got enough rest. 

![Enough Data.png]({{site.baseurl}}/img/Enough Data.png)

Throughout the day, we use a lot of energy as humans. I would like 

Next, we can look at different ways we can effect our sleep by not even knowing. We conducted a survey and we wanted to see how many people slept with their phone in arms reach and how many hours they slept.

![PhoneReach Hrs.png]({{site.baseurl}}/img/PhoneReach Hrs.png)
Majority of the people had their phones in arms reach. 71 people said yes while 31 said no. You might be wondering now if you sleep with your phone in an arms reach. There is no major difference between hours slept if you had your phone near you or not. 

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
