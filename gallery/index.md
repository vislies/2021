---
layout: default
gallery-nav:
  - title: Stop, Go, and Not Stop
    url: "#stop-go-and-not-stop"
  - title: Not the Flu
    url: "#not-the-flu"
  - title: A Bigger Pool
    url: "#a-bigger-pool"
---

# VisLies 2021 Gallery

It was another great year of lies.
Unfortunately, COVID-19 once again prevented us from meeting in person.
But, nevertheless we were able to meet virtually and share the fun VisLies we found during the previous year.


## Stop, Go, and Not Stop

<a href="stop-go-and-not-stop.jpg" class="image-right">
<img src="lie.png" class="lie" />
![](stop-go-and-not-stop-thumbnail.jpg)
</a>

[Ken Moreland] has had diseases on his mind, so he started us off with this interesting example showing us prevalence of hepatitis A antibodies.
This graphic features a [choropleth map] with 4 color categories: High, Intermediate, Low, Very Low.
These categories have a clear order.
However, take a close look at the colors chosen.
The red, yellow, and green colors are a standard set of colors that most people will grok meaning from.
But while red is used for "high", a very similar orange is used for "very low".
Why are to two values at the opposite have almost identical colors?
It makes the lowest values look like the highest values.

[Ken Moreland]: http://www.kennethmoreland.com/
[choropleth map]: https://en.wikipedia.org/wiki/Choropleth_map


## Not the Flu

<a href="coronavirus-vs-flu-pie.png" class="image-right">
<img src="lie.png" class="lie" />
![](coronavirus-vs-flu-pie-thumbnail.jpg)
</a>

Of course, the disease that is on all of our minds is COVID-19.
[Ken Moreland] next presented this graphic, which was originally features in a [_Time_ magazine article] and later highlighted in [a blog post by Stephen Tracy].
The graphic is showing a series of pie charts showing the fraction of fatal cases per viral infection.

The article observes that the measured mortality rate of COVID-19 is closer to the seasonal flu than to other recent more deadly viruses like SARS and MERS concluding that "Even when taking the current estimated global mortality rate of 3.4% at face value, COVID-19 looks more like influenza than other once-novel coronaviruses."
That, unfortunately, has proven to be gravely untrue.
As of November 2021, there have been over 250 million COVID-19 deaths worldwide.
This staggering number far exceeds the [total number of SARS deaths during the 2003 outbreak] (774), the [total number of MERS deaths] (888), and [estimated global seasonal influenza deaths] (290,000 -- 650,000 per year).

What went wrong?
One problem is that the comparison of fatality rates between COVID-19 and seasonal flu are somewhat uncomparable.
Flu fatality is averaged over years of observation whereas at the time of this article COVID-19 there were only a few months of preliminary data.

But a bigger issue is that the measurement presented in the graphic, percentage of fatal cases, might not be indicative of the total number of fatalities.
To total number of fatalities is determined by both the case fatality rate _and_ the infectivity rate (typically measured by the [R-naught value]).
A disease with a 100% case fatality might not actually kill a lot of people if it does not spread well.
In fact, a high fatality might lead to a lower infection rate because victims die before infecting others.


## A Bigger Pool

<!--
The previous VisLie was actually dated.
This visualization was formed at the beginning of the COVID-19 pandemic when there was neither much understanding nor data available.
So, we can forgive those hopefuls that were overly optimistic.

But what of today?
After a year worth of data collection and research, the COVID-19 pandemic, its dangers and recommendations for it, is still a divisive topic.
Surely, there 
-->

<a href="https://drive.google.com/file/d/1zXBaNe-TrmmnN3XNNYzuvgCoegmbYpVR/view?usp=sharing" class="image-right">
<img src="lie.png" class="lie" />
![](covid-choropleth-thumbnail.jpeg)
</a>

Continuing on the theme, [Ken Moreland] presented this simple [choropleth map] demonstrating the number of confirmed COVID-19 cases in the US.
On the surface, this seems like a straightforward representation.
But on closer inspection, there is a serious problems.

All the numbers are given in terms of absolute cases since the beginning of the pandemic.
This is misleading for 2 reasons.
First, this is heavily biased toward the population of the region.
Higher populations will naturally have larger numbers even if the infection rate is about the same.
The infections in several of the highly populated states are larger than the entire population of Wyoming.
The second problem is that the numbers combine an accumulation of a years worth of data.
That's OK for some questions, such as a post-mortem of the policies from start to end.
But this might not be very indicative of how things are right _now_.
This includes many cases at the beginning of COVID-19 where conditions were very different.

<div class="image-stop" />

<a href="https://drive.google.com/file/d/1DtBMt9HftF5kHJpB7oyxjJEztKJs0691/view?usp=sharing" class="image-left">
![](covid-choropleth-better-thumbnail.png)
</a>

In contrast, here is a similar map that corrects these two problems.
This map provides numbers per capita and on a sliding 7 day window.
Where in the first map, CA, TX, and FL were all near the top of the infection rates, recent per capita data says that the CA infection rate is way down, TX is in the middle, and FL (the lowest of the 3) is currently one of the worst in the country.
I also note that some more sparsely populated areas like West Virginia and the Dakotas look pretty good by absolute numbers but not so great per capita.

It should be pointed out that some VisLies participants noted that the color scale of this plot is a little weird.
The ranges are oddly precise, there are also odd gaps between each region, and the range for each color is inconsistent.
Likely, the states and territories were divided into 6 even(ish) groups.

<div class="image-stop" />

<a href="https://drive.google.com/file/d/1rCpfrF8bhWgYx8CwFYzfcNeuzhR8Osrj/view?usp=sharing" class="image-right">
![](correlations-karen-territory-thumbnail.jpg)
</a>

So, what is so bad about providing data that is not scaled per capita?
This pithy infographic does a great job describing just what can go wrong.
In a nutshell, a count of just about anything related to people will be proportional to the population count.
This means pretty much anything can be "proven" despite how rediculous the relationship might be.


[_Time_ magazine article]: https://time.com/5798168/coronavirus-mortality-rate/
[a blog post by Stephen Tracy]: https://analythical.com/blog/covid19-in-charts
[total number of SARS deaths during the 2003 outbreak]: https://www.who.int/publications/m/item/summary-of-probable-sars-cases-with-onset-of-illness-from-1-november-2002-to-31-july-2003
[total number of MERS deaths]: https://applications.emro.who.int/docs/WHOEMCSR471E-eng.pdf?ua=1
[estimated global seasonal influenza deaths]: https://www.who.int/influenza/Global_Influenza_Strategy_2019_2030_Summary_English.pdf
[R-naught value]: https://globalhealth.harvard.edu/understanding-predictions-what-is-r-naught/
