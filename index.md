# About this project

There is a lot of misinformation about guns in the media coming from both sides of the aisle. It's hard to get unbiased information from any one source - but luckily for us, data doesn't lie.

I have taken it upon myself to collect data from multiple sources and compile it in one place, so that we can do a comprehensive analysis and take a look at the *facts*.

I will not pretend to be unbiased about this issue - but I have tried to present the data in an unbiased manner, and since all of the data and code used to analyze it is freely available, I invite you to look at it yourself.

Before we get to the graphs and data, lets go over some definitions.

* Automatic weapon: The firearm will continue to fire bullets as long as the trigger is depressed.
* Semi-automatic weapon: The firearm will fire one bullet per pull of the trigger. By far the most popular kind of the weapon in the United States, and most likely, the world.
* Assault weapon: a rather nebulous term used by the media to describe AR-15 style rifles. In military parlance, an assault rifle is a "select-fire" weapon, meaning it can switch between fully automatic and semi-automatic rates of fire. AR-15s, as purchasable by US citizens, are not "select-fire", as they only fire in semi-automatic mode.

All analyses are performed on data that is publically available, from reputable sources - typically government agencies, or the World Bank. Where I believe the sources are more spurious, I will tell you.

[Download the data (.xls)](https://github.com/gundata/Gat-Facts/raw/master/combined.xls)


## Gun Crime in the United States

Both gun homicides, and general homicides have experienced steep declines since 1995. Rates of gun homicides dropped 50% from the high of 1995 to the low of 2014, and have only slightly rebounded since then, mirroring the overall homicide trend in the United States.

There has been a [lot](https://www.vox.com/policy-and-politics/2018/2/21/17028930/gun-violence-us-statistics-charts) of [talk](https://www.npr.org/2016/01/05/462017461/guns-in-america-by-the-numbers) about the increasing number of guns owned by civilians in the United States. Several of these pieces draw a direct link between the number of guns, and rates of gun homicides, even going so far as to suggest that more guns = more gun homicides.

The data suggests otherwise.

![png](output_3_0.png)

![png](output_4_0.png)


## Are assault weapons really that deadly?

The rate of rifle homicides (including so-called "assault rifles") has dropped even quicker than general homicide rate. Despite all of the furor raised over civilian ownership of "assault rifles", less than 400 people have been killed with rifles (hunting, military, semiautomatic, etc) for the last 10 years.

The answer seems to be no. The overwhelming majority of homicides committed with firearms involve handguns.


![png](output_6_0.png)



![png](output_6_1.png)


## Mass Shootings

Data on mass shootings was collected from [Mother Jones US Mass Shooting Database](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/)

Mother Jones used the following criteria were used to define a mass shooting:
* The perpetrator took the lives of at least three people. 
* The killings were carried out by a lone shooter. (Except in the case of the Columbine massacre and the Westside Middle School killings, which involved two shooters.)
* The shootings occurred in a public place. (Except in the case of a party on private property in Crandon, Wisconsin, and another in Seattle, where crowds of strangers had gathered.) Crimes primarily related to gang activity or armed robbery are not included, nor are mass killings that took place in private homes (often stemming from domestic violence).
* Perpetrators who died or were wounded during the attack are not included in the victim counts.
* "Spree Killings": more than one location over a short period of time, that otherwise fit the above criteria.

___There have been only 97 mass shootings in the United States since 1982___

Processing on data was performed, with the following categorical terms lumped under semi-automatic rifles:
* Semi-automatic/semiautomatic rifle
* AR-15
* Assault rifle

Data on firearm homicides was collected from the [FBI Uniform Crime Reporting page](https://ucr.fbi.gov/ucr-publications)

I have selected the years since 1995 for this case study, since reliable data for some statistics tends to be harder to find for years prior to that (FBI crime reports, World Bank development indicators, homicide data, etc). 1996 was also the year that the Australian ban on semi-automatic weapons was implemented.


#### Semi-automatic rifle use in mass shootings

In the last 23 years (since 1995), there have been a total of 21 instances of mass shootings involving the use of semi-automatic rifles (also called "assault" rifles).  
In those 21 cases, a total of 229 people were killed. 160 (69%, expected: 19%) of those fatalities came from just four mass shootings:  

1. Las Vegas, 2017: 58
2. Orlando nightclub, 2016: 49
3. Sandy Hook, 2012: 27
4. Texas First Baptist, 2017: 26

#### Semi-automatic handgun use in mass shootings

Interestingly, in the same time span there have been 36 instances of mass shootings where only semi-automatic handguns were used.  
In these cases, a total of 267 people were killed. 85 (25%, expected: 11%) of those fatalities came from four mass shootings:  

1. Virginia Tech, 2007: 32
2. Killeen, Texas, 1996: 24
3. USPS, 1986: 15
4. Binghamton, 2009: 14

### Are mass shootings increasing in frequency?

Looking at the data, there is an increase in the number of victims of mass shootings, and the percentage of gun homicides from mass shootings. However, this increase is relatively small (accounting for approximately 0.5% of gun homicides), and is significantly smaller than the increase in defensive gun use by citizens

![png](output_9_0.png)
