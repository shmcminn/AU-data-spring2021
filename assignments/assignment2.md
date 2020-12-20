# Assignment 2: Collecting your own data.

Some great stories come out of reporters collecting their own datasets. Here are some examples:
* [Governors with very low approval ratings](https://fivethirtyeight.com/features/chris-christie-is-still-more-popular-than-governors-who-were-literally-criminals/)
* [Every Trump tweet insulting anything](https://www.nytimes.com/interactive/2016/01/28/upshot/donald-trump-twitter-insults.html)
* [White House visitors](https://www.politico.com/interactives/databases/trump-white-house-visitor-logs-and-records/index.html)
* [Emergency room bills](https://erbills.vox.com/)

## Assignment

Think about an area you're interested in, or one you may do your final project on, and come up with a dataset you wish existed. Then submit the following:

* A description of the question you're curious about, and an explanation about how this data could turn into a story. (Imagine this as your justification to your editor as to why this is worth your time)
* A list of the things you want to know about any data point
* An explanation of how you'd go about collecting that data (you don't actually have to do it on an ongoing basis, especially if it involves staking something out, just tell me how you would do it).
* A table **including at least five data points (rows)** that you've compiled of this dataset
* You can put your data in a google sheet (in which case, put the link in your homework) or make a table directly in the document you submit.
* Your dataset cannot be something you can just find elsewhere. For example, do not pick something like "all earthquakes above magnitude 7 in the US" because someone (the USGS) already has exactly that data collection. If you want to do earthquakes, add more information such as the number of injuries and deaths reported in the media, and possibly include a link to the relevant media report as one of your columns.
* Submit this assignment as `assigment2.md`

## Can we have an example?

### Sure

It seems to me there's been an uptick in the number of protest-related arrests in Washington. I'd like to know if this is actually the case or just the result of more news coverage, and whether it's driven by a particular ideology or type of arrest (i.e. trespassing vs. violent crime).

To compile, I would search for arrests related to each protest in D.C. over the last two decades. As a *starting point*, I would use this list of protests from [Wikipedia](https://en.wikipedia.org/wiki/List_of_rallies_and_protest_marches_in_Washington,_D.C.).

Here are the features I'll be collecting, and an explanation of why:

* Date
* Time of arrest (possibly more violence-related arrests happening later at night)
* Protester affiliation (to see if we can compare groups)
* Protester political affiliation (my best attempt at classifying them as "right"/"left"/"other," also for comparison)
* Reason for arrest 
* Prosecuted? (to see if cases were dropped and crimes perhaps weren't as serious)
* Link to source document (i.e. news coverage, arrest record from police, etc)

The first five rows of the data table would look like this:

Date | Time | Affiliation | Political_Affiliation | Reason | Prosecuted | Source
---- | ----- | ---- | -------- | ----------- | -------------- | ----------
tk | tk | tk | tk | tk | tk | tk
tk | tk | tk | tk | tk | tk | tk
tk | tk | tk | tk | tk | tk | tk
tk | tk | tk | tk | tk | tk | tk
tk | tk | tk | tk | tk | tk | tk


*you actually have to collect 5 datapoints from your proposed dataset -- this is just an example with TKs*