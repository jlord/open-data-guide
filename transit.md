
#1 Question

Why open up transit data?

People want to know:

* When is the next bus/train? 
* Where is the closest stop/station? 
* How do I get from here to there using transit? 


#2 Standard
## Is there a standard?
    
###Yes! 
In fact, there are probably several...  
_(the following is shamlessly cribbed from [smarter people](http://transportation-camp-dc-2013.wikispaces.com/Transit+Data+Standards))_

- [GTFS](https://developers.google.com/transit/gtfs/reference) - The General Transit Feed Specification, originally developed by Google, contains static schedule information for transit agencies including: stop locations, route geometries and stop times;
- [GTFS-realtime](https://developers.google.com/transit/gtfs-realtime/) - GTFS-realtime contains real-time information related to vehicle positions, service alerts and trip updates (delays, cancellations, etc.);
- [SIRI](http://www.kizoom.com/standards/siri/) - The Service Interface for Real Time Information is a real-time data standard predominant in Europe, but making significant inroads into the US market, notably at MTA in New York. Recent change proposals to the SIRI standard include the definition of a structure for SIRI web services;
- [TCIP](http://www.aptatcip.com/) - The Transit Communications Interface Protocol is an APTA standard, sponsored by the US DOT. It has components which deal with passenger information and scheduling, as well as a whole host of other business divisions in transit;
- [NextBus](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) - A number of transit agencies employ the NextBus XML API to deliver real-time arrival information. While this standard is not as extensive as others, it still deserves mention on this list.

##Which one should I use?
```@TODO 
figure out why one should use one over the other
```

#3 How to publish
Depends on what kind of data you're looking to publish.

* API
```
explain benefits specifically, if it's realtime
explain formats
```
* File Download
```
explain downsides
explain appropriate uses (stop/route data?)
```



#4 Find your data
##Where should I look?
The best place to start would probably be with your transportation board.

```
other places that people have found that data inside of govt.
```

##Do they not have it?
It may be that the data you want to open is actually housed with a non-government agency. You may want to: 

* look into potential partnerships
* see if they already have an api that you can mirror/integrate

#5 Release it!
transform what you have to the standard you chose.
###tools for transforming
* commercial ETL
* open source ETL
* roll your own ETL





#is this becoming hugely painful?
Can't find the data?
###cost/savings conversation
This is probably a 
Data
##other things:
###consume your own data
```boilerplate
    This is the best way to ensure that the standard and quality of your data/api are maintained 
```
###tips for researching/liberating data

