---
layout: default
gallery-nav:
  - title: Stop, Go, and Not Stop
    url: "#stop-go-and-not-stop"
  - title: Not the Flu
    url: "#not-the-flu"
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

[_Time_ magazine article]: https://time.com/5798168/coronavirus-mortality-rate/
[a blog post by Stephen Tracy]: https://analythical.com/blog/covid19-in-charts
[total number of SARS deaths during the 2003 outbreak]: https://www.who.int/publications/m/item/summary-of-probable-sars-cases-with-onset-of-illness-from-1-november-2002-to-31-july-2003
[total number of MERS deaths]: https://applications.emro.who.int/docs/WHOEMCSR471E-eng.pdf?ua=1
[estimated global seasonal influenza deaths]: https://www.who.int/influenza/Global_Influenza_Strategy_2019_2030_Summary_English.pdf
[R-naught value]: https://globalhealth.harvard.edu/understanding-predictions-what-is-r-naught/
